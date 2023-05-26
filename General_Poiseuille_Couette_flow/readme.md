Problem Description:

-> The problem can be defined as a fluid confined between two infinite, parallel plates separated by a distance $h$.  
-> The flow is driven by constant pressure gradient, $\frac{d P}{d x}$, and with a moving top plate.    
-> The applied pressure gradient can be an adverse pressure gradient or a favourable pressure gradient.  
-> The analytical solution for the described problem can be written as follows:  

$$ \frac{u}{U} = P \frac{y}{h} \left( 1 - \frac{y}{h} \right) + \frac{y}{h}$$

where $U$ is the top plate velocity, $h$ is the plate separation distance, $\mu$ is the dynamic viscosity of the fluid, and $P$ is non-dimensional pressure gradient and is defined as   

$$P = - \frac{h^2}{2 \mu U} \left( \frac{d P}{d x} \right)$$

-> The domain size considered is $2h \times h$.  
-> No-slip velocity boundary conditions are applied on the walls, whereas periodic boundary condition is considered in the streamwise direction.  
-> The top wall velocity is governed by the Reynolds number, defined as $Re = U h / \nu = 15$.
