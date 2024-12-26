# Loan Prediction Practice Problem Repository

## Introduction
This repository contains the code and analysis for the "Loan Prediction Practice Problem" project. Below is an organized structure and code snippets for each step in the project workflow.

---

### Project Summary
Dream Housing Finance provides home loan services to its customers and aims to automate the customer loan eligibility process. This project seeks to develop a model that predicts loan approval status based on various customer details.

#### Datasets
- **Training Data (train.csv):** Contains information about customers and their loan eligibility status.
  - Target Variable: Loan Status (Yes/No).
- **Test Data (test.csv):** Contains information about new customers.
  - Target Variable: Loan Status (Yes/No) will be predicted for this dataset.
- **Submission File (submission.csv):** Contains the predicted loan status for the test data.
  - Columns:
    - Loan_ID
    - Loan_Status

#### Data Dictionary
| Variable          | Description                                |
|-------------------|--------------------------------------------|
| Gender            | Male/Female.                              |
| Married           | Marital status.                           |
| Dependents        | Number of dependents.                     |
| Education         | Graduate/Undergraduate education.         |
| Self_Employed     | Self-employment status.                   |
| ApplicantIncome   | Income of the applicant.                  |
| CoapplicantIncome | Income of the co-applicant.               |
| LoanAmount        | Loan amount requested.                    |
| Loan_Amount_Term  | Loan repayment term (in months).          |
| Credit_History    | Credit payment history.                   |
| Property_Area     | Urban, Semi-Urban, or Rural area.         |
| Loan_Status       | Was the loan approved? (Yes/No).          |


---

### Model Implementations
For this project, we explored multiple machine learning models. You can access the detailed implementations through the following links:

- [Logistic Regression](notebooks/logistic_regression.ipynb)
- [Decision Tree](notebooks/decision_tree.ipynb)
- [Random Forest](notebooks/random_forest.ipynb)
- [XGBoost](notebooks/xgboost.ipynb)

---
### Contributions

1. Univariate and bivariate analysis of loan features
2. Implementation of stratified k-fold cross-validation for model evaluation
3. Data cleaning, feature engineering, and handling missing values
4. Building and saving a logistic regression model

---

### TODOs

- Improve feature engineering with advanced techniques
- Test different classification algorithms (e.g., Decision Trees, Random Forests)
- Explore hyperparameter tuning with GridSearchCV

---

### License

This project is licensed under the MIT License.

---

### Acknowledgments

This project is inspired by the practice problem available on [Analytics Vidhya](https://www.analyticsvidhya.com/).


















---

## Yeni part:

# Machine Learning Models for Loan Approval Prediction

## Model Implementations

For this project, we explored multiple machine learning models. You can access the detailed implementations through the following links:

- [Logistic Regression](#)
- [Decision Tree](#)
- [Random Forest](#)
- [XGBoost](#)

## Model Performance

We evaluated the performance of the four models, and our analysis indicates that Logistic Regression and Random Forest performed the best in terms of validation scores and leaderboard scores.

| Model               | Validation Score | Leaderboard Score |
|---------------------|------------------|-------------------|
| Logistic Regression | 0.80            | Slightly lower    |
| Decision Tree       | 0.70            | Slightly lower    |
| Random Forest       | 0.80            | Slightly lower    |
| XGBoost             | 0.80            | Slightly lower    |

**Logistic Regression** and **Random Forest** emerged as the top-performing models, making them the most reliable choices for predicting loan approval status.



### YENi

# Loan Prediction Practice Problem Repository

## Introduction
Welcome to the repository for the "Loan Prediction Practice Problem" project. This project involves analyzing and predicting loan approval status using various customer details. Below you will find the organized structure, detailed explanations, and code snippets for each step of the project workflow.

## Table of Contents
- [Project Summary](#project-summary)
- [Datasets](#datasets)
- [Data Dictionary](#data-dictionary)
- [Model Implementations](#model-implementations)
- [Model Performance](#model-performance)

## Project Summary
Dream Housing Finance provides home loan services to its customers and aims to automate the customer loan eligibility process. This project seeks to develop a model that predicts loan approval status based on various customer details.

## Datasets
- **Training Data (train.csv):** Contains information about customers and their loan eligibility status.
  - Target Variable: Loan Status (Yes/No).
- **Test Data (test.csv):** Contains information about new customers.
  - Target Variable: Loan Status (Yes/No) will be predicted for this dataset.
- **Submission File (submission.csv):** Contains the predicted loan status for the test data.

### Columns:
- **Loan_ID**
- **Loan_Status**

## Data Dictionary

| Variable           | Description                                |
|--------------------|--------------------------------------------|
| Gender             | Male/Female                               |
| Married            | Marital status                            |
| Dependents         | Number of dependents                      |
| Education          | Graduate/Undergraduate education          |
| Self_Employed      | Self-employment status                    |
| ApplicantIncome    | Income of the applicant                   |
| CoapplicantIncome  | Income of the co-applicant                |
| LoanAmount         | Loan amount requested                     |
| Loan_Amount_Term   | Loan repayment term (in months)           |
| Credit_History     | Credit payment history                    |
| Property_Area      | Urban, Semi-Urban, or Rural area          |
| Loan_Status        | Was the loan approved? (Yes/No)           |

## Model Implementations

For this project, we explored multiple machine learning models. You can access the detailed implementations through the following links:

- [Logistic Regression](#)
- [Decision Tree](#)
- [Random Forest](#)
- [XGBoost](#)

## Model Performance

We evaluated the performance of the four models, and our analysis indicates that Logistic Regression and Random Forest performed the best in terms of validation scores and leaderboard scores.

| Model               | Validation Score | Leaderboard Score |
|---------------------|------------------|-------------------|
| Logistic Regression | 0.80            | Slightly lower    |
| Decision Tree       | 0.70            | Slightly lower    |
| Random Forest       | 0.80            | Slightly lower    |
| XGBoost             | 0.80            | Slightly lower    |

**Logistic Regression** and **Random Forest** emerged as the top-performing models, making them the most reliable choices for predicting loan approval status.

