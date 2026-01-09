# CodeAlpha Credit Scoring Model
A machine learning model that predicts whether a borrower can repay a bank loan.
# 💰 Credit Risk Prediction

## 📌 Project Overview
This project develops a Credit Scoring Model to assess a person’s financial reliability using their financial history. It helps predict whether a loan applicant is likely to repay the loan or default, enabling banks to evaluate financial risk.

## Objective
The aim is to build a machine learning model to predict loan defaults, helping banks make safer, data-driven lending decisions by analyzing customer financial data and evaluating model performance.

## 📂 Dataset
- **Dataset Name:** Credit Risk Dataset
- **File:** credit_risk_dataset.csv
- **Target Variable:** loan_status
  - `0` → Non-Default (Safe)
  - `1` → Default (Risk)
- **Key Features:**
  - Person Age & Income
  - Home Ownership
  - Employment Length
  - Loan Amount & Intent
  - Interest Rate

## Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## 🔄 Project Workflow
1. Data Loading
2. Data Exploration
3. Data Cleaning 
4. Data Preprocessing
5. Feature Selection
6. Train-Test Split
7. Model Training (Decision Tree Classifier)
8. Model Prediction
9. Model Evaluation
10. Result Analysis(ROC-AUC Curve)

## 🤖 Machine Learning Model
**Decision Tree Classifier:** It provides a straightforward, flowchart-style approach to decision-making. It simplifies complex financial information into simple "True or False" questions, making the bank's decision process easy to understand.

## 📊 Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Curve
  
## 📈 Results
- Decision Tree classifier achieved good prediction accuracy by creating logical rules for credit approval.
- ROC–AUC analysis showed reliable classification performance.
- confusion matrix provided insights into correct and incorrect prediction
