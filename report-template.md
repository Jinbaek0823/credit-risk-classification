# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to use machine learning to predict the likelihood of a loan being high-risk. The dataset consisted of financial information related to loans, and the objective was to predict the loan_status column, where 0 indicates a healthy loan and 1 represents a high-risk loan.

We followed the standard machine learning process:

First, we split the data into training and testing sets.
Then, we trained a logistic regression model to predict loan risk.
Finally, we evaluated the model's performance using a confusion matrix and classification report.

## Results

Logistic Regression Model:
Accuracy: 85%
Precision (Healthy Loan): 87%
Precision (High-Risk Loan): 75%
Recall (Healthy Loan): 92%
Recall (High-Risk Loan): 65%

## Summary

The logistic regression model performs well overall, especially in predicting healthy loans. However, its performance in predicting high-risk loans is lower, with a recall of 65%. Given that identifying high-risk loans is crucial, we recommend improving the model further before deployment.