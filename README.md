# 🏦 Loan Approval Prediction

## 📌 Project Overview
This project builds a supervised machine learning model to predict whether a loan application will be approved based on borrower features.  

The focus is on:
- Data preprocessing  
- Handling class imbalance  
- Comparing multiple models  
- Evaluating performance using key metrics  
- Providing business-oriented insights  

---

## 📂 Dataset
Dataset link:  
https://www.kaggle.com/datasets/bhanupratapbiswas/loan-approval-prediction-case-study  

The dataset includes applicant details such as income, credit history, loan amount, and other relevant features.

---

## 🎯 Goal
- Predict loan approval status using supervised learning  
- Handle missing and categorical data effectively  
- Address class imbalance  
- Compare multiple models  
- Evaluate using Precision, Recall, F1 Score, and ROC-AUC  
- Provide business insights from model results  

---

## ⚙️ Workflow

### 1. Data Preprocessing
- Handled missing values using mean/mode imputation  
- Encoded categorical variables using:
  - Label Encoding  
  - One-Hot Encoding  
- Scaled numerical features using standardization  

---

### 2. Handling Class Imbalance
- Applied techniques such as:
  - SMOTE (oversampling)  
  - Undersampling  
  - Class weights in models  

---

### 3. Exploratory Data Analysis (EDA)
- Analyzed feature distributions  
- Identified relationships between variables  
- Observed patterns affecting loan approval  
- Checked class imbalance  

---

### 4. Model Building
Models used:
- Logistic Regression  
- Decision Tree  
- Random Forest  

---

### 5. Model Evaluation
Evaluation metrics:
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  

---

## 📊 Results
- Tree-based models performed better than logistic regression  
- Handling class imbalance improved recall and F1 score  
- Logistic regression provided interpretability but lower performance  

---

## 💼 Business Insights
- Credit history, income, and loan amount are key factors in approval decisions  
- High recall ensures fewer eligible applicants are rejected  
- Balanced models help reduce financial risk  
- Model can support automated and consistent loan approval decisions  

---
