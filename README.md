# Customer-Churn-Prediction-in-Telecom-Using-ML

This project aims to predict customer churn in the telecommunications industry using machine learning techniques. By analyzing customer demographics, service usage patterns, contract details, and payment behaviors, we build predictive models that help identify customers at high risk of churning, enabling proactive retention strategies.


## Model Prediction and Deployment

Here’s a snapshot of the customer churn prediction interface:

![image_alt](https://github.com/muhammedafsalpm/Customer-Churn-Prediction-in-Telecom-Using-ML/blob/4cf9a9bff9900e144a58867e14b58f817becea59/IMG-20241013-WA0008.jpg)
![image_alt](https://github.com/muhammedafsalpm/Customer-Churn-Prediction-in-Telecom-Using-ML/blob/3e7f3d256fcdf790a1fbf61f37d3335d65a6256d/IMG-20241013-WA0009.jpg)
Table of Contents

Introduction

Problem Definition

Objectives

Dataset

Methodology

Data Preprocessing

Exploratory Data Analysis

Feature Engineering and Selection


Machine Learning Models

Model Evaluation

Results

Deployment

Conclusion

References


## Introduction

Customer churn, where customers discontinue their service, poses a significant financial challenge for telecom providers. Predicting which customers are likely to churn allows companies to implement targeted strategies to retain them, enhancing customer satisfaction and reducing revenue losses.

## Problem Definition

The objective of this project is to build a model that predicts the likelihood of a customer churning based on historical data. Using the predictive insights, telecom companies can improve customer retention strategies and minimize attrition.

## Objectives

1. Data Exploration: Understand feature distributions and relationships.


2. Feature Engineering: Create and select the most informative features.


3. Model Development: Train and evaluate machine learning models.


4. Model Evaluation: Assess model performance with accuracy, precision, recall, and F1-score.


5. Business Insights: Provide actionable insights for targeted retention strategies.



## Dataset

Source: Kaggle - Telco Customer Churn

Description: 7,043 records with 21 features including demographics, account information, and customer service usage.

Target Variable: Churn (indicating if a customer has churned or not).


## Methodology

Data Preprocessing

Missing Values: Replaced missing values in the TotalCharges column with 0.

Encoding: Categorical features were converted to numerical values using Label Encoding and One-Hot Encoding.

Scaling: Min-Max scaling was applied to numerical features to ensure uniformity.


Exploratory Data Analysis

Univariate Analysis: Analyzed individual features to understand distributions.

Bivariate Analysis: Examined relationships between features and the target variable (Churn).


Feature Engineering and Selection

Feature Reduction: Used methods like Mutual Information, Lasso Regression, and Chi-Square tests to select relevant features.

Synthetic Minority Over-sampling Technique (SMOTE): Applied SMOTE to handle class imbalance in the target variable.


## Machine Learning Models

The following machine learning models were trained and evaluated:

1. AdaBoost Classifier


2. Gradient Boosting Classifier


3. Logistic Regression


4. Random Forest Classifier


5. Decision Tree Classifier


6. Voting Classifier (ensemble of multiple models)



## Model Evaluation

Models were evaluated using the following metrics:

Accuracy

Precision

Recall

F1-Score


Cross-validation was also applied to validate model performance across different data splits.

## Results

The Voting Classifier performed the best with an accuracy of 78.45% and balanced metrics for precision and recall, making it suitable for predicting customer churn.

Deployment

The final model was deployed using a web-based interface built with Streamlit. This interactive application allows users to input customer data and receive real-time churn predictions.

## Conclusion

Our analysis demonstrates that predictive modeling can effectively identify customers at risk of churning. The insights gained can help telecom providers develop retention strategies, optimize customer satisfaction, and ultimately reduce churn rates.

## References

1. Kaggle - Telco Customer Churn Dataset


2. Scikit-learn Documentation - https://scikit-learn.org/stable/
