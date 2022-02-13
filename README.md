# MechaCar_Statistical_Analysis

The MechaCar_mpg.csv dataset contains mpg test results of MechaCars. The samples were produced using multiple design specifications to identify ideal vehicle performance.  The purpose of this research is to compare the vehicle performance between different variables. 


**Deliverable 1: Linear Regression to Predict MPG**

The vehicle length(P-value 2.60e-12) and vehicle ground clearance(P-value 5.24e-08) have a significant impact on miles per gallon on the prototype. On the other hand, the vehicle weight(P-value 0.077), spoiler angle(P-value 0.3), and All Wheel Drive (AWD) (P-value 0.185)have higher p-Values that can't see statistically support to prove for the impact.
![new](https://github.com/Sirius0531/MechaCar_Statistical_Analysis/blob/main/Resources/D1%20result-1.PNG)
Resulting Model:
mpg = (6.267)vehicle_length + (0.0012)vehicle_weight + (0.0688)spoiler_angle + (3.546)ground_clearance + (-3.411)AWD + (-104.0)
![new](https://github.com/Sirius0531/MechaCar_Statistical_Analysis/blob/main/Resources/D1%20result-2.PNG)


**Deliverable 2: Create Visualizations for the Trip Analysis**


Summary for all manufacturing lots:
![new](https://github.com/Sirius0531/MechaCar_Statistical_Analysis/blob/main/Resources/D2%20Lot%20summary.PNG)
Groupby lots:
![new](https://github.com/Sirius0531/MechaCar_Statistical_Analysis/blob/main/Resources/D2%20total%20summary.PNG)

boxplot illustrates the differences between the lots
![new](https://github.com/Sirius0531/MechaCar_Statistical_Analysis/blob/main/Resources/D2%203lot%20compare.PNG)


**Deliverable 3: T-Tests on Suspension Coils**

The results of the T-test for the suspension coils across all manufacturing lots show the p-value is 0.0603. No statistical difference (p-value>0.05) from the population means the null hypothesis cannot be rejected.
![new](https://github.com/Sirius0531/MechaCar_Statistical_Analysis/blob/main/Resources/D3%201%20sample%20t%20test.PNG)

However, we can breakdown into different lots for further analysis: 

The results of the T-test for the suspension coils for Lot 1 show the p-value is 1. No statistical difference (p-value>0.05) from the population means the null hypothesis cannot be rejected.
![new](https://github.com/Sirius0531/MechaCar_Statistical_Analysis/blob/main/Resources/D3%20lot1.PNG)

The results of the T-test for the suspension coils for Lot 2 show the p-value is 1. No statistical difference  (p-value>0.05)from the population means the null hypothesis cannot be rejected.
![new](https://github.com/Sirius0531/MechaCar_Statistical_Analysis/blob/main/Resources/D3%20lot2.PNG)

The results of the T-test for the suspension coils for Lot 3 show the p-value is 0.04168. There is a statistical difference (p-value<0.05) from the population, which means the null hypothesis is rejected. This lot needs to be reviewed.
![new](https://github.com/Sirius0531/MechaCar_Statistical_Analysis/blob/main/Resources/D3%20lot3.PNG)


## Study Design: MechaCar vs Competition:

What metric or metrics are you going to test?
Engine type: Electric, Hybrid, Gasoline  vs overall sales
What is the null hypothesis or alternative hypothesis?
Null Hypothesis (Ho): The sales of the MechaCar is based on its engine type.
Alternative Hypothesis (Ha): The sales of the MechaCar is not based on its engine type.
What statistical test would you use to test the hypothesis? And why?
A multiple linear regression (multiple factors) would be used to determine the factors that have the highest correlation with the sales. 
What data is needed to run the statistical test?
Selling price, annual/monthly sales and ebgine type of each model. 
