# Module 12 Report Template

## Overview of the Analysis

In this analysis, we want to use the logistic regression model to predict high risk and healthy loans from the dataset provided.
Then, we resample the data then use the logistic model on the resampled data to predict high risk and healthy loans and compare 
the results to the first test.

## Results
* Logistic Regression without Resampling :
      precision    recall  f1-score   support
  0       1.00      1.00      1.00     18759
  1       0.87      0.89      0.88       625


* Logistic Regression without Resampling (Using RandomOversampler):
      precision    recall  f1-score   support
  0       1.00      1.00      1.00     18759
  1       0.87      1.00      0.93       625

## Summary

To summarize, resampling the data then using logistic regression performed better than just splitting the data into training and testing datasets 
then using logistic regression. We want to correctly identify loaners who will be able to pay back their loans and also correctly identify loaners
who will most likely be high risk.
