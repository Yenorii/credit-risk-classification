# credit-risk-classification
UCF Data Sci Bootcamp - Module 20 Challenge<br>
## Overview of the Analysis

In this analysis, two machine learning models were developed to predict loan default risks using financial data. The dataset used credit scores, incomes, debt-to-income ratios, and employment histories. The target variable was the loan status, with 0 representing healthy loans and 1 representing high-risk loans.

Using logistic regression, the models were both evaluated using balanced accuracy scores, precision, and recall.
To address class imbalance, the RandomOverSampler technique was used to oversample the smaller class, 1, and balance out the rest of the dataset.

## Results

* Machine Learning Model 1:
  * Balanced Accuracy: 0.9941
  * Precision (Class 0): 1.00
  * Recall (Class 0): 0.99
  * Precision (Class 1): 0.85
  * Recall (Class 1): 0.99
  
* Machine Learning Model 2:
  * Balanced Accuracy: 0.9912
  * Precision (Class 0): 1.00
  * Recall (Class 0): 0.99
  * Precision (Class 1): 0.86
  * Recall (Class 1): 0.94

## Summary

Both models show strong performance with high accuracy, precision, and recall scores. Model 1 did have a higher balanced accuracy and precision for identifying high risk loans. Overall, both models could be used, model 1 for pinpointing high-risk loans, and model 2 for overall balanced accuracy.
