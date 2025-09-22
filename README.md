# Loan-Prediction-Using-Logistic-Regression_Small-Dataset
🏦 Loan Prediction Model

This repository contains a simple machine-learning pipeline to predict loan approval (loan_status) from applicant data. The README below is generated after inspecting the notebook and dataset you uploaded — it reflects what the notebook actually does (no invented steps).

Project summary

Dataset shape: 61 rows × 8 columns.

Target column: loan_status.

Preprocessing performed: only pd.get_dummies() (one‑hot encoding) to convert categorical features into numeric features. No exploratory data analysis (EDA) or feature engineering was performed.

Model used: LogisticRegression from scikit-learn (the notebook defines and fits a LogisticRegression estimator).

Evaluation: 5-fold cross-validation using cross_val_score.

Dataset (columns)

The CSV contains the following columns (as found in loan.csv):

age

gender

occupation

education_level

marital_status

income

credit_score

loan_status ← target
