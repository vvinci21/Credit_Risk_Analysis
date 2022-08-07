# Credit_Risk_Analysis

Evaluate several machine learning models to assess credit card risk.
## Overview:
Use six machine learning models to evaluate which has the highest accuracy and precision in evaluating credit card risk.
## Results:
### Native Random Oversampling Model - Accuracy Score= 0.68
* ![Native2](https://github.com/vvinci21/Credit_Risk_Analysis/blob/ccb5ddc5a9d45d839005866a51a6afdeb20ffd22/Images/nativerandomoverreport%202.png)
* ![Native](https://github.com/vvinci21/Credit_Risk_Analysis/blob/ccb5ddc5a9d45d839005866a51a6afdeb20ffd22/Images/nativerandomover%202.png)

### SMOTE Model - Accuracy Score= 0.64
* ![Smote](https://github.com/vvinci21/Credit_Risk_Analysis/blob/ccb5ddc5a9d45d839005866a51a6afdeb20ffd22/Images/smotemodel%202.png)
* ![Smote2](https://github.com/vvinci21/Credit_Risk_Analysis/blob/8602d650bbe9f928d259f912a83cc5ffd97140e8/Images/smotereport.png)

### Undersampling Model - Accuracy Score= 0.53
* ![under](https://github.com/vvinci21/Credit_Risk_Analysis/blob/8602d650bbe9f928d259f912a83cc5ffd97140e8/Images/undersample%202.png)
* ![under2](https://github.com/vvinci21/Credit_Risk_Analysis/blob/6b965ecf0e8273ebb9f4b3c073336021e7383fca/Images/undersamplereport.png)

### SMOTEENN Model - Accuracy Score= 0.64
* ![smoteen](https://github.com/vvinci21/Credit_Risk_Analysis/blob/6b965ecf0e8273ebb9f4b3c073336021e7383fca/Images/smoteenmodule%202.png)
* ![smoteen2](https://github.com/vvinci21/Credit_Risk_Analysis/blob/cecd42028a981080b44c7f3f82a98288272c258f/Images/smoteenreport.png)

### Balanced Random Rainforest Model - Accuracy Score= 0.79
* ![balance](https://github.com/vvinci21/Credit_Risk_Analysis/blob/cecd42028a981080b44c7f3f82a98288272c258f/Images/balancedmodule%202.png)
* ![balance2](https://github.com/vvinci21/Credit_Risk_Analysis/blob/7663304757bc83ab0458b7c88f8c8aeb0a404555/Images/forestreport.png)

### Easy Ensemble Model - Accuracy Score= 0.93
* ![easy](https://github.com/vvinci21/Credit_Risk_Analysis/blob/33e06e70f3b4bf6cec0a73785dac7eb63f93d1ce/Images/easymodule%202.png)
* ![easy2](https://github.com/vvinci21/Credit_Risk_Analysis/blob/7663304757bc83ab0458b7c88f8c8aeb0a404555/Images/easyreportNEW.png)

## Summary:
The summary of model results is presented in order of highest accuracy score to lowest accuracy score.
* The Easy Ensemble model has the highest accuracy score of 0.93 and the F-1 score for low risk of 0.97 is also the highest. 
  *  The recommended model for credit card analysis would be the Easy Ensemble model.
* The Balanced Random Rainforest model has the second highest accuracy score at 0.79 and the F-1 score is 0.93. 
* The Naïve Random Oversampling model has an accuracy of 0.68 and a F-1 score of 0.81 for low risk. 
* The SMOTE model has an accuracy score of 0.64 and the F-1 score is 0.79 for low risk.
* The SMOTEENN model has an accuracy score of 0.64 and the F-1 score is 72 for low risk.
* UnderSampling has the lowest accuracy score at 0.53 and F-1 score of 0.62. 
  * Because of how low both scores are the Undersampling model is not recommended for credit card risk analysis.
