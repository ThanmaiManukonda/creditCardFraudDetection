# 💳 Credit Card Fraud Detection using Random Forest

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning. Since fraud datasets are highly imbalanced, accuracy is not a reliable metric. Therefore, this project uses precision, recall, and F1-score for proper evaluation.

This task was completed as part of the **AI & ML Internship – Task 9 (Ensemble Learning)**.

## 📂 Dataset
- 📍 Source: Kaggle Credit Card Fraud Dataset
- 💼 Credit card transactions made by European cardholders
- 🎯 Target column:
  - 0 → Non-Fraud
  - 1 → Fraud
- ⚠️ Highly imbalanced dataset

## 🛠 Tools & Libraries Used
- 🐍 Python  
- 📊 Pandas  
- 🔢 NumPy  
- 🤖 Scikit-learn  
- 📈 Matplotlib  
- 📉 Seaborn  
- 💾 Joblib  

## 🧪 Models Implemented

### 🔹 Logistic Regression (Baseline Model)
- Used as a baseline for comparison
- 📏 Feature scaling applied to fix convergence issues
- ⚖️ Class weighting used to handle class imbalance

### 🔹 Random Forest Classifier
- 🌲 Ensemble learning technique
- Trained with 100 decision trees
- ✅ Performed better than Logistic Regression in fraud detection

## 📊 Evaluation Metrics
Due to class imbalance, the following metrics were used:
- 🎯 Precision
- 🔍 Recall
- 📌 F1-score
- 🧮 Confusion Matrix

## 📈 Feature Importance
Feature importance was extracted from the Random Forest model to identify the most influential features contributing to fraud detection.

## 🏆 Results
- Logistic Regression achieved high accuracy but lower fraud recall
- Random Forest improved recall and F1-score for fraud cases
- 🌟 Ensemble learning proved more effective for this problem

## 💾 Model Saving
The trained model and scaler were saved using joblib:
- 📁 credit_card_fraud_random_forest.pkl
- 📁 scaler.pkl

## 📁 Repository Structure
📦 Credit-Card-Fraud-Detection  
├── 📄 creditcard.csv  
├── 📘 Credit_Card_Fraud_Detection.ipynb  
├── 💾 credit_card_fraud_random_forest.pkl  
├── 💾 scaler.pkl  
├── 📝 README.md  

## 🏁 Conclusion
Random Forest outperformed Logistic Regression in detecting fraudulent transactions. This project demonstrates the effectiveness of ensemble learning methods for handling imbalanced datasets.
