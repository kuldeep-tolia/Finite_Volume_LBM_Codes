-> This repository contains FVM codes for solving Boltzmann equation using cell-centered structured grid approach to study the incompressible and laminar flows.    
-> The present solver can achieve second-order spatial accuracy and first-order temporal accuracy.  
-> A cell-centered control volume appraoch is adopted in the present solver.  
-> For the spatial discretization, $2^{nd}-$ order Upwind Difference scheme is used to obtain the value of the particle distribution function at the cell faces, and the gradients of the particle distribution function is computed using the $2^{nd}-$ order explicit CDS.  
-> The solution is marched in time using the $1^{st}-$ order Euler-explicit forward scheme.  
-> The source term formulation proposed by Ref. [1] is used.  
-> For the boundary condition treatment, ghost cell approach is used rather than the conventional bounce-back scheme appraoch.  
-> For further details, interested readers are adviced to read the following articles [2] and [3].
-> Two benchmark test cases are presented here: Poiseuille-Couette flow and Lid-driven cavity flow.  

References:  

[1] Guo, Z., Zheng, C., & Shi, B. (2002). Discrete lattice effects on the forcing term in the lattice Boltzmann method. Physical Review E, 65(4), 046308.  
[2] Wang, Y., Zhong, C., Cao, J., Zhuo, C., & Liu, S. (2020). A simplified finite volume lattice Boltzmann method for simulations of fluid flows from laminar to turbulent regime, Part I: Numerical framework and its application to laminar flow simulation. Computers & Mathematics with Applications, 79(5), 1590-1618.  
[3] Shrestha, K. (2015). Simulation of wall-bounded turbulent convective flows by Finite Volume Lattice Boltzmann Method (Doctoral dissertation, Lille 1).
