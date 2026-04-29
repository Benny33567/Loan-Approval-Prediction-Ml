# Loan Approval Prediction using Machine Learning

This project predicts whether a loan application will be approved or rejected using applicant financial, asset, and credit-related features.

## Project Overview

The goal of this project is to build a machine learning model that can classify loan applications as Approved or Rejected.

The workflow includes:

- Data loading and cleaning
- Exploratory Data Analysis
- Data profiling using ydata-profiling
- Feature engineering
- Preprocessing using ColumnTransformer
- Model comparison using cross-validation
- Hyperparameter tuning using GridSearchCV
- Final model evaluation using accuracy, precision, recall, F1-score, and confusion matrix
- Feature importance analysis

## Dataset

The dataset contains features such as:

- Number of dependents
- Education
- Self-employment status
- Annual income
- Loan amount
- Loan term
- CIBIL score
- Residential asset value
- Commercial asset value
- Luxury asset value
- Bank asset value
- Loan status

## Models Used

The following models were compared:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost

## Final Result

The final model achieved very high accuracy on the test dataset.

Further analysis showed that `cibil_score` is the most important predictor of loan approval. This explains the near-perfect classification performance.

To verify this, model performance was also checked after removing `cibil_score`.

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- ydata-profiling

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/Benny33567/Loan-Approval-Prediction-ML.git
