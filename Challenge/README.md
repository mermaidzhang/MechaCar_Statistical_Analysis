# MechaCar_Statistical_Analysis
## Project Overview
The purpose of this project is to perform statistical tests to provide insights on the company performance using R and suggest more ways of comparision for MechanCar for it to compete against others. 

## Results & Analysis
## Linear Regression to Predict MPG
p-value needed to be consindered to determine a non-random amount of variance to the mpg values in the dataset. If the p-vaklue is below 0.05, thihc means that those variables have a significant impact on mpg. Results indicated that the p-value for all ground clearnace, vehicle length and intgercept are less than 0.05, which means the intercepts are statistically significant. There are other factors needed to be considered to contribute to the variation in mpg.The P-value is much smaller than the assumed signifanct level of at 95% which means we can  reject our null hypothesis and the slope of our model is not 0. The R calue is 0.72 and indicates that 72% of all mpg of MechaCars prototypes will be correct when using this model. Hence, it is a fairly accurate model. 
![](images/1.PNG)
## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The current manufacturing data indicates the lot3 has a variance of 220, which does not meet the standard. But in total the variance does meet the standard.  

Total:
![](images/2.PNG)

By lots:
![](images/3.PNG)

## T-Tests on Suspension Coils
H0:There is no significantly difference between the suspension coil data set mean and the population mean of 1,500 pounds per square inch.
Based on our results, p-value for all lots is 0.5117, whihc is bigger than assumed 0.05. Lot 1 is at 0.9, lot 2 is at 0.3451 and lot three is at 0.637. All cases are higher than 0.05. Hence, we accept the null hypothesis that there is not significantly differences between the suspension coil data set mean and its population mean. 
Total: 
![](images/4.PNG)

Lot 1:
![](images/5.PNG)
Lot 2:
![](images/6.PNG)
Lot 3:
![](images/7.PNG)
## Study Design: MechaCar vs Competition
The new study design is  the highway fuel efficiency between two companies 
H0:Our null hypothesis is that there is no significantly differences tween MechaCar and its competition 
Ha:There is a statistically differences between MechaCar and its competition 
we will use two sample T test to compare those two metrics. The difference in veicel performance of the MechaCar against the compeition will tell us if MechaCar is more fuel efficient on highway. 
the sampling plan is random sampling and interlock based on regional demographics. 