# 2D Finite-Elements-Method
This is an implementation of the finite elements method, which is applied on a 2-dimensional boundary value problem with Dirichlet boundary conditions.


## requirements and installation 
 - Python 3.12.0
 - numpy 1.26.1
 - scipy 1.11.3
 - matplotlib 3.8.1
   
Will probably work with newer version of the packages listed above.
Simply run the python notebook.
## Explanation
We are given the 2-dimensional boundary value problem with dirichlet conditions 

$$
\begin{cases}
-\Delta u = f \quad \text{in} \quad  \Omega = (0,1)^{2}, \\
u = 0   \quad \text{on} \quad \delta \Omega, 
\end{cases}
$$

where $f(x,y) = 10\sin(3\pi x) sin(\pi y)$.

We calculate an approximate solution of this BVP using the finite elements method with piecewise linear basis functions. For comparison, we plot the approximate solution $u_n$ and the exact solution $u(x,y) = \sin(3\pi x) \sin(\pi y)$. 


