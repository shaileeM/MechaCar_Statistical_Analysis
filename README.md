# MechaCar_Statistical_Analysis


## Linear Regression to Predict MPG
1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

From the data, Vehicle length is the most non-random value followed by ground clearance. Vehicle length has the smallest probability
value of 2.60e-12.

2. Is the slope of the linear model considered to be zero? Why or why not?
Here our null hypothesis is : There is no relation between mpg to the other numerical values such as vehicle length,weight, etc. 
Our p value is 5.35e-11 which is significantly lower than 0.05, hence we have sufficient evidence to reject our null hypothesis which means
there is some relation between mpg to other numerical values. 

Hence the value of slope will be non zero. 

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Yes the linear model of MechaCar prototypes is effective as the combined pearson corelation coefficient(r) is 0.82.
As it is greater than 0.7 it is "Strong"

## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not 
exceed 100 pounds per square inch. 
Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? 
Why or why not?

Lot 1 and Lot 2 meets the design specification and variance does not exceed 100 pounds individually.
In total , all the lots combine meet the design specification as the variance is 62 < 100. 