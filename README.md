# Module 20 Credit Risk Analysis

## Overview of the Analysis

The purpose of the analysis is to build a model that can identify the creditworthyness of borrowers.  The analysis is based on a variety of financial information from the borrowers that includes loan size, interest rate, borrower income, borrower debt, debt to income ratio, number of accounts, derogatory marks, and the loan status. The data includes 75,036 healthy loans and 2,500 high risk loans.

First, I separated the data using "loan_status" as the labels (`y`), and the rest of the variables for the features (`X`). Then I split the data into training and testing datasets by using `train_test_split`.  From there, I used the `LogisticRegression` model method from the `sklearn.linear_model` library for the analysis.  I evaluated the model's performance by calculating the accuracy score, generating a confusion matrix, and then printing the classification report.

## Results

* Machine Learning Model:
  * The `balanced_accuracy_score` is 95.2%.
  * Healthy Loans: Precision score = 100% and Recall score = 99%.
  * High Risk Loans: Precision score = 85% and Recall score = 91%.

## Summary

To summarize, this model would be a great model to use because it has a very high accuracy score, and high precision and recall scores for both healthy and high risk loans.
