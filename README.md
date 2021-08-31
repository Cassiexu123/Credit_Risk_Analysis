# Credit_Risk_Analysis
## Overview of the analysis:
The purpose of this analysis is to apply machine learning to Q1 2019 LoanStats in order to predict credit risk. Three methods were used in this analysis, which Resampling, SMOTEENN and Emsemble classifiers.

## Results
There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models:
### 1.RandomOverSampler
- Balanced Accuracy Score: 64.94%
- Precision Score -High Risk: 0.01
- Precision Score -Low Risk: 1.00
- Recall Score Difference: 0.16%

### 2.SMOTE

- Balanced Accuracy Score: 65.84%
- Precision Score -High Risk: 0.01
- Precision Score -Low Risk: 1.00
- Recall Score Difference: 0.05%

### 3.ClusterCentroids

- Balanced Accuracy Score: 54.42%
- Precision Score -High Risk: 0.01
- Precision Score -Low Risk: 1.00
- Recall Score Difference: 0.29%

### 4.SMOTEENN

- Balanced Accuracy Score: 66.22%
- Precision Score -High Risk: 0.01
- Precision Score -Low Risk: 1.00
- Recall Score Difference: 0.24%

### 5.BalancedRandomForestClassifer

- Balanced Accuracy Score: 78.85%
- Precision Score -High Risk: 0.03
- Precision Score -Low Risk: 1.00
- Recall Score Difference: 0.17%

### 6.EasyEnsembleClassifier

- Balanced Accuracy Score: 93.17%
- Precision Score -High Risk: 0.09
- Precision Score -Low Risk: 1.00
- Recall Score Difference: 0.02%

## Summary
Based on the six different machine learning models above, we can treat EasyEnsembleClassifier as the recommended model. Because the balanced accuracy score is 93.17% which is the highest one and small variance of the recall score-0.02%.






















