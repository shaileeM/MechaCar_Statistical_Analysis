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


## T test analysis for whole data on PSI value
Null hypotheses : Mean of PSI is not equal to 1500
Here p value is less than 0.05 hence we have enough evidence
to reject our null hypotheses 
This means mean is equal to 1500 (here nean is 1498.78)

## T test analysis for each lot on PSI value
Null hypotheses : Mean of PSI is not equal to 1500

Lot 1 : p value(2.2e-16) is very less than 0.05 
Lot 2 : p value(2.2e-16) is very less than 0.05 
Lot 3 : p value(2.2e-16) is very less than 0.05 

All the 3 means are almost equal to 1500 and p is < 0.05 hence we have enough evidence to reject our null hypotheses


## Study Design: MechaCar vs Competition
The metrics of interest for the consumer can be following : 
1. braking power(Data for breaking power will be in Watts)
Null hypotheses : The breaking power for mechaCar is more than the competitor cars.
As the data is numerical, we can use t- test to find the p value which may support or reject our null hypotheses. 

We need list of breaking horse powers for both the type of cars.

2. Hatchback cars for MechCar 
Null hypotheses : The mileage of hatchback cars for MechaCar is higher than the mileage of hatchback cars of competitor company. 
Here as the data is categorical/non numeric, we will use chi-squared test to prove our hypothesis. 

We need a column for hatchback car with values are True or False. 

3. Time versus tyre pressure
Null hypotheses : As time/year passes the tyre pressure decreases by half
Here we will be using linear regression. After we get the p value and the r squared value, we can determine what is the strength of 
correlation and in what direction(positive/negative).
We can also determine the probability of how random our data is based on the Pr(>|t|)
