🏷️ Project Title

Loan Approval Prediction using Random Forest Classification with Model Comparison

📌 Overview

This project focuses on predicting loan approval using Random Forest Classification and comparing its performance with Decision Tree and Logistic Regression models.

The goal is to understand ensemble learning, overfitting reduction, and model performance across different algorithms.

🎯 Objectives
Build a Random Forest Classification model
Reduce overfitting observed in Decision Tree
Improve model stability and performance
Compare with Logistic Regression and Decision Tree
📊 Dataset Description

The dataset contains applicant details such as:

Gender, Married, Dependents
Applicant & Coapplicant Income
Loan Amount & Term
Credit History
Property Area

🎯 Target: Loan_Status (Approved / Rejected)

⚙️ Methodology
1. Data Preprocessing
Handled missing values using mode & median
Dropped unnecessary columns
Applied one-hot encoding
2. Model Building
Implemented Random Forest Classifier
3. Hyperparameter Tuning
Used GridSearchCV
Tuned parameters:
n_estimators
max_depth
min_samples_split
min_samples_leaf
4. Model Evaluation
Accuracy
Precision, Recall, F1-score
Overfitting analysis
📊 Results
🔹 Random Forest (After Tuning)
Training Accuracy: 0.82
Testing Accuracy: 0.83
🔹 Logistic Regression
Accuracy: 0.83
🔹 Decision Tree
Accuracy: 0.82
⚖️ Model Comparison
Random Forest improved over Decision Tree by reducing overfitting
Logistic Regression and Random Forest achieved similar performance
Dataset showed patterns that could be handled well by simpler models
🧠 Key Learnings
Ensemble learning improves model stability
Random Forest reduces overfitting of Decision Trees
Model selection depends on data complexity
Simpler models can perform equally well
📌 Conclusion

Random Forest provided improved generalization compared to Decision Tree, but its performance was similar to Logistic Regression. This indicates that while ensemble methods are powerful, simpler models can still be effective depending on the dataset.

🚀 Future Work
Apply Random Forest Regression
Try Gradient Boosting (XGBoost, LightGBM)
Feature engineering for better performance
