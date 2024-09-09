# Customer Churn Prediction for Telecommunication Companies

## Project Overview

This project aims to predict customer churn for a telecommunication company using machine learning techniques. Customer churn refers to when customers discontinue their service, and accurately predicting this can help the company take proactive measures to retain customers.

## Dataset Description

The dataset includes various customer-related features that have been transformed into numerical format for modeling purposes. Key features include:

- **CustomerID**: Unique identifier for each customer.
- **Tenure**: Number of months the customer has been with the company.
- **MonthlyCharges**: The amount charged to the customer every month.
- **TotalCharges**: The total amount charged to the customer.
- **Contract**: Type of contract (e.g., month-to-month, one year, two years).
- **PaymentMethod**: Payment method used by the customer (e.g., electronic check, credit card).
- **Churn**: Target variable indicating whether the customer churned (Yes/No).

## Data Processing

- **Transformation**: Categorical features have been converted into numerical form using encoding techniques.
- **Handling Imbalanced Data**: Addressed class imbalance issues through resampling techniques to ensure balanced class representation.

## Machine Learning Models

1. **XGBoost Classifier**:
   - A gradient boosting framework designed for speed and performance, used for classification tasks.

2. **Random Forest Classifier**:
   - An ensemble learning method based on decision trees, effective for handling high-dimensional data.

## Model Evaluation

Both XGBoost and Random Forest classifiers have been evaluated using various metrics, including accuracy, precision, recall, and F1-score. The models' performance was compared to determine the best approach for predicting customer churn.

## Instructions for Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Barri-FZ2001/Customer-Churn-Prediction-for-Telecommunication-Companies.git
