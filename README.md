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
 1. **Easy Ensemble AdaBoost Classifier - High Risk 7%, Low Risk 100%**
 2. Balanced Random Forest Classifier - High Risk 4%, Low Risk 100%
 3. Naive Random Algorithm - High Risk 1%, Low Risk 100%
 4. SMOTE Algorithm - High Risk 1%, Low Risk 100%
 5. SMOTEENN Algorithm - High Risk 1%, Low Risk 100%
 6. ClusterCentroids Algorithm - High Risk 1%, Low Risk 100%

### Recall
 1.  **Easy Ensemble AdaBoost Classifier - High Risk 91%, Low Risk 94%**
 2.  Balanced Random Forest Classifier - High Risk 67%, Low Risk 91%
 3.  Naive Random Algorithm - High Risk 62%, Low Risk 68%
 4.  SMOTE Algorithm - High Risk 59%, Low Risk 66%
 5.  SMOTEENN Algorithm - High Risk 71%, Low Risk 53%
 6.  ClusterCentroids Algorithm - High Risk 59%, Low Risk 43%

## Summary

The Easy Ensemble AdaBoost Classifier out preformed each of the other 5 algorithms in accuracy, precision, and recall scores. If we need to ship something today, I’d use Easy Ensemble AdaBoost Classifier. Otherwise, I’d continue building and evaluating with an eye on improvement to High Risk Precision.

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
