# MechaCarChallenge

## Overview
AutosRus is in the process of manufacturing a new protoype called The "MechaCar", Unfortunatley production woes are blocking the manufacturing team’s progress. AutosRUs’ upper management has called upon the data analytics team to review the production data for insights that may help the manufacturing team.

The team sets off to analyze sets of data in oder to perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes. Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots, run t-tests to determine if the manufacturing lots are statistically different from the mean population. Also design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Deliverable 1

For our first set of analysis we utilize linear regression to predict MPG
The results are shown here 
 ![results](Deliverable1.png)

1: The Vehicle Length and Ground Clearance provide the non-random variances to the models, these variances provide more of an impact to the miles per gallon of each model


2: The p-Value for this model 5.35e-11 wich is smaller than the significance level of .05% so we can reject our null hypothesis, making the slope of the model not zero


3: This model perdicts the mpg of the MechaCar pretty effectivly with an overall 71% accuracy
 
 ## Deliverable 2
Summary of the suspension coils

![result](Deliverable2TotalSummary.png)

This data set look at the various suspension coils per manufacturer lot

lets look at each lot individually

![results](Deliverable2LotSummary.png)

The total variance of the coil springs per lot is well with in the 100psi threshold making them viable for use. If we divide the data between each of the three lots we can see that lot 1 and lot 2 are within the 100psi threshold. unforunatley lot 3 has a variance of 170psi almost double the threshold making them not as desirable. The production team could use the springs from lot 3 with springs from lots 1 and 2 distirbuting the psi load across the suspension.

![results](Deliverable2BoxPlot.png)
