# Assignment15-CLY
Assignment 15 Loan Default Prediction with https://www.kaggle.com/datasets/yasserh/loan-default-dataset


Loan Default Prediction — README
This project builds a machine learning model to predict loan default risk using a publicly available Kaggle dataset. It includes full data preprocessing, feature engineering, model training, explainability, and fairness analysis.

Project Structure
Task 1 — Data Analysis & Cleaning

Loaded dataset, performed EDA, visualized distributions

Handled missing values (median/mode)

One‑hot encoded categorical variables

Scaled numerical features

Task 2 — Feature Engineering

Created DTI, Interest Burden (IB), credit score buckets, and LTV risk buckets

Added engineered features to improve predictive power

Task 3 — Model Training & Evaluation

Trained a Random Forest classifier

Achieved ~85% accuracy

Evaluated using confusion matrix, precision, recall, F1

Identified top predictors (Credit Score, loan amount, DTI, credit type, etc.)

Task 4 — Explainability & Fairness

Used SHAP (KernelExplainer) for global and local explanations

Visualized feature impact and individual predictions

Assessed fairness across demographic groups (e.g., gender)

Task 5 — Ethical Considerations

Discussed fairness, transparency, privacy, and bias mitigation

Provided recommendations for responsible deployment

Key Findings
Higher DTI, IB, loan amount, and LTV risk increase default likelihood.

Higher Credit Score strongly reduces risk.

SHAP confirms model behavior is consistent with financial intuition.

Technologies
Python, Pandas, NumPy

Scikit‑learn

SHAP

Matplotlib / Seaborn
