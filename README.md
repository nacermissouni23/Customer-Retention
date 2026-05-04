# 📊 Customer Churn Prediction + Retention System

## 🎯 Overview
This project builds an end-to-end machine learning system to predict customer churn and convert predictions into actionable retention strategies.

Instead of only predicting churn, the system assigns each customer a risk level and recommends a business action.

---

## 🧠 Problem Statement
Telecom companies lose customers continuously. The goal is to:
- Predict churn probability
- Identify key drivers of churn
- Prioritize customers for retention efforts

---

## 📦 Dataset
Telco Customer Churn dataset  
- ~7043 customers  
- 21 features  
- Target: `Churn (Yes/No)`

---

## ⚙️ Workflow

### 1. Data Understanding
- Dataset structure analysis
- Missing value handling
- Target distribution analysis

### 2. Exploratory Data Analysis
- Contract vs churn behavior
- Tenure distribution insights
- Service-based churn patterns
- Billing impact analysis

### 3. Data Preprocessing
- Cleaned missing values
- Encoded categorical variables
- Converted target into binary format
- Removed irrelevant features (customerID)

### 4. Modeling
- Baseline: Logistic Regression
- Advanced: XGBoost Classifier

### 5. Evaluation
- Accuracy, Precision, Recall, F1-score
- ROC-AUC comparison
- Confusion matrix analysis
- Feature importance extraction

### 6. Business Layer
- Churn probability scoring
- Risk segmentation (Low / Medium / High)
- Action recommendations per customer group

---

## 🧠 Key Insight
The system does not only predict churn, it **translates predictions into decisions**, enabling proactive customer retention.

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn

---

## 🚀 Outcome
A complete churn intelligence system that helps businesses:
- Identify at-risk customers early
- Reduce churn rate
- Optimize retention campaigns
- Improve customer lifetime value