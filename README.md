# MechaCar_Statistical_Analysis

## Deliverable 1: Linear Regression to Predict MPG
![Devliverable1](/images/Deliverable1.png)

##### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Vehicle Length (vehicle_length) and Ground Clearance (ground_clearance) are statistically unlikely to provide random amounts of variance to the linear model. 

Vehicle Length p-value = 2.60e-12 
Ground Clearance p-value = 5.21e-08

This indicates they are both statistically significant on MPG.

##### Is the slope of the linear model considered to be zero? Why or why not?

The p-value is below a significance level of 0.05%, meaning the slope of this model is not zero, so we reject the null hypothesis.

##### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The R-squared value for this model is 0.7149 which means 71.5% of observed variations can be explained by this model.This is a good model to predict MPG.


## Deliverable 2: Summary Statistics on Suspension Coils
![Devliverable2](/images/deliverable2.png)
![Devliverable2_2](/images/deliverable2_2.png)

##### Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
The overall variance for all lots is 62.29 PSI.

Lot 1 variance = 0.979 PSI 
Lot 2 variance = 7.5 PSI

- both meet design requirements
- Suspension coils from Lot 3 variance = 170.27 PSI, outside of design requirements.

## Deliverable 3: T-Tests on Suspension Coils

##### Total of Three Lots t-test:

- P-Value for all lots is 0.06028 which is above our significance level of 0.05 
- fail to reject null hypothesis
![devliverable3](/images/deliverable3.png)

##### Lot 1 t-test

- P-Value for Lot 1 is 1, above our significance level of 0.05
- fail to reject null hypothesis


##### Lot 2 t-test

- P-Value for Lot 2 is 0.6072, above our significance level of 0.05
- fail to reject null hypothesis
![Devliverable3_2](/images/deliverable3_2.png)

##### Lot 3 t-test

- P-Value for Lot 3 is 0.04168, below our significance level of 0.05
- reject null hypothesis

