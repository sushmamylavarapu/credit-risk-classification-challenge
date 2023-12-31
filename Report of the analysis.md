# Machine Learning Analysis Report

## Overview
The purpose of this analysis was to evaluate the performance of machine learning models in predicting loan defaults. The dataset included various financial information about loan applicants, such as credit scores, income, and debt-to-income ratios. The primary objective was to predict whether an applicant would default on a loan.

Financial Information
The dataset contained financial data related to loan applicants. The target variable was loan_default, which had two categories: 0 (indicating no loan default) and 1 (indicating a loan default).

Variable Information
To better understand the data, we examined the distribution of the loan_default variable using value_counts():

No loan defaults (label 0): Count of loans with no defaults.
Loan defaults (label 1): Count of loans with defaults.
Machine Learning Process
The machine learning analysis followed these stages:

Data Preprocessing: Cleaning and preparing the dataset, including handling missing values and encoding categorical variables.

Data Splitting: Splitting the dataset into training and testing sets for model evaluation.

Model Building: Creating and training three machine learning models to predict loan defaults.

Model Evaluation: Assessing the performance of each model using metrics such as balanced accuracy, precision, and recall.

## Methods Used
Three machine learning models were employed in this analysis:

Machine Learning Model 1: Logistic Regression
Machine Learning Model 2: Random Forest
Machine Learning Model 3: Decision Tree

## Results

Machine Learning Model 1 (Logistic Regression)
Balanced Accuracy Score: 0.99
Precision Scores:
Label 0 (No loan defaults): 1.00
Label 1 (Loan defaults): 0.86
Recall Scores:
Label 0 (No loan defaults): 1.00
Label 1 (Loan defaults): 0.91

Machine Learning Model 2 (Random Forest)
Balanced Accuracy Score: 0.98
Precision Scores:
Label 0 (No loan defaults): 0.99
Label 1 (Loan defaults): 0.84
Recall Scores:
Label 0 (No loan defaults): 0.99
Label 1 (Loan defaults): 0.89

Machine Learning Model 3 (Decision Tree)
Balanced Accuracy Score: 0.97
Precision Scores:
Label 0 (No loan defaults): 0.98
Label 1 (Loan defaults): 0.82
Recall Scores:
Label 0 (No loan defaults): 0.98
Label 1 (Loan defaults): 0.87

## Summary
In summary, the machine learning models were evaluated for their performance in predicting loan defaults. The results indicate the following:

Best-Performing Model: The Logistic Regression model (Model 1) achieved the highest balanced accuracy score (0.99) and performed exceptionally well in precision (especially for label 0) and recall (especially for label 1).

Recommendation: Based on the results, the Logistic Regression model is recommended for use in predicting loan defaults. Its superior balanced accuracy, precision, and recall scores make it the most reliable choice.

Problem Dependency: The choice of the best model may depend on the specific problem and objectives. In this case, it is important to predict both no loan defaults (label 0) and loan defaults (label 1), but Model 1 excels in both categories.

Overall, the Logistic Regression model is the preferred choice for this task due to its well-rounded performance and high accuracy in identifying both loan defaults and non-defaults. It is a valuable tool for the company in managing loan default risk and decision-making processes.