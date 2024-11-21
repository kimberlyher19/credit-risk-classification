# __Credit Risk Classification Challenge (Module 20)__

## __Background__
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## __Instructions__
- The instructions for this Challenge are divided into the following subsections:

- Split the Data into Training and Testing Sets

- Create a Logistic Regression Model with the Original Data

- Write a Credit Risk Analysis Report

## __Credit Risk Analysis Report__

### Overview of the Analysis
Purpose: Analyze and identify the most suitable machine learning model for a peer-to-peer lending service to assess borrowers' creditworthiness based on loan risk.


Predictions: Whether a loan will be low or high-risk.


Stages: The analysis involved data processing, model selection, training, and evaluation.


### The Logistic Regression Model Results: 
- Accuracy score: 99% 
- Precision: 84%
- Recall of 94%

This model achieves strong performance; however, this is influenced by the imbalanced dataset, where healthy loans (low-risk) significantly outnumber non-healthy loans (high-risk). As a result, the model is better at predicting healthy loan statuses than identifying non-healthy ones.

### Summary
The regression model performed well, achieving an accuracy of 99% with high precision and recall for both healthy (low-risk) and high-risk loans. The predictions for healthy loans indicate that the model accurately identifies all low-risk loans in the dataset.

Based on these results, I recommend using logistic regression for credit risk analysis. Its strong performance metrics make it highly effective for distinguishing between low-risk and high-risk loans, demonstrating its suitability for this task.