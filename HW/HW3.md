# HW 3
## Rebekah Grant - A02297991

### Question 1

For the example problem, 
$$u^{"}(x)= f(x)$$
with $f(x)= cos(\frac{3 \pi}{2}x)$ and boundary conditions $u(0) = 0$ and $u(1) = 1$, complete a computational convergence analysis. Use the sequence of h values, 

### Question 2- graphics

Using Matplotlib (or equivalent) graph the solutions obtained in the computational convergence study.

### Question 3- An alternative method

The finite difference scheme can be changed by including an alternative difference quotient. Use the code written in Assignment/Homework 1 to produce coefficients for a fourth order derivative approximation of $u^{"}$. Use a centered difference quotient. Describe problems that occur at the boundaries of the domain. How does the alternate method incorporate the boundary conditions? If a reflection condition is applied at the boundary points, determine if this effects the accuracy of the approximation.
 
### Question 4

Use your code from Assignment/Homework 1 to produce a fourth order difference that stays within the domain at the boundaries and use the foruth order central difference at points where possible. Discuss how the matrix structure is effected. What advantages are there to using the Jacobi iteration method over a Gaussian elimination approach?