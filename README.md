# MechaCar_Statistical_Analysis

## Overview


## Deliverable 1: Linear Regression to Predict MPG
Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Vehicle weight, spoiler angle, and AWD provided a non-random amount of variance.

Is the slope of the linear model considered to be zero? Why or why not?
The slope is not zero. This was based on the p-value, 5.35e-11, which is far less than even an extreme significance level of 0.0001. This means that we can reject the null hypothesis.

Does this linear model predict mpg of MechaCar protoypes effectively? Why or why not?
This linear model has an r-squared value of 0.7149, which means that approximately 71% of all mpg predictions will be determined by this model. This indicates that it is an effective prediction model.

## Deliverable 2: Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Overall the manufacturing data meets the required design specifications as the total summary variance is only 62.29 PSI. When looking at individual lots, Lot 1 and Lot 2 meet requirements with variances of 0.98 PSI and 7.47 PSI respectively. However, Lot 3 fails to meet requirement by a considerable margin with a variance of 170.29 PSI.

## Deliverable 3: T-Tests on Suspension Coils


## Deliverable 4: Study Design (MechaCar vs. Competition)
For there to be a comparison between MechaCar and it's competitors, key metrics need to be chosen and analyzed between them. One key metric for consumers is fuel efficiency. For this study, the city and highway MPG for MechCar and it's competitors would be used. The test will determine if there is a statistically significant difference between the MPG averages of MechaCar and its competitors. 

The null hypothesis is that the metrics do not vary signficantly between the competition and MechaCar. The alternative hypothesis is that MechaCar does vary signficantly from it's competitors'. A T-test would be used to determine if there is a statistical significant difference in the average (highway and city) MPG for MechaCar and similar models from their competitors'. For the study, I would recommend a dataset of 500 cars, where 50 cars are used from each model. This would give a dataset size of 500, which would be a good sample size to determine if there is a significant difference. 

