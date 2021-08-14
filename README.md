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