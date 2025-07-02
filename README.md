📉🔍 Customer Churn Prediction using 🤖 Logistic Regression & XGBoost
This 📦 repository contains a project focused on predicting customer churn 🔄 in a banking environment using advanced machine learning techniques. The dataset contains customer information 🧾 including financial status, account activity, and demographics. Three models have been implemented — Logistic Regression (with 5️⃣ and 🔟 features) and an optimized XGBoost classifier 🚀 — to identify customers who are likely to leave the bank 🏦.

📁 Contents:
 logistic_regression_5_features.py — Logistic regression model using 5 features.
 logistic_regression_10_features.py — Enhanced logistic regression with 10 features and feature analysis.
 xgboost_model.py — Optimized XGBoost pipeline with outlier handling, SMOTE, PCA, and hyperparameter tuning.
 Churn_Modelling.csv — 📊 Dataset used for training and evaluation.
 README.md — This 📄 file, describing project structure and usage.
 requirements.txt — List of required libraries for the project.

🌟 Project Overview
Churn prediction 🔁 is a crucial aspect for customer-focused industries like banking 🏦. By predicting which customers are at risk of leaving, institutions can take proactive actions 🎯 to improve retention and customer satisfaction.

This project implements:
   📊 Data preprocessing
   🔁 SMOTE for handling class imbalance
   ⚙️ Polynomial feature engineering
   📏 Outlier handling using IQR
   🔐 Feature scaling (Standard & Robust)
   ⚙️ PCA for dimensionality reduction
   🧠 Model tuning using GridSearchCV

🔧 Steps Followed
 1)Data Loading and Cleaning
    Load and clean the dataset from Churn_Modelling.csv. Handle duplicates and missing values.
 2)Exploratory Data Analysis (EDA)
    Visualize feature distributions, correlation heatmaps, and outlier detection using boxplots 📦.
 3)Feature Engineering
 4)Logistic regression uses polynomial interaction terms.
 5)XGBoost pipeline includes Label Encoding, PCA, and robust scaling for numerical features.
 6)Model Building
 7)Logistic Regression with 5 and 10 features.
 8)XGBoost with GridSearchCV-based hyperparameter tuning and SMOTE.
 9)Model Evaluation
 10)Evaluate using Accuracy ✔️, Precision 🎯, Recall 🔁, F1 Score 📊, and Confusion Matrix 🔀.
 Feature Importance & PCA Analysis
 Understand which features or principal components impact churn predictions the most 💥.


 📊 Dataset
 🗂 File: Churn_Modelling.csv
 🧾 Rows: 10,000
 🎯 Target: Exited (1 = churned, 0 = retained)
 Features include: CreditScore, Age, Tenure, Balance, NumOfProducts, IsActiveMember, EstimatedSalary
 Categorical: Geography, Gender


📊 Visualizations
  🔥 Heatmaps showing correlation between features
  📦 Boxplots before and after outlier removal
  🔍 Confusion matrices for all models
  📊 Feature importances from XGBoost (via PCA components)
