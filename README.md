# Credit Risk Analysis

## Overview

Understanding credit risk is vital for lenders. As lending demand continue to grow, so will lender expectations in risk prediction. This technical analysis is focused on evaluating several machine learning models to predict credit risk. 

## Results

The balanced accuracy, precision, and recall scores for all six algorithms:

### Balanced Accuracy
 1. **Easy Ensemble AdaBoost Classifier 93%**
 2. Balanced Random Forest Classifier 79%
 3. Naive Random Algorithm 65%
 4. SMOTE Algorithm 62%
 5. SMOTEENN Algorithm 62%
 6. ClusterCentroids Algorithm 51%

### Precision
 1. **Easy Ensemble AdaBoost Classifier - High Risk 0.07, Low Risk 1.00, avg/total 0.99**
 2. Balanced Random Forest Classifier - High Risk 0.04, Low Risk 1.00, avg/total 0.99
 3. Naive Random Algorithm - High Risk 0.01, Low Risk 1.00, avg/total 0.99
 4. SMOTE Algorithm - High Risk 0.01, Low Risk 1.00, avg/total 0.99
 5. SMOTEENN Algorithm - High Risk 0.01, Low Risk 1.00, avg/total 0.99
 6. ClusterCentroids Algorithm - High Risk 0.01, Low Risk 1.00, avg/total 0.99

### Recall
 1.  **Easy Ensemble AdaBoost Classifier - High Risk 0.91, Low Risk 0.94, avg/total 0.94**
 2.  Balanced Random Forest Classifier - High Risk 0.67, Low Risk 0.91, avg/total 0.91
 3.  Naive Random Algorithm - High Risk 0.62, Low Risk 0.68, avg/total 0.68
 4.  SMOTE Algorithm - High Risk 0.59, Low Risk 0.66, avg/total 0.66
 5.  SMOTEENN Algorithm - High Risk 0.71, Low Risk 0.53, avg/total 0.53
 6.  ClusterCentroids Algorithm - High Risk 0.59, Low Risk 0.43, avg/total 0.44

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

## Module 17 Challenge

### Deliverable 1: Use Resampling Models to Predict Loan Risk

Naive Random Oversampling

![Naive Random Oversampling Image](https://github.com/krisnagoda/Credit_Risk_Analysis/blob/cd583f367d1bc3e633b8039fb2994a197dbdb8b0/Naive_Random_Oversampling.png)

SMOTE Oversampling

![SMOTE Oversampling Image](https://github.com/krisnagoda/Credit_Risk_Analysis/blob/cd583f367d1bc3e633b8039fb2994a197dbdb8b0/SMOTE_Oversampling.png)

Cluster Centroids Undersampling

![Cluster Centroids Undersampling Image](https://github.com/krisnagoda/Credit_Risk_Analysis/blob/cd583f367d1bc3e633b8039fb2994a197dbdb8b0/Cluster_Centroids_Undersampling.png)

 - There is an accuracy score and confusion matrix for ALL THREE algorithms

 - A classification report is generated for ALL THREE algorithms

### Deliverable 2: Use the SMOTEENN Algorithm to Predict Loan Risk

![SMOTEENN_Combo_Sampling_Image](https://github.com/krisnagoda/Credit_Risk_Analysis/blob/4069d1cc75f4ef240be56cc663c7cad94da969de/SMOTEENN_Combo_Sample.png)

 - There is an accuracy score for the SMOTEENN algorithm

 - There is a confusion matrix for the SMOTEENN algorithm

 - A classification report is generated for the SMOTEENN algorithm

### Deliverable 3: Use Ensemble Classifiers to Predict Loan Risk

Balanced Random Forest Classifier

![Balanced Random Forest Classifier Image](https://github.com/krisnagoda/Credit_Risk_Analysis/blob/4069d1cc75f4ef240be56cc663c7cad94da969de/Balanced_Random_Forest_Classifier.png)

Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost Classifier](https://github.com/krisnagoda/Credit_Risk_Analysis/blob/4069d1cc75f4ef240be56cc663c7cad94da969de/Easy_Ensemble_AdaBoost_Classifier.png)

 - There is an accuracy score and confusion matrix for TWO algorithms

 - A classification report is generated for TWO algorithms

 - The list of features is sorted in descending order by feature importance

### Deliverable 4: Analysis

 - The purpose is well defined

 - The balanced accuracy score and the precision and recall scores for ALL SIX algorithms are described

 - The results are summarized, and there is a recommendation on which model to use or justification
