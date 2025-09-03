# Project: Customer Churn Prediction

Predicting customer churn using machine learning to help businesses proactively retain customers and reduce revenue loss.

---

## Overview

Customer churn—the percentage of customers that stop using a service—is a major problem for businesses. This project aims to develop a machine learning model that accurately predicts which customers are likely to churn, enabling companies to take preemptive actions and improve customer retention.

---

## Tools & Technologies

- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, and xgboost

---

## Dataset

- **Source:** Telco Customer Churn from Kaggle
- **Rows:** ~7,000 customer records
- **Target:** `Churn` (Yes/No)
- **Features Include:**
  - Customer tenure
  - Monthly charges
  - Contract type
  - Internet service usage
  - Payment methods
  - And more

---

## Project Pipeline

### 1. Data Preprocessing
- Cleaned missing values
- Label-encoded categorical features
- Normalized numerical variables

### 2. Exploratory Data Analysis (EDA)
- Identified churn trends by contract type, payment method, and tenure
- Visualized feature distributions and correlations

### 3. Model Training
- Evaluated several models:
  - Logistic Regression
  - Random Forest
  - XGBoost (best performance)
- Tuned hyperparameters using cross-validation

### 4. Model Evaluation
- Used precision, recall, F1-score, and ROC-AUC for evaluation
- Visualized confusion matrix and ROC curve

---

## Results

- **Best Model:** XGBoost Classifier
- **Accuracy:** 86%
- **F1 Score:** 83%
- **Top Predictive Features:**
  - Contract Type
  - Tenure
  - Monthly Charges
  - Internet Service

---

# Contact
- LinkedIn: [linkedin.com/in/anubhav-dogra](https://www.linkedin.com/in/anubhav-dogra/)
- Website: [My Portfolio](https://fuschia-yak-f61.notion.site/Anubhav-Dogra-211d6dc537bf8027bfe3ebdf322032ec)

