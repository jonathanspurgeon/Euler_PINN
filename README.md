Despite the significant progress over the last 50 years in simulating flow problems using 
numerical discretization of the Navier–Stokes equations, we still cannot incorporate 
seamlessly noisy data into existing algorithms, mesh-generation is complex, and we cannot 
tackle high-dimensional problems governed by parametrized NSE. We implement
physics-informed neural networks physics-informed learning by integrating data and exisiting mathematical models. We investigate the 
possibility of using physics-informed neural networks to approximate the Euler 
equations that model high-speed aerodynamic flows. In particular, we solve the forward two-dimensional
Riemann problem. We utilize the Euler equations and simulation data to 
formulate the loss function. We demonstrate the effectiveness of PINNs in capturing the 
highly dynamic solutions with only scattered points clustered randomly.
