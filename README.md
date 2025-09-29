# Probabilistic-Inference-and-Particle-Filter

This project was developed as part of the Artificial Intelligence course.  

1. Bayesian Network Inference
   - Exact inference via elimination
   - Approximate inference via Rejection Sampling and Gibbs Sampling 
   - Comparison of results with histograms, showing mean, standard deviation, and true probability

2. Particle Filter
   - State estimation of an object moving along a 1D line  
   - Motion model: stochastic velocity with drift μ and Gaussian noise  
   - Measurement model: Laplace noise with possible sign inversion (5% probability)  
   - Implemented particle filtering with three resampling strategies:
     - No resampling  
     - Resampling at every step  
     - Conditional resampling (effective sample size test)  
   - Evaluation via Monte Carlo simulations (100 runs), comparing RMSE of estimated position
