# credit-risk-classification
Module 20 Challenge
## Overview of the Analysis

This analysis required the use of logical regression models to identify the creditworthiness of borrowers from a peer-to-peer lending service.
With the provided information (Loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks and total debt), we have assessed whether a loan can be classified as healthy or high-risk.

To analyse this data, it was split into x and y variables. The sklearn toolkit was applied to split the data into training and testing datasets before being used to train the model.

## Results

### Machine Learning Model:
 *	Accuracy: 99%
 *	Healthy Loans
    *	Precision: 1
    *	Recall: 1
 *	High-Risk loans
    *	Precision: 0.87
    *	Recall: 0.89


## Summary

This model appears to have a good grasp of the data for which it is being used. However, given that its precision with the high-risk loans is at .87 with a recall of .89, it can be understood that further testing and data may be required to improve these numbers, as the high-risk loans are where more certainty is required for safe lending. 