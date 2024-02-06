# Credit Card Fraud Prediction

## Overview
Credit card fraud is a significant concern for both credit card companies and customers, as fraudulent transactions can result in financial losses. This project aims to develop a predictive model to detect fraudulent credit card transactions using machine learning techniques.

The dataset used in this project contains transactions made by credit cards in September 2013 by European cardholders. It includes a highly unbalanced distribution of transactions, with only 492 frauds out of 284,807 transactions, accounting for 0.172% of all transactions.

## Objectives
Identify the most useful independent input variables out of the 30 available features for predicting fraudulent transactions ('Class').
Evaluate the effectiveness of Principal Component Analysis (PCA) in reducing the number of independent variables.
Implement and evaluate three classification models:
Logistic Regression
Support Vector Classifier (SVC)
Decision Tree Classifier
Provide detailed explanations of each model's workings and performance.

## Dataset
The dataset used for this project is available on Kaggle: 
(Credit Card Fraud Detection: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data.)

### Methodology
Exploratory Data Analysis (EDA): Explore the dataset to understand its structure, distributions, and relationships between variables.
Feature Selection: Identify the most relevant features for predicting fraudulent transactions.
PCA: Apply Principal Component Analysis to reduce the dimensionality of the dataset.
Model Implementation:
Logistic Regression: A linear regression model used for binary classification.
Support Vector Classifier (SVC): A classification algorithm that seeks to find the hyperplane that best separates the classes.
Decision Tree Classifier: A tree-based model that recursively splits the data based on the features to create decision rules.
Model Evaluation: Assess the performance of each model using metrics such as accuracy, precision, recall, and F1-score.
Conclusion: Summarize the findings and discuss the effectiveness of each model in detecting fraudulent transactions.

### Usage
Install the required libraries specified in the Credit_Card_Fraud_Detection_project.ipynb.
Download the dataset from the provided Kaggle link.
Run the Jupyter Notebook or Python script to execute the project.
Analyze the results and conclusions drawn from the models.

### Results
The results of each model, along with their performance metrics, are provided in the project report. Detailed explanations of the models and their effectiveness in detecting fraudulent transactions are also included.

### Future Work
Potential areas for further exploration and improvement could include:
Experimenting with additional feature engineering techniques.
Trying different algorithms or ensemble methods.
Fine-tuning hyperparameters to optimize model performance.
Exploring advanced anomaly detection techniques.


