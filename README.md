# credit-risk-classification


## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

In this analysis we will be using Machine Learning to analyze a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers

The financial data was on the loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt, loan status. The task was to predict the loan status, categorizing it as "Healthy Loan" or a "High Risk Loan" based on these financial attributes.

I used value_counts() to determine the distribution of loan statuses and the differnece between the different classes in order to build and evaluate the predictive models for loan risk analysis.

The stages of the machine learning process I went through as part of this analysis were to:

1 - Read the data and converted into the pandas dataframe.

2 -Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

3 -Split the data into training and testing datasets by using train_test_split.


4 -Fit a logistic regression model by using the training data (X_train and y_train).


5 -Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.


6 -Evaluate the model’s performance by doing the following:




* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

Methods used: Logistical regression. In logitical regression we statisically predict binary outcomes from data.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

- Healthy Loan Results: Precision: 1.00 Recall: .99 F1-score: 1.00

- High Risk Loan Results: Precision: 0.86 Recall: 0.91 F1-score: 0.88


* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

Accuracy is how often the model is correct—the ratio of correctly predicted observations to the total number of observations. 

Precision is the ratio of correctly predicted positive observations to the total predicted positive observations.


Recall is the ratio of correctly predicted positive observations to all predicted observations for that class. 


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.





