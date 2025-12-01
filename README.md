South_African_Fraud_Detection Machine Learning Project

This project is a full end-to-end fraud detection pipeline designed for portfolio demonstration and junior data science applications. It includes data wrangling, preprocessing, class balancing, model training, evaluation, and explainability.

1. Project Overview

Financial fraud is rare but costly, making fraud datasets highly imbalanced.
This project builds a machine learning solution to detect fraudulent transactions using:

XGBoost

SMOTENC oversampling

Feature engineering

Hyperparameter tuning (GridSearchCV)

SHAP explainability

The goal is to create a production-style pipeline that handles real-world data challenges.

2. Data Wrangling & Preprocessing

✔ Cleaned dataset and performed EDA
✔ Identified categorical & numerical columns
✔ Applied Label Encoding for SMOTENC compatibility
✔ Train/test split with stratification
✔ Balanced minority class using SMOTENC
✔ Scaled numerical features after oversampling

3. Exploratory Data Analysis (EDA)

Key visualizations include:

*Fraud class distribution

*Transaction amount distribution

*Boxplot of amount vs fraud class

*Correlation matrix (numeric features)

*Categorical frequency plots

4. Modeling

Model used: XGBoostClassifier

Hyperparameter optimization with GridSearchCV using ROC-AUC scoring.

Metrics reported:

Confusion Matrix

Classification Report

ROC-AUC Score

5. Explainability (SHAP)

SHAP TreeExplainer was used to interpret:

Global feature importance

Contribution of features to predictions

Fraud-driver insights

This demonstrates understanding of model interpretability—highly fundamental analytics.

6. Results

✔ Improved fraud detection after SMOTENC
✔ Balanced dataset improved recall for the minority class
✔ Good ROC-AUC performance
✔ SHAP plots showed the top influential features

📂 Files Included

South_African_Fraud_Detection_Notebook_with_EDA.ipynb

Fraud_Detection_Summary.pdf

Power BI dashboard

Dataset (synthetic version)

🎯 Skills Demonstrated

Data wrangling & preprocessing

Imbalanced data handling

Model development & tuning

Explainable AI (XAI)

Visualization (matplotlib)

Pipeline design for fraud detection

👤 Author

Kidima Medy Masuka
Junior Data Scientist |  Operations & Supply Chain Professiona
