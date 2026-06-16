# Customer Churn Prediction

Machine learning project focused on predicting customer churn using customer demographics, account information, and banking activity data.

## Overview

The objective of this project is to identify customers who are likely to leave a financial institution. The workflow includes data preprocessing, feature engineering, model development, hyperparameter tuning, and performance evaluation.

## Dataset

The dataset contains customer demographic and account-related information, including:

* Credit score
* Country
* Gender
* Age
* Tenure
* Account balance
* Product count
* Card ownership
* Account activity status
* Estimated salary

**Target Variable:** `exit_status`

## Methodology

* Missing value imputation using KNN Imputer and Simple Imputer
* Feature scaling with StandardScaler
* One-Hot Encoding for categorical variables
* Variance Threshold feature selection
* Model training and evaluation
* Hyperparameter tuning using GridSearchCV

## Models

* Logistic Regression
* Perceptron
* K-Nearest Neighbors
* Decision Tree
* Random Forest
* Gradient Boosting
* AdaBoost

## Results

| Model             | Accuracy | F1 Score |
| ----------------- | -------- | -------- |
| Gradient Boosting | 86.07%   | 0.609    |
| AdaBoost          | 85.76%   | 0.601    |
| Random Forest     | 85.52%   | 0.599    |
| KNN               | 84.11%   | 0.574    |

**Best Model:** Gradient Boosting Classifier

## Technologies

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

## Skills Demonstrated

* Binary Classification
* Feature Engineering
* Missing Value Treatment
* Model Evaluation
* Hyperparameter Tuning
* Machine Learning Pipelines
