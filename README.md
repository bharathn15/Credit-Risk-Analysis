# Credit-Risk-Analysis
IIITB DS Project for Business Analytics


# Credit Risk Analysis

## Project Overview
This project builds a **credit risk model** to classify loan applications as **approved** or **rejected** based on past applicant behavior and bureau data.

## Dataset
- **applications_base.csv**: Contains loan applicant details.
- **bureau.csv**: Contains past credit history from credit bureaus.

## Steps Performed
1. **Data Cleaning & Preprocessing**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Engineering**
4. **Handling Class Imbalance (SMOTE)**
5. **Model Training (Random Forest, XGBoost)**
6. **Model Evaluation (Precision, Recall, ROC-AUC)**

## Key Findings
- **Loan Amount (`AMT_CREDIT`)** and **Max Overdue Days (`CREDIT_DAY_OVERDUE`)** are key indicators.
- **XGBoost performed best** with **ROC-AUC ~0.75+**.
- **SMOTE improved recall** for high-risk applicants.

## Files
- `Credit_Risk_Model.ipynb` → Main Python notebook.
- `Credit_Risk_Analysis.pdf` → Business insights presentation.
- `README.md` → Project documentation.

## How to Run
1. Clone the repository:
