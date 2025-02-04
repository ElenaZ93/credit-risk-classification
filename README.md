# Credit Risk Classification //  Scalable Loan Risk Prediction

## Background
In this challenge, the goal is to use machine learning techniques to train and evaluate a model based on loan risk. We will utilize a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

### Files
This project includes the following files:
- `credit_risk_classification.ipynb`: Jupyter notebook containing the steps to train and evaluate the model.
- `lending_data.csv`: The dataset was used to train and test the model.

- You can find the instructions for this challenge in the resources folder.

## Overview of the Analysis

The purpose of this analysis was to build and evaluate a machine-learning model to predict credit risk using financial data. The dataset contained features such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The goal was to predict whether a loan would be healthy (label 0) or high-risk (label 1).

To understand the distribution of the labels, the data was analyzed with a value count on the target variable (loan_status). We went through several stages of the machine learning process, including:

* Data preprocessing (splitting the data into features X and labels y).

Splitting the dataset into training and testing sets.

Standardizing the features.

Training a logistic regression model (LogisticRegression) to predict the credit risk of loans.

* Results
  
Machine Learning Model 1: Logistic Regression

Accuracy: 99%

Precision for label 0 (healthy loan): 1.00 (meaning almost all predicted healthy loans were correct)

Precision for label 1 (high-risk loan): 0.84 (meaning some loans predicted as high-risk were healthy)

Recall for label 0: 0.99 (almost all healthy loans were correctly identified)

Recall for label 1: 0.94 (a high proportion of high-risk loans were correctly identified)

* Summary:
  
The logistic regression model performed exceptionally well, achieving an overall accuracy of 99%. It showed very high precision and recall for healthy loans (label 0), and relatively strong performance for predicting high-risk loans (label 1). However, the precision for high-risk loans (0.84) indicates that some healthy loans were incorrectly classified as high-risk.

Given the results, the logistic regression model is recommended for this problem, as it provides reliable predictions for healthy loans and reasonably good predictions for high-risk loans. This model is suitable if the main priority is minimizing the incorrect classification of high-risk loans while maintaining high overall accuracy.


## References

 edX Boot Camps LLC
