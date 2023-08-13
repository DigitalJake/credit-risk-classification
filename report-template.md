# Credit Risk

## Analysis

This analysis was completed to create a supervised ML model that would predict if a loan is a healthy or high-risk option for a lending isntitution. Our data set was a 77,500 line csv file that contained columns of various data about the loan (amount and interest rate) and the borrower's income, debt and accounts, and a column classifying the loan as healthy or high-risk. Only 2,500 of the total loans were classified as high-risk.:

### To preform the ML process the data was:

1. Split into labels and features, with the loan status (healthy or high-risk) being the label with the seven columns as features.
2. The data was then split into training and testing data sets.
3. A LR model from sklearn was created.
4. LR was chosen as we are classifying loans as healthy or high-risk.
5. The model was fit with the training data.
6. The model was evaluated by comparing the predictions with the test labels.

## Results

Accuracy: 0.99185
Balanced Accuracy: 0.95205

Precision

Healthy: 1.00
High-Risk: 0.85

Recall

Healthy: 0.99
High-Risk: 0.91

## Summary

The LR model predicts the healthy loans well. But, the model has a difficult opportunity to predict high-risk loans. This is shown with about 10% of high-risk loans being classified as healthy.

There are a limited number of  high-risk loans in the data for the model to learn from compared to healthy loans. 

### Model Pros and Cons:

Pros

Healthy loan prediction
Lots of data points for healthy loans

Cons

Limited high-risk loan data points
Loans are only in value up to $24,000




