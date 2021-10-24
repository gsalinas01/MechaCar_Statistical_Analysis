# MechaCar_Statistical_Analysis
## Overview 
  
## Results
  ### Linear Regression to Predict MPG
  * Utilizing linear regression on the six variables in the MetaCar dataset: This test reveals two variables, Vehicle Length and Ground Clearance, that show a non-random amount of variance to the mpg values in the dataset as evidenced by their low p-values (<0.05) (seen below in red boxes)
  * Because the p-value is less than our assumed significance level of 0.05% (5.35 e-11 as indicated by the green box below), the slope of the linear model cannot be considered to be zero. Therefore, we can state that there is sufficient evidence to reject our null hypothesis.
  * The r-squared value of 0.71 (indicated by the blue box below) means that roughly 71% of the variability of mpg predictions is explained using this linear model. This is a relatively effective model to predict mpg, however it could be improved utilizing different methods.
<img width="525" alt="Screen Shot 2021-10-24 at 12 46 11 AM" src="https://user-images.githubusercontent.com/60943801/138583101-1619b0e5-a335-4ec1-afe9-c4bda19fd994.png">

  ### Summary Statistics on Suspension Coils
  * The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. 
  * Total Summary data suggests that the overall variance in psi meets the required 100 pounds per square inch rule. As shown below, the mean and Median statistics show that the overall data meets specifications. 
  <img width="333" alt="total_summary" src="https://user-images.githubusercontent.com/60943801/138583734-1c7887bc-37ac-4e40-9767-a27761bf79a9.png">
  * However, upon further inspection in the Lot Summary data, although still at or below specification requirements overall per lot, the variance in Lot 3 stands out. Lot 3 reveals a variance of 170.29 and a SD of 13, which raises questions on the safety of those cars in the lot which vary from the mean.
  <img width="496" alt="lot_summary" src="https://user-images.githubusercontent.com/60943801/138583748-778b0bdf-9868-46f0-a365-6dc844423f05.png">
