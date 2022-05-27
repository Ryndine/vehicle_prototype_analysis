# Vehicle Pototype Analysis

## Objective: 
Run statistical analysis on a vehicle dataset.

## Tools & databases used:
- R Studio

## Analysis:

**Linear regression to predict mpg**  
There seems to be a relation with the vehicle weight in which it may have slightly added variance to the mpg values, however with a significance level of 0.05 it does not seem to be significant. The  p-value and hypothesis test result was 5.35e-11 which is msaller than our 0.05 significance level, therefore the slope of the linear regression model is not considered zero. With a 0.71 r-squared value we can say that 71% of the time we can predict the mpg correctly. This is a fairly good model for predicting mpg. There are likely more variables to consider but I lack the additional data for.

**Summary statistics on suspension coils**  
It seems upon analysis that Lot 1 and Lot 2 have the same calculated mean and median, which means they're both within the specifications we desire. Lot 3 seems to have higher variables than the other lots. The caculated variance exceeds our specifications. However, if all lots are combined and we analysis the total data, the overall variance is within specifications.

**T-tests on suspension coils**  
Upon analyzing each one-sample t-test we can see that Lot 1 and Lot 2 PSI values are similar to the population mean. Lot 3 p-value is below the significance level, with a p-value of 0.041. This means our Lot 3 mean PSI is different than the population mean.
