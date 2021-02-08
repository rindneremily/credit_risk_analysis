# credit_risk_analysis
## Overview
The purpose of this analysis was to take a deeper look into a loan dataset to determine the amount of risk.
## Results
![Balanced Random Forest Classifier](https://github.com/rindneremily/credit_risk_analysis/blob/main/images/Balanced%20Random%20Forest%20Classifier.png)
Balanced Random Forest Classifier:
- Balanced Accuracy score: 0.7885
- Precision: 0.0319
- Sensitivity: 0.703
- F1: 0.061
![Combination Sampling](https://github.com/rindneremily/credit_risk_analysis/blob/main/images/Combination%20Sampling.png)
Combination Sampling:
- Balanced Accuracy Score: 0.645
- Precision: 0.0098
- Sensitivity: 0.7228
- F1: 0.0194
![Easy Ensemble Classifier](https://github.com/rindneremily/credit_risk_analysis/blob/main/images/Easy%20Ensemble%20Classifier.png)
Easy Ensemble Classifier:
- Balanced Accuracy Score: 0.9317 
- Precision: 0.0864
- Sensitivity: 0.9208
- F1: 0.1581
![Naive Random Oversampling](https://github.com/rindneremily/credit_risk_analysis/blob/main/images/Naive%20Random%20Oversampling.png)
Naive Random Oversampling:
- Balanced Accuracy Score: 0.6403
- Precision: 0.0101
- Sensitivity: 0.6634
- F1: 0.1981
![SMOTE Oversampling](https://github.com/rindneremily/credit_risk_analysis/blob/main/images/SMOTE%20Oversampling.png)
SMOTE Oversampling:
- Balanced Accuracy Score: 0.6515
- Precision: 0.0115
- Sensitivty: 0.6139
- F1: 0.0227
![Undersampling](https://github.com/rindneremily/credit_risk_analysis/blob/main/images/Undersampling.png)
Undersampling:
- Balanced Accuracy Score: 0.5442
- Precision: 0.0068
- Sensitivty: 0.6733
- F1: 0.0135

## Summary
The results show a comparison of the models utilizing the same dataset. Their different evaluations can come together through the F1 and balanced accuracy score. By looking at these numbers, you can see which model is the most ideal for analysis. The naive random oversampling model had the highest F1 score at 0.1981. This score is still very far from perfect. Ideally, this number would be closer to one. The easy ensemble classifier has the highest balanced accuracy score at 0.9317. This is probably the most ideal score we can get from these models. I would recommend using either of these models. However, neither are perfect. 
