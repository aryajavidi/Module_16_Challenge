# Module_16_Challenge

## Linear Regression to Predict MPG

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

The variables that provided us with a non-random amount of variance to the mpg values in this dataset were vehicle weight, spoiler angle, and AWD. The variables that provided us with random variance were ground clearance and vehicle length. 

### Is the slope of the linear model considered to be zero? Why or why not?

The slope of the linear model is not considered to be zero. The P-value is less than 0.05

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The R-Squared of this model is .71, which is a strong correlation for the dataset. This tells us that approximately 71% of the time, this model will predict mpg values correctly, making this an effective model for predicting the mpg of MechaCar prototypes. This value could be skewed as other factors that were not included in the dataset and model could potentially change the variability of the mpg and thus the effectiveness of the model. 

## Summary Statistics on Suspension Coils

### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

I have included images of the summary statistics of the manufacturing lots below.
![1](https://user-images.githubusercontent.com/69175360/210922795-3defc67f-f1af-4f07-b85f-2022a1c51010.JPG)
![2](https://user-images.githubusercontent.com/69175360/210922842-09a14edc-08a0-4c91-aca0-923370a14284.JPG)

The current manufacturing data meets the design specification, with the variance of the total manufacturing lot. Lot 3 has a variance of 170, and individually does not meet the design specifications stated (exceeding 100). Lot 1 and 2 have much lower variance, meeting the requirements for the design specification. 

## T-Tests on Suspension Coils

In your README, create a subheading ## T-Tests on Suspension Coils, then briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.


Lot 1: p-value = 1, alpha = .05

1 > .05, which means Lot 1 is not statistically significant from the normal distribution and normality can be assumed. The mean falls within the 95% confidence interval.

![3](https://user-images.githubusercontent.com/69175360/210922900-715752de-e30a-454b-8b2b-88eec98da082.JPG)

Lot 2: p-value = .6072, alpha = .05

.60 > .05, which means Lot 2 is not statistically significant from the normal distribution and normality can be assumed. The mean falls within the 95% confidence interval.


![4](https://user-images.githubusercontent.com/69175360/210922941-00b7708e-9516-46e3-863a-cc7d90c19ee2.JPG)

Lot 3: p-value = .04168, alpha = .05

.04 < .05, which means it is statistically significant from the normal distribution and normality cannot be assumed. However, the mean falls within the 95% confidence interval.

![5](https://user-images.githubusercontent.com/69175360/210922989-daa2a3d9-a38c-4d8f-8472-7852d1b9f631.JPG)

## Study Design: MechaCar vs Competition

I believe that the fuel efficiency, safety rating, and horse power would be important metrics to test. The null hypothesis is that the MechaCar is no different from the competition in terms of fuel efficiency, safety rating, and horse power. The alternative hypothesis is that there are differences in these three areas.  I would perform a multiple linear regression summary to show the differences between MechaCar and several different competitors in regards to their safety rating and fuel efficiency. I could use t test. In order to run this statistical test, I would need a random sample of MechaCars and different competitors that included their safety ratings and fuel efficiency.



