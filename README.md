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
