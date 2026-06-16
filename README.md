# Customer Churn Prediction

Predicting customer churn for a financial institution using machine learning.

## Project Highlights

* Performed exploratory data analysis (EDA) on 90,000 customer records
* Handled missing values using KNN and frequency-based imputation
* Applied feature engineering, scaling, and one-hot encoding
* Trained and evaluated 7 machine learning models
* Performed hyperparameter tuning using GridSearchCV
* Compared models using Accuracy, Precision, Recall, F1-Score, and ROC-AUC

## Visualizations

### Customer Churn Distribution

![Customer Churn Distribution](images/churn_distribution.png)

### Estimated Salary vs Exit Status

![Salary vs Exit Status](images/salary_vs_exit.png)

### Account Balance vs Product Count

![Balance vs Product Count](images/balance_vs_products.png)

## Models Evaluated

* Logistic Regression
* Perceptron
* K-Nearest Neighbors
* Decision Tree
* Random Forest
* Gradient Boosting
* AdaBoost

## Best Model

**Gradient Boosting Classifier**

| Metric   | Score |
| -------- | ----: |
| Accuracy | 86.1% |
| F1 Score | 0.609 |
| ROC-AUC  | 0.878 |

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Repository Structure

```text
Customer_Churn_Prediction.ipynb
README.md
requirements.txt
images/
```

## Future Work

* Address class imbalance using SMOTE
* Explore XGBoost and LightGBM
* Add model explainability with SHAP
* Deploy as a web application

```
```
