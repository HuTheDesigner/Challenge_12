# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).


The purpose is to create a machine learning model (mlm) that can predict the credit worthiness of borrowers.
Csv data and historical activity from a peer-to-peer lending company to see if the borrowers would repay the loans.
Credit risk and healthy loans are types of risk to assess. categorizing the loans as risky and healthy are part of the task. In my analysis, 
Logistic Regression model is used on the test data, 95 percent accuracy with this data. Oversampling is how i overcame the issue with the original method which is not as accurate as id like to be. in doing the oversampling method, accuracy to the data has increased to 99. 
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
Machine Learning Model 1: 
overall Accuracy: 95.2%
healthy loans: 100%
high-risk loans: 91%
~ish 

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
Machine Learning Model 2: Model 2 Accuracy: 99.3%
healthy loans: 100%
high-risk loans: 99%
~ish
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best?  How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
model 2 was waaaay more accurate and performed best. the results of the filtered loans is how i knew it performed better.
objectively youre trying to identify the high risk loans.
If you do not recommend any of the models, please justify your reasoning.
model 1 is not accurate, with a money based business every penny counts. so the more accurate the better.