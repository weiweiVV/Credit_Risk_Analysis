# Credit_Risk_Analysis
## Overview of the analysis: 
Use the imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling to predict risk
## Results:
- Random Oversampling:
<img width="475" alt="1" src="https://user-images.githubusercontent.com/19679507/123583275-2e7ce200-d794-11eb-8425-00ed952d94ee.png">
The precision ("pre" column) is very low for high risk class which it's critical to predict risk. The recall ("rec" column) are in line with each other for both high risk and low risk group.

- SMOTE Oversampling
- <img width="461" alt="2" src="https://user-images.githubusercontent.com/19679507/123584227-d515b280-d795-11eb-860d-3d53875a3dd6.png">
There are not much improvement from SMOTE Oversampling comparing with Random Oversampling.

-Undersampling:

<img width="464" alt="3" src="https://user-images.githubusercontent.com/19679507/123584442-389fe000-d796-11eb-8170-6020f8307e3a.png">
