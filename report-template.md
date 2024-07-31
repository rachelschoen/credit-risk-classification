# Module 12 Report Template

## Overview of the Analysis

The goal of this analysis is to develop a supervised machine learning model to predict whether a loan is healthy (class 0) or high-risk (class 1). We will utilize logistic regression as a binary classifier for our model. The analysis was performed on financial data, with a specific focus on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The objective is to classify the loan status as either healthy (0) or high-risk (1). The dataset used consists of 77,500 entries in a CSV file.

The stages of the machine learning process in this analysis include:

- Splitting the data into labels and features, with the loan status (healthy or high-risk) as the label and the remaining seven columns as features.
- Dividing the data into training and testing sets.
- Creating a Logistic Regression model using sklearn.
    - Logistic Regression was chosen as a binary classifier to classify loans as either healthy or high-risk.
- Fitting the model with the training data.
- Making predictions using the test data.
- Evaluating the model’s performance using accuracy, precision, and recall scores.


## Results

The following is a description of the Logistic Regression Model Accuracy, Precision, and Recall scores.

- Accuracy: The overall accuracy of the model is 0.99, meaning it correctly classifies 99% of the instances.

- Precision
    - Healthy Loan (class 0): 1.00, or 100%
    - High-Risk Loan (class 1): 0.85, or 85%

- Recall
    - Healthy Loan (class 0): 0.99, or 99%
    - High-Risk Loan (class 1): 0.91, or 91%


## Summary

The logistic regression model performs very well in predicting healthy loans (class 0), with a precision of 1.00 and recall of 0.99. For high-risk loans (class 1), the model also performs well, achieving a precision of 0.85 and recall of 0.91.

The lower precision and recall for predicting high-risk loans (class 1) may be due to our imbalanced dataset, where the support test data for class 1 is only 619 compared to 18,765 for class 0. This imbalance leaves room for improvement in predicting high-risk loans, as the model has fewer high-risk loans to learn from compared to the number of healthy loans. Adding more high-risk loan data could enhance the model's performance.

In loan classification, preventing high-risk loans is more critical than approving loans, as the financial loss from a defaulted loan can outweigh the interest earned from a healthy loan. The overall accuracy of the model is a high 99%.
