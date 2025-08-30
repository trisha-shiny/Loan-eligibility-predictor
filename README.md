# Loan-eligibility-predictor
# Loan Eligibility Predictor

A Machine Learning project to predict whether a loan application should be approved or not, based on applicant details like income, education, credit score, etc.  

---

## Problem Statement
Banks want to predict whether an applicant is eligible for a loan.  
This project builds a classification model using **Logistic Regression** and **Random Forest**.

---

## Objective
- Preprocess applicant data (handle missing values, encode categorical features, scale numerical features).  
- Train models using Logistic Regression and Random Forest.  
- Evaluate performance using Accuracy, Confusion Matrix, and ROC curve.  

---

## Dataset
We use the **Loan Prediction dataset**:  
 [Kaggle Dataset](https://www.kaggle.com/datasets/ninzaami/loan-predication)

Columns include:
- Applicant Income, Coapplicant Income, Education, Credit History, Property Area, Loan Amount, etc.  
- Target: `Loan_Status` (Y = Approved, N = Not Approved).  

---

## Requirements
Install dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
