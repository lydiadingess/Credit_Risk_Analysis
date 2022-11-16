# Credit_Risk_Analysis

Credit risk analysis using scikit-learn and imbalanced-learn on sample credit data.

## Overview 

The purpose of this analysis was to build and evaluate various machine learning models to evaluate individual customer credit risk. 

## Results:

The results for the six machine learning models including their respective balanced accuracy, precision, and recall scores are as follows:

### Naive Random Oversampling

1. Balanced Accuracy: 0.6366972052004142
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .62/.65

###  SMOTE Oversampling

1. Balanced Accuracy: 0.6302712208564487
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .62/.64

### Undersampling

1. Balanced Accuracy: 0.6302712208564487
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .61/.45

### Combination Under-Over Sampling

1. Balanced Accuracy: 0.5292734810302525
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .70/.53

### Balanced Random Forest Classifier

1. Balanced Accuracy: 0.7885466545953005
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .70/.87

### Easy Ensemble AdaBoost Classifier

1. Balanced Accuracy: 0.9316600714093861
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .91/.94

## Summary:

After creating 6 different models and testing the performance of each, all the models used to perform the credit risk analysis show weak precision in determining if a credit risk is high. For example, the EasyEnsembleClassifier Model is a strongner model in comparison to the others, specially on the sensitivity of the high risk credits. This is demonstrated with its 92% high_risk precision so it detects almost all high risk credit. However, with a low precision, a lot of low risk credits are still falsely detected as high risk. This can alter and jeopordize the bank's credit strategy.

As a result, I would not recommend the bank to use any of these models to predict credit risk.
