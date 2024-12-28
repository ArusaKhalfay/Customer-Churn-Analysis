# Churn Analysis - Model Building

## Project Overview

This project focuses on **Churn Analysis** for a telecom company. The objective is to analyze customer data, identify patterns of churn, and develop a predictive model to classify customers at risk of leaving. By understanding the factors that drive customer churn, the analysis provides actionable insights for improving customer retention strategies.

## Dataset

- **Source**: The dataset contains information on 7,032 customers with 52 features.
- **Key Features**:
  - **Demographics**: Senior citizen status, gender.
  - **Services**: Internet, phone, and streaming services.
  - **Contract Details**: Contract type, tenure, payment methods.
  - **Target Variable**: `Churn` (binary indicator of customer churn).

## How It Was Done

### 1. Exploratory Data Analysis (EDA)
- Explored customer demographics and service usage trends.
- Visualized relationships between features and churn behavior.
- Identified correlations between variables to guide model selection.

### 2. Feature Engineering
- Encoded categorical variables using one-hot encoding.
- Grouped tenure into logical intervals for better analysis.
- Standardized numerical variables like `MonthlyCharges` and `TotalCharges`.

### 3. Model Building
- Trained multiple machine learning models:
  - **Logistic Regression**
  - **Decision Trees**
  - **Random Forest**
- Applied cross-validation for robust performance evaluation.

### 4. Model Evaluation
- Assessed models using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - ROC-AUC
- Fine-tuned hyperparameters to enhance model performance.

### 5. Insights and Recommendations
- Highlighted key drivers of churn, such as:
  - Contract types (month-to-month contracts had higher churn rates).
  - Payment methods (electronic check payments correlated with higher churn).
- Suggested interventions:
  - Incentives for long-term contracts.
  - Improvements in service reliability to retain customers.
