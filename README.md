# Credit_Risk_Analysis
## Overview of the analysis: 
Use the imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling to predict risk
## Results:
- Random Oversampling:
<img width="475" alt="1" src="https://user-images.githubusercontent.com/19679507/123583275-2e7ce200-d794-11eb-8425-00ed952d94ee.png">
The precision ("pre" column) is very low for high risk class which it's critical to predict risk. The recall ("rec" column) are in line with each other for both high risk and low risk group.

- SMOTE Oversampling:
<img width="461" alt="2" src="https://user-images.githubusercontent.com/19679507/123584227-d515b280-d795-11eb-860d-3d53875a3dd6.png">
There are not much improvement from SMOTE Oversampling comparing with Random Oversampling.

- Undersampling:
<img width="464" alt="3" src="https://user-images.githubusercontent.com/19679507/123584442-389fe000-d796-11eb-8170-6020f8307e3a.png">
There is no changes on precision but the recall is getting worse comparing to the above two oversampling model.

- Combination (Over and Under) Sampling:
<img width="473" alt="4" src="https://user-images.githubusercontent.com/19679507/123584780-d09dc980-d796-11eb-8424-01b0263a211d.png">
These recall is worse than those from random under/oversampling. The precise remain the same.

## Summary:
None of the models have a high precision for the high risk prediction. Therefore, I will recommend to search for other models for risk prediction.
