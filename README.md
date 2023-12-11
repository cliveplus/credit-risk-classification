# credit-risk-classification
## Overview of the Analysis
The purpose if this analysis is to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. 

Financial informations from the dataset:\
-Loan Size\
-Interest Rate\
-Borrower Income\
-Debt to Income Ratio\
-Number of Account\
-Derogatory Marks\
-Total Debts\
-Loan Status

A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

Machine Learning process are as follows:\
1.Create the labels (X,y)\
2.Split the data into training and testing datasets by using train_test_split.\
3.Create and fit a Logistic Regression Model model by using the training data (X_train and y_train).\
4.Evaluate the model’s performance by generating a confusion matrix.

## Results
Precision:\
Precision for class 0 (healthy) is 1.00 or 100%\
Precision for class 1 (defaulting) is 0.87 or 87%

Recall:\
Recall for class 0 is 1.00, suggesting that the model correctly identified all instances of class 0.\
Recall for class 1 is 0.89, indicating that the model captured 89% of the actual instances of class 1.

## Summary
In summary, the model demonstrates high accuracy and performs well in terms of precision and recall.
