# R_Analysis
Learning how to analyze vehicle data using R and statistics.

## Overview
A special project had been brought up to Jeremy by upper management. Production issues were plaguing the MechaCar, the most recent prototype from AutosRUs' Manufacturing Team. Jeremy and his team were instructed by AutosRUs' upper management to analyze the production data and uncover trends that will benefit the manufacturing division.

## Linear Regression to Predict MPG
- In this investigation, non-random deviations were primarily caused by the spoiler weight, vehicle angle, and AWD. The two most important variables in terms of random variance are ground clearance and vehicle length.

- Our slope is not zero, as can be seen by the fact that the p-value is less than 0.05.

- The R-square of 0.71 indicates that changes in vehicle length, weight, spoiler angle, drivetrain, and ground clearance account for 71% of mpg variances. The mpg of MechaCar prototypes can be roughly predicted using this linear model.

## Summary Statistics on Suspension Coils
- The suspension coils of MechaCar are intended to vary by no more than 100 pounds per square inch. With a global variance of 62.3 psi, the manufacturing batches consistently adhere to the design specifications. Lot 1 and Lot 2 both meet specifications, with variances of 0.98 and 7.5 psi, respectively. Lot 3 is outside of specifications with a 170.3 psi variance.

## T-Tests on Suspension Coils
- The p-value of 0.45 exceeds the significance level when using the conventional 0.05 percent level of significance. The PSI over all manufacturing lots is statistically equivalent to the population mean, as there is insufficient data to refute the null hypothesis.

## Study Design: MechaCar to the Competition
- The performance of MechaCar is intended to be on par with or better than that of automobiles found in the general market. The best way to accomplish this goal is to make improvements to the MechaCar's safety features, pricing, and fuel efficiency. Data must be gathered for all MechaCar production designs in addition to the six factors from this research.
- In this scenario, ANOVA would be utilized. In this test, a continuous numerical variable is compared between different groups. Therefore, for this research, we would compare the means of each statistic among manufacturers.
