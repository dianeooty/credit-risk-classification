# Module 12 Report Template

## Overview of the Analysis

The objective of this is analysis, is to use the historical lending activity dataset, to build and implement a model that can identify the credit worthiness of borrowers.  The model will predict the risk levels for each borrower and classify their loan status as either healthy or high-risk.  

The financial information used to build the model consisted of the loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks and total debt.  These are key information that assesses the borrower's ability to repay the loan.

In order to create a working model to best predict the loan status, the dataset was split into training and testing sets.  The first model used for the loan status predictions was Logistic Regression.  The second model, was RandomOVerSampler with resampled data from the dataset.  After processing the data with the model, the prediction results were then displayed with the confusion matrix and classification report was generated.  


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy: 95.20%
  * Precision: healthy-100%, high-risk-85%
  * Recall: healthy-99%, high-risk-91%

* Machine Learning Model 2:
  * Accuracy: 99.36%
  * Precision: healthy-100%, high-risk-84%
  * Recall: healthy-99%, high-risk-99%

## Summary

Machine Learning Model 2 resulted in a better performance than Model 1.  Although the high-risk precision decreased by 1%, the recall results for the high-risk loans improved with Model 2. We also see an improvement in the balanced accuracy score.  I recommend using Model 2 for the assessment when checking for high-risk loans.

If checking for healthy loans, Model 1 may provide a slightly better result, but overall assessment Model 2 fits best.

Checking for both, healthy and high-risk loans are important.  It depends on what we are trying to achieve, such as approving additional loans to the borrower or implementing precautionary measures to mitigate high-risk loans.  

