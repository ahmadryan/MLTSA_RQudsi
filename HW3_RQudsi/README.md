# Solution to assignment 3

### HW3 solution

The file titled **HW3_RQUDSI.ipynb** gives the solution to the problems of 
assignment 3. The solution was developed from a skeleton ipython notebook file
 provided by the professor. Work was done along with the class mate Amey Rachel.

#### Describing what we did

In this assignment we learnt to do various things.
 1. We learnt how to implement the **Facebook Prophet** package for the 
 purpose of forecasting. In this case we used the data of total number of 
 Uber riders for six months (from April to September) for the year 2014.
 The data was avaraged daily and then plotted along with various different 
 methods of forecasting.
 2. In the first case we just looked at the number of daily rides and made the 
 forecast as well as prediction for one month (October).
 3. In the second case we used the same package but added the two weather 
 parameters (daily average temperature and daily mean rainfall). This 
 improved the model as evident from the improvement in the $\chi^2$ value
  which changed from 0.460 to 0.458.
 4. The third case added one more parameter, US Holidays, to the regression 
 and we see the continuing improvement in the $\chi^2$ value which decreased to
  0.421.
 5. We implement the Markov Chain Monte Carlo optimization based on full 
 Bayesian formulation for the same three cases as done for the Facebook 
 Prophet model and we observed that the $\chi^2$ changed from 0.561 for the 
 simplest case to 0.497 for the case where we considered the effect of weather 
 as well as US Holidays.

#### Contribution detail

Part one of the assignemnet was done on my own.
Model 2 and further parts were done with Amey Rachel with equal contribution 
from both in each section.
