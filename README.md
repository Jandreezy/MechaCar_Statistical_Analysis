# MechaCar Statistical Analysis

## Linear Regression to Predict MPG
![1](https://github.com/Jandreezy/MechaCar_Statistical_Analysis/blob/main/Images/linear_regression_summary.PNG?raw=true)

## Summary Statistics on Suspension Coils
The data suggests that the current manufacturing data meets the required variance of 100 pounds per square inch apart from lot 3. Since the variance of lot 3 is much higher and above 100, this lot has exceeded the 100 pound target and should be brought to attention.

![2](https://github.com/Jandreezy/MechaCar_Statistical_Analysis/blob/main/Images/total_summary_table.PNG?raw=true)
![3](https://github.com/Jandreezy/MechaCar_Statistical_Analysis/blob/main/Images/lot_summary_table.PNG?raw=true)

## T-Tests on Suspension Coils
The t-tests show that the lots are out of tolerance. The allowable p-value is 0.05 and the summary of the lots shows 0.06028. Lot 1 and 2 are within tolerance but lot 3 seems to be drastically different with the p-value of 0.04168.

![4](https://github.com/Jandreezy/MechaCar_Statistical_Analysis/blob/main/Images/t-test.PNG?raw=true)
![5](https://github.com/Jandreezy/MechaCar_Statistical_Analysis/blob/main/Images/lots_t_test.PNG?raw=true) 

## Study Design: MechaCar vs Competition
Another statistical study that can be performed to determine MechaCar's standing against its competition is a linear regression on city and highway fuel efficiency. Gasoline is expensive nowadays, and it is an important feature that many consumers look at when purchasing a new car. The metrics that can be included in this analysis are:

- City and highway fuel efficiency: dependent variable
- Horse power: independent variable
- Vehicle weight: independent variable
- AWD capabilities: independent variable
- MPG: independent variable
