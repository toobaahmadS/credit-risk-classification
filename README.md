# credit-risk-classification
The Machine learning techniques are used to predict loan risk.The dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.


## Instructions

The instructions for this Challenge are divided into the following subsections:
1. Split the Data into Training and Testing Sets
2. Create a Logistic Regression Model with the Original Data
3. Write a Credit Risk Analysis Report


## Overview of the Analysis

The dataset was split into training and testing sets.By using orignal data we created a trained set to build an initial logistic regression model (Logistic Regression Model 1) using the LogisticRegression module from scikit-learn. Logistic Regression Model 1 was then applied to the testing dataset. The purpose of the model was to determine whether a loan to the borrower in the testing set would be low- or high-risk and results are summarized below.

The resampled data was used to build a new logistic regression model (Logistic Regression Model 2). The purpose of Logistic Regression Model 2 was to determine whether a loan to the borrower in the testing set would be low- or high-risk. The results are summarized below.


## Prediction 


Logistic Regression Model 1:

Precision: 93% (an average--in predicting low-risk loans, the model was 100% precise, though the model was only 87% precise in predicting high-risk loans)
Accuracy: 94%
Recall: 95% (an average--the model had 100% recall in predicting low-risk loans, but 89% recall in predicting high-risk loans)

Logistic Regression Model 2:

Precision: 93% (an average--in predicting low-risk loans, the model was 100% precise, though the model was only 87% precise in predicting high-risk loans)
Accuracy: 100%
Recall: 100%


## Summary

Logistic Regression Model 2 is less likely to predict false negative results. However, based on the confusion matrices for each model, Logistic Regression Model 2 predicted slightly more false positives (low-risk when the actual was high-risk).

If the goal of the model is to determine the likelihood of high-risk loans, neither model scores above 90% precision. Logistic Regression Model 2 had fewer false predictions of the testing data overall and would be the best model to use based on the high accuracy and recall of this model.