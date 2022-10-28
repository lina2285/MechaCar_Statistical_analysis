# MechaCar_statistical_analysis

## Overview

The manufacturing team incharge of the newest AutosRUs' prototype, the MechaCar, requested a revision of the production data inorder to get more insights that can help move along the production of this product. 

### Plan
1. Predict the MPG of MechaCar prototypes by performaing linear regression analysis. 
2. Collect statistics on the suspension Coils PSI
3. Run T-tests to compare the manufactoring lots vs the mean population

## Linear regression to Predict MPG
To predict the MPG of MechaCar prototypes a linear regression was performed and the code can be found in [MechaCarChallenge.R](https://github.com/lina2285/MechaCar_statistical_analysis/blob/main/R-Analysis/MechaCarChallenge.R)

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset? the Vehicle_length provided a non-random amount of variance. 
Is the slope of the linear model considered to be zero? Why or why not? The slope is note zero because the P-value of the linear regression is 5.35e-11.  Based on this, there isn't enough evidence to reject the null hypothesis. 
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not? This model has a 71.49% accuracy, which means there is almost 20% chance that the prediction will not be correct. 

![Linear regression output](https://github.com/lina2285/MechaCar_statistical_analysis/blob/main/R-Analysis/linear%20regression%20output.png)

## Summary Statistics on Suspension Coils

In this analysis we are reviewing the weight capacities of multiple suspension coils.  This will help determnine if the manufacturing process is consistent across production lots. Based on the data retrieved and analyzed, we find that the current manufacturing data does not meet the design specifications. Lot 3 from the analysis has a variance over of 170.2861224, which is over the limit. 
![Total_Summary](https://github.com/lina2285/MechaCar_statistical_analysis/blob/main/R-Analysis/Total_summary.png)

![Lot_Summary](https://github.com/lina2285/MechaCar_statistical_analysis/blob/main/R-Analysis/Lot_summary.png)

## T-tests on Suspension Coils

T-tests were ran to determine the statistical similarities or differences between manufacturing lots.  The results of the test proved that there is very little difference between Lot 1 and 2, but Lot 3 was significantly different. The P-value of Lot 3 is much lower than the assumed significance level. 
