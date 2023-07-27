# Module 20 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of the analysis was to evaluate machine learning modules to predict loan default status based on financial information from the Lending Data. The goal is to create a model that can effectively distinguish between loans that will effectively distinguish between loans that will default and loans that will not to help financial institutions assess loan risk.

* Explain what financial information the data was on, and what you needed to predict.
The data consists of serveral financial features related to loan applicants such as age, income, credit score, loan amount, etc. Teh target variable, "loan_status," was used to determine whether a loan defaulted (1) or not (0).

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

The "loan_status" variable has two classes: 0 (non-default) and 1 (default). To get an idea of the class distribution, we can use value_counts():

Non-default (0): 18,759 samples
Default (1): 625 samples

* Describe the stages of the machine learning process you went through as part of this analysis.
Data prep
Data splitting
Model training
Model prediction
Model evaluation

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

The Primary method used logistion regression since it's best used for binary classification. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  - Balanced Accuracy Score: 0.94
  - Precision (default class 1): 0.87
  - Recall (default class 1): 0.89

* Machine Learning Model 2:
  - [Balanced Accuracy Score, Precision, Recall not provided]

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

## Answer

Logisic regression model (Model 1) performed with high accuracy, precision, and recall for both default and non-default cases. 

Model 2 was mentioned, but specific performance metrics were not provided, making it difficult to compare. As a result, we cannot make a definitive recommendation without additional information.

Based on the available results, Model 1 (logistic regression) is recommended for predicting loan default status due to its strong performance and balanced predictions for both classes. However, further evaluation and comparison with additional metrics for Model 2 would be necessary to make a more conclusive recommendation.
