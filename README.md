# Credit_Risk_Analysis

## Overview

In this analysis we are attempting to solve a real world problem for credit risk. Using machine learning and statistical reasoning we are trying to use supervised machine learning to automate the prediction process of credit risk. The libraries used include, imbalanced-learn, scikit-learn, RandomOverSampler, SMOTE, ClusteredCentroids, SMOTEENN, BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results

### Naive Random Oversampling
- balanced accuracy scores
  - The Naive Random Oversampling method was not accurate enough to automate this task with machine learning. 
  
![PyBer_Summary_df](/Images/Native_Random_Ovesampling_balanced_accuracy_score.PNG)

- precision and recall scores 
  - The precision accuracy score for this model is very accurate for low-risk scores, but very low for high-risk loans. 
  - The recall scores show this model is better at predicting low risk scores but isn't super accurate in either area.
 
![PyBer_Summary_df](/Images/Native_Random_Ovesampling_precision_and_recall_scores.PNG)



### SMOTE Oversampling
- balanced accuracy scores
  - The SMOTE Oversampling method was not accurate enough to automate this task with machine learning. 
 
![PyBer_Summary_df](/Images/SMOTE_Oversampling_balanced_accuracy_score.PNG)

- precision and recall scores 
  - The precision accuracy score for this model is very accurate for low-risk scores, but very low for high-risk loans. 
  - The recall scores show this model is better at predicting low risk scores but isn't super accurate in either area.
 
![PyBer_Summary_df](/Images/SMOTE_Ovesampling_precision_and_recall_scores.PNG)



### ClusterCentroids
- balanced accuracy scores
  - The ClusterCentroids method was not accurate enough to automate this task with machine learning. 

![PyBer_Summary_df](/Images/ClusterCentroids_Undersampling_balanced_accuracy_score.PNG)

- precision and recall scores 
  - The precision accuracy score for this model is very accurate for low-risk scores, but very low for high-risk loans. 
  - The recall score is better at predicting high risk loans but isn't very accurate for high or low risk loans.
   
![PyBer_Summary_df](/Images/ClusterCentroids_Undersampling_precision_and_recall_scores.PNG)



### SMOTEENN
- balanced accuracy scores
  - The SMOTEENN method was not accurate enough to automate this task with machine learning. 
  
![PyBer_Summary_df](/Images/SMOTEENN_Combination(Over_and_Under)_Sampling_balanced_accuracy_score.PNG)

- precision and recall scores 
  - The precision accuracy score for this model is very accurate for low-risk scores, but very low for high-risk loans. 
  - The recall score shows this model is better at predicting high risk than low risk. The high-risk score is better than previously shown at 0.7.
 
![PyBer_Summary_df](/Images/SMOTEENN_Combination(Over_and_Under)_Sampling_precision_and_recall_scores.PNG)



### BalancedRandomForestClassifier
- balanced accuracy scores
  - While the BalancedRandomForestClassifier method had the highest accuracy percent, it was not accurate enough to automate this task with machine learning. 
  
![PyBer_Summary_df](/Images/Balanced_Random_Forecast_Classifier_balanced_accuracy_score.PNG)

- precision and recall scores 
  - The precision accuracy score for this model is very accurate for low risk scores, but very low for high risk loans. 
  - The recall score shows this model is better at predicting low risk over high risk.
 
![PyBer_Summary_df](/Images/Balanced_Random_Forecast_Classifier_precision_and_recall_scores.PNG)
 
 
 
### EasyEnsembleClassifier
- balanced accuracy scores
  - The EasyEnsembleClassifier method was not accurate enough to automate this task with machine learning. 
  
![PyBer_Summary_df](/Images/EasyEnsembleClassifier_balanced_accuracy_score.PNG)

- precision and recall scores 
  - The precision accuracy score for this model is very accurate for low-risk scores, but very low for high risk loans. 
  - The recall score shows this model is better at predicting low risk over high risk.
 
![PyBer_Summary_df](/Images/EasyEnsembleClassifier_Classifier_precision_and_recall_scores.PNG)



## Summary

In summary, the BalancedRandomForestClassifier was the most accurate model at predicting precision and recall scores. Although none of these models are able to predict the outcome at a high enough percentage to choose machine learning in this instance for credit risk.
