Employee Attrition Prediction

📌 Project Overview

Employee attrition is a critical challenge for companies, leading to the loss of valuable expertise and business disruption. This project aims to build a predictive model to identify employees likely to leave the company, helping organizations take proactive measures to improve retention.

📂 Dataset

Source: Kaggle

Size: ~900 records

Features: 16 columns, including employee name, age, gender, promotion status, job role match, marital status, experience, and department.

🔍 Exploratory Data Analysis (EDA) Findings

Gender: Higher retention rate among males.

Promotion: Employees who were promoted tend to stay longer.

Department: 90% of employees belong to the operations section.

Marital Status: Single and married employees dominate the workforce.

Job Role Match: Employees with the right job role match are more likely to stay.

🔧 Data Preprocessing & Feature Engineering

Handling Missing Values: Imputation techniques applied where necessary.

Encoding Techniques:

One-Hot Encoding for nominal categorical features.

Label Encoding for ordinal categorical features.

Dummy Encoding for optimized categorical representation.

🏆 Machine Learning Models Used

Logistic Regression

Random Forest (Selected as Best Model)

Evaluation Metrics:

F1 Score (Used due to imbalanced dataset)

ROC-AUC Curve

🎯 Model Performance

Random Forest outperformed Logistic Regression based on F1 Score and AUC-ROC Curve.

📊 Evaluation Metrics

F1 Score: Harmonic mean of Precision & Recall, ensuring a balance between both.

Accuracy: Overall correctness of the model.

Precision & Recall: Balance between false positives and false negatives.

ROC-AUC Curve: Measures model performance across various classification thresholds.

🤖 Machine Learning Concepts Used

Cross-Validation: Ensuring model generalization.

Bagging vs. Boosting: Used for improving model robustness.

Smoothing: Reducing variance in predictions.

💡 Use Cases

HR Analytics: Predicting employee turnover to improve retention strategies.

Resource Planning: Ensuring workforce stability.

Performance Insights: Identifying key factors influencing attrition.
