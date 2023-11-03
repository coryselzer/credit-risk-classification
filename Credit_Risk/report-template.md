# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of this analysis is to train and evaluate models to identify the credit worthiness of borrowers.  
* Explain what financial information the data was on, and what you needed to predict.
The data was based on numerical information of borrower's credit status and history.  We needed the loan status column (healthy vs. high risk loans).
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
The value count showed us there were 75,036 healthy loans and 2,500 high risk loans.
* Describe the stages of the machine learning process you went through as part of this analysis.
I had to split the data, fit the data, calculate predictions and then compute and print out the results.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
I used LogisticRegression to help fit the data and make predictions.  Also used the RandomOverSampler package to help add more data points and resample.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Model 1 showed a 0.95 balanced accuracy score.
  * Model 1 showed a perfect precision score and almost perfect recall score for 0 (healthy loans).  Model 1 showed a 0.85 precision score and 0.91 recall score.



* Machine Learning Model 2:
  * Model 2 showed a 0.993 balanced accuracy score.
  * Model 2 showed a perfect precision score and almost perfect recall score for 0 (healthy loans).  Model 2 showed a 0.84 precision score and an almost perfect recall score.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
Model 2 performs best as the balanced accuracy score is higher as well as the recall for both loan labels.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

Yes, I believe it is more important to predict the '1's.

If you do not recommend any of the models, please justify your reasoning.
