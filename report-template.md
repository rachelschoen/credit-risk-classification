# Module 12 Report Template

## Overview of the Analysis

The goal of this analysis is to develop a supervised machine learning model to predict whether a loan is healthy (class 0) or high-risk (class 1). We will utilize logistic regression as a binary classifier for our model. The analysis was performed on financial data, with a specific focus on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The objective is to classify the loan status as either healthy (0) or high-risk (1). The dataset used consists of 77,500 entries in a CSV file.

The stages of the machine learning process in this analysis included:

    - Splitting the data into labels and features, with the loan status (healthy or high-risk) as the label and the remaining seven columns as features.
    - Dividing the data into training and testing sets.
    - Creating a Logistic Regression model using sklearn.
        - Logistic Regression was chosen as a binary classifier to classify loans as either healthy or high-risk.
    - Fitting the model with the training data.
    - Making predictions using the test data.
    - Evaluating the model’s performance using accuracy, precision, and recall scores.


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
