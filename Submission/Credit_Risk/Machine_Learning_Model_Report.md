# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to create a predictive model that can predict healthy low risk loans and high risk loans.
* The analysis was based on lending data with data types such as interest rates, borrower income, debt to income ratio, number of accounts, derogatory marks, etc. in order to predict loan health and the risk associated with providing loans.
* One of the main variables used to predict was loan status.
* For the machine learning process a logistic regression model was created with the original data to create the predictions. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model Logistic Regression Model:
    * The Logistic Regression Model was very accurate in predicting healthy loans and accurate in predicting high risk loans. The precision score was a perfect "1" for healty loans and ".87" with high risk loans. Which shows room for improvement with the high risk loans. In recall scores, the healthy loans were perfect again, with the high risk loans being ".95" which is good.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* When predicting healthy loans the model works best based on the numbers being perfect and having a high number to test.
* The performance does depend on what you are trying to identify and there is room for improvement with this model if your focus is solely trying to identify high risk loans. In that case I would not recommend it just yet until its high risk loan prediction precision gets to at least the mid 90s.
