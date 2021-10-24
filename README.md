# MechaCar_Statistical_Analysis
## Overview 
  In this project I aim to perform statistical analysis of MechaCar data (a hypothetical car from a hypothetical car manufacturer: AutosRUs') utilizing R and generating summaries of the different data points uncovered. 
  
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
  
  ### T-Tests on Suspension Coils
  * The image below shows the results of a t-test to determine if the PSI across all manufacturing lots is statistically different from the population mean of 1,500 pounds per square inch.
  * The p-value of 0.06 determines that there is not sufficient evidence for us to reject the null hypothesis as it lies just above our assumed significance level of 0.05%. In this conclusion, we would state that the two means are statistically similar.
<img width="406" alt="ttest" src="https://user-images.githubusercontent.com/60943801/138584074-0685afe6-a4ee-4fea-bc4b-ce946fbe8c7f.png">
 
 The image below dives into each lot individually (Lot 1, Lot 2, and Lot 3). Here we try to determine if the PSI for each manufacturing lot is statistically different from the population mean of 1,500 pounds per square inch. 
 <img width="566" alt="ttest3" src="https://user-images.githubusercontent.com/60943801/138584255-5d75425e-06ac-436e-94ed-f9d9e86a921f.png">
 * The p-values in both lot 1 and lot 2 lie above our assumed significance level of 0.05% indicating that there is not sufficient evidence to reject the null hypothesis (H0 : There is no statistical difference between the observed sample mean and its presumed population mean.).
 * Lot 3: Lot 3 p-value lies at 0.042, just below our assumed significance level of 0.05%. This indicates that we can reject the null hypothesis as there is a statistical difference (however slight, still below our p-value) between the population mean and lot 3 mean. 


## Study Design: MechaCar vs Competition
