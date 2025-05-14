# Image-Denoising
Mini project exploring Bayesian image denoising using statistical physics: Metropolis Hastings sampling and the Ising Model. The main goal of the project is to practice the concepts I studied at University of Waterloo and Bishop's University. The purpose is to denoise a binary image that has been corrupted by random noise, using a prior that favors smoothness, or agreeing with neighboring pixels and a likelihood based on how well the pixel agrees with observed data. 

# Overview
**Input**: a clean binary image with a central white square, corrupted by random noise.
**Model**: Ising and Bayesian inference.
**Sampling**: Metropolis-Hastings algorithm ( Markov Chain Monte Carlo ).
**Output**: a denoised image that balances prior smoothness and observed data.

# Notes
**Prior**: Neighboring pixels tend to have the same value.
**Likelihood**: Noisy observations still contain useful info. 
- Each pixel is treated like a spin (+1 for white and -1 for black)
- Nearby pixels or spins want to align, mimicking **magnetic interactions**.
- The Metropolis algorithm flips the pixels probabilistically based on an energy change function.

# References and Acknowledges
While developing the project, I referenced online tutorials, AI, and academic materials.
( Unfortunately, I didn't keep track of every link but if you recognize the material and you'd like credit, please reach out! ) 

# Reflections
This project was an intro to other MCMC projects I would like to successfully execute but for now it helped me to connect ideas from machine learning, statistical physics, and Bayesian statistics in a hands-on way. It also helped me to reinforce my understanding of how physical models can be repurposed for computer tasks.

