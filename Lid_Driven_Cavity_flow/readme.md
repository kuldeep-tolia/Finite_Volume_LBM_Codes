Problem Description:  

-> Lid-driven cavity is a standard test case with reference data available in the literature.  
-> Here, a FVM-based LBM solver is presented utilizing cell-centered approach on a uniform Cartesian grid.  
-> Boundary conditions:  
- Velocity bc: no-slip stationary walls $\left( u = v = 0 \right)$, top plate imposed with uniform velocity $\left( u = U, v = 0 \right)$    
- The top plate velocity $U$ must be chosen such that it satisfies the incompressible limit for LBE, i.e., Mach number $Ma < 0.13$.  
- Pressure boundary condition: Homogenous Neumann boundary condition at all walls $\frac{\partial p}{\partial n} = 0$  
 
-> The domain size considered is $H \times H$.   
-> The top wall velocity is governed by the Reynolds number, defined as $Re = U h / \nu$.  
-> The results for the cases $Re = 100$ and $Re = 400$ are compared with the reference data available in the literature.  

Reference: Ghia, U. K. N. G., Ghia, K. N., & Shin, C. T. (1982). High-Re solutions for incompressible flow using the Navier-Stokes equations and a multigrid method. Journal of computational physics, 48(3), 387-411.  
