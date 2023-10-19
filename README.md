# Credit Risk Classification Challenge

Repository for the Monash University Bootcamp Module 20.

## File Structure

- `credit_risk_classification.ipynb`: The primary Jupyter Notebook with the analysis workflow, from data loading to model evaluation.
- `Resources` folder: Contains the `lending_data.csv` - a CSV data file providing details on various loans and their risk categorization.
- `README.md`: The document you're currently reading, which offers an overview of the project and lists the included files.

## Project Overview

This project delves into the realm of loan creditworthiness, aiming to predict the credit risk associated with each loan. Using the `lending_data.csv` dataset, which contains historical lending activity data, the project aims to build a model that can classify the creditworthiness of borrowers. The project covers:

### Data Splitting
- Loading the dataset and splitting it into training and testing sets.

### Logistic Regression Model 
- Training a logistic regression model on the training data.
- Making predictions on the test data.
- Evaluating the model's performance using metrics like the confusion matrix and classification report.

## Credit Risk Analysis Report

Targeted Prediction:
Healthy Loan (0): Represents loans that are expected to be repaid.
High-Risk Loan (1): Indicates loans that are at a high probability of defaulting.

## Results
The logistic regression model was employed, and the findings are as follows:

![class_report](https://github.com/ashakozak/credit-risk-classification/assets/134185577/36be826c-901e-479b-a199-be915b94f67d)

Healthy loan (0):
Precision: Out of all the loans that the model predicted to be healthy loans, 100% of them actually were.
Recall: Out of the 18759 loans which were actually healthy loans, the model correctly identified 18759 of them, which is 100%.
F1-Score: The harmonic mean of precision and recall for healthy loans is 100%.

High-risk loan (1):
Precision: Out of all the loans that the model predicted as a high-risk loan, 87% of them actually were high-risk.
Recall: Out of the 625 loans which were actually high-risk loans, the model correctly identified 556 of them, which is 89%.
F1-Score: The harmonic mean of precision and recall for high-risk loans is 88%.

Overall Performance:
Accuracy: The model exhibited an accuracy of 99%, signifying it correctly predicted the loan category (either healthy or high-risk) for 99% of the loans in the test set.

## Summary

The model has showcased a high degree of accuracy, making it a robust tool for credit risk prediction.
The precision and recall values for both healthy and high-risk loans are commendable, ensuring a minimal rate of false positives and false negatives.
With the potential financial implications of high-risk loans, the high recall value for this category is particularly noteworthy, as it ensures that a significant majority of such loans are rightly flagged.
Recommendation: I would endorse the use of this logistic regression model for the company's credit risk evaluation. Its strong performance metrics are indicative of its reliability in differentiating between healthy and high-risk loans, which is instrumental for prudent lending decisions.


