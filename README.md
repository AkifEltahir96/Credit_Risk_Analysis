# Credit Risk Analysis

## Purpose
The purpose of this analysis is to apply machine learning to predict credit card risk through LendingClub, a credit lending services organization. Using a credit card dataset provided by LendingClub, we will predict lending risk through machine learning models that oversample data, undersample data, and a combinatorial approach (under and oversampling). In addition, we will also use models that reduce bias when predicting risk. Once the analyses are complete, we will make a final recommendation on whether these models should be used to predict credit risk.

## Results
1. [Oversampling](https://github.com/AkifEltahir96/Credit_Risk_Analysis/blob/main/Pictures/Oversampling.png)
Balanced Accuracy Score: 0.66
Precision Score: 0.01
Recall Score: 0.71

2. [SMOTE Oversampling](https://github.com/AkifEltahir96/Credit_Risk_Analysis/blob/main/Pictures/SMOTE-Oversampling.png)
Balanced Accuracy Score: 0.66
Precision Score: 0.01
Recall Score: 0.63

3. [Undersampling](https://github.com/AkifEltahir96/Credit_Risk_Analysis/blob/main/Pictures/Undersampling.png)
Balanced Accuracy Score: 0.54
Precision Score: 0.01
Recall Score: 0.69

4. [Combination](https://github.com/AkifEltahir96/Credit_Risk_Analysis/blob/main/Pictures/Combination.png)
Balanced Accuracy Score: 0.64
Precision Score: 0.01
Recall Score: 0.72

5. [Balanced Random Forest Classifier](https://github.com/AkifEltahir96/Credit_Risk_Analysis/blob/main/Pictures/Balanced-Random-Forest.png)
Balanced Accuracy Score: 0.79
Precision Score: 0.03
Recall Score: 0.70

6. [Easy Ensemble Classifier](https://github.com/AkifEltahir96/Credit_Risk_Analysis/blob/main/Pictures/Easy-Ensemble.png)
Balanced Accuracy Score: 0.93
Precision Score: 0.09
Recall Score: 0.92

## Summary

In summary, while these models have moderate to high balanced accuracy and recall scores (0.5 - 0.95), the precision scores are extremly low (<0.05). Since we are dealing with credit risk, accurately identifying a bad lending option is extremely important. With this is mind, I would not recommend any of these models.
