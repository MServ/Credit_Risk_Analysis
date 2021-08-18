# Credit_Risk_Analysis

## Overview of the Analysis
In this analysis we used six machine learning models to calculate credit risk. The models were:
naive random oversampling, SMOTE oversampling, Cluster Centroids undersampling, SMOTEENN combination sampling, balanced random forest classifier, and Easy Ensemble classifier.

## Results
Notes: all models used a random state of 1.
       the extremely low precision and f1 score values for high-risk loans.

Model 1: naive random sampling
Balanced accurancy score = 64%
Precision = 99%
Recall = 65%
f1 score = 78%

[images/naive_random_over1.png]

Classification report
[images/naive_random_over2.png]

Model 2: SMOTE oversampling
Balanced accurancy score = 66%
Precision = 99%
Recall = 69%
f1 score = 81%
[images/smote_over1.png]
Classification report
[images/smote_over2.png]

Model 3: Cluster Centroids undersampling
Balanced accurancy score = 54%
Precision = 99%
Recall = 40%
f1 score = 56%
[images/cluster_centroid1.png]
Classification report
[images/cluster_centroid2.png]

Model 4: SMOTEENN combination sampling
Balanced accurancy score = 64%
Precision = 99%
Recall = 57%
f1 score = 72%
[images/smoteenn_under1.png]
Classification report
[images/smoteenn_under2.png]

Model 5: balanced random forest classifier
Balanced accurancy score = 79%
Precision = 99%
Recall = 87%
f1 score = 93%
[images/brforest1.png]
Classification report
[images/brforest2.png]

Model 6: Easy Ensemble classifier
Balanced accurancy score = 93%
Precision = 99%
Recall = 94%
f1 score = 97%
[images/easy_ensemble1.png]
Classification report
[images/easy_ensemble2.png]

## Summary
In conclusion, the model that performed with the greatest accuracy, precision, recall, and f1 score was the Easy Ensemble classifier. This would be the model best suited to use.
