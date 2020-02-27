# Solution to assignment 2

### HW2 solution

The file titled **HW2_RQUDSI.ipynb** gives the solution to the problems of 
assignment 2. The solution was developed from a skeleton ipython notebook file
 provided by the professor. Work was done exclusively by RQ on this because no 
 one else volunteered to work with him.

#### Describing what we did

In this assignment we learnt to do various things.
 1. How to read and download data from an online data source called **kaggle**
 2. We also learnt how to carry out several operations like computing 
 correlation and plotting the scatter matrix
 3. We read data from the first 10 files of a specific folder, and carried out
 the stationarity test on all the data and found that except for one dataset, 
 all the datasets were non-stationary, based on the threshold we set, which 
 p=0.05.
 4. We implemented the ARMA method on the stationary file and computed the 
 optimal paramters by recursivvely computing the AIC value for each parameter 
 and choosing the values for which AIC was minimized. For this case we found 
 that the AIC was minimized for (1,1).
 5. We then selected two other datasets, those between which correlation was 
 minimum, after dropping the stationary dataset from the lsit.
 6. We carried out the ARIMA model and computed the optimal paramters for 
 each of the dataset and plotted the result alongwith a brief discussion about 
 the coeeficients.
