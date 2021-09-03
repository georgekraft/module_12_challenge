# Module 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

I used a logistic regression model in order to categorize loans into healthy and high-risk loans which can then be used to predict whether un-labeled loans are healthy or high-risk.  For this purpose I used a loan database that had features and labels whether a loan is healthy or high-risk for each loan.  First I split the loan database into training and testing data sets.  Creating a logistic regression model then allowed to predict the label of a loan and evaluate the performance of the model, e.g. by determining the accuracy, prediction and recall scores.  I then resampled the original data by oversampling the minority of high-risk loans in order to mitigate biases due to sampling.  

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1 with original data:
  * Accuracy scores: 0.952
  * Precision scores for healthy loans: 1.00 and high-risk loans: 0.85
  * Recall scores for healthy loans: 0.99 and high-risk loans: 0.91

* Machine Learning Model 2 with oversampled data:
  * Accuracy scores: 0.994
  * Precision scores for healthy loans: 1.00 and high-risk loans: 0.84
  * Recall scores for healthy loans: 0.99 and high-risk loans: 0.99

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. 

Model 2 with the oversampled data has better accuracy scores and better recall scores for high-risk loans than Model 1 which means that Model 2 is better at identifying the truly high-risk loans than the Model 1. At the same time precision and recall scores for healthy loans for Model 2 are the same as for Model 1 while precision scores for high-risk loans for Model 2 is only slightly lower than for Model 1. Therefore, Model 2 seems to perform best overall.
