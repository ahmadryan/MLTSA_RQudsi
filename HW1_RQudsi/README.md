# Solution to assignment 1

### HW1 solution

The file titled **HW1_RQudsi.ipynb** gives the solution to the problems of 
assignment 1. The solution was developed from a skeleton ipython notebook file
 provided by the professor. Work was done exclusively by RQ on this.

#### Describing what we did

In this assignment, we fit a power law to the flux received from a gamma-ray
 burst (GRB) using four different methods which are:
 1. Solving the analytical equation in python
 2. Using sklearn package to solve the analytical equation.
 3. Using L1 minimization.
 4. Using chi-square minimization, which takes into account the error in measuremnt.
 
 We do so by fitting a straight line on a log-log plot with time on the x-axis 
 and magnitude (used as a proxy to flux) on y-axis.

 The values of parameters using four methods changes only by a little amount, 
 which is verified from the small values of standard deviation in both slope 
 and intercept ( 0,07 and 0.18 respectively). Though it has not been shown in 
 the present notebook, but it was found that changing the initial guess does 
 not affect the final value of the solution.

### HW1 extra credit solution solution

The file titles **HW1_ExtraCredit_RQudsi.ipynb** gives out the solution for 
the extra credit problems. The work was done exclusively by RQ.
 
#### Describing what we did

In this assignment, we solve the analytical equation for finding the best fit 
line while taking error in the measurement into consideration. This introduces 
covriance matrix in the equation leading to a slightly complicated computation.
 However, an advantage of this is that we can compute error in the fit 
 parameters as well.

 We see the affect of outliers on the result and how the error in the fit 
 parameters increases in the presence of outliers.
