Customer Churn Prediction Using Logistic Regression and XGBoost
This project focuses on predicting customer churn using machine learning models. It demonstrates preprocessing, feature engineering, oversampling, hyperparameter tuning, and evaluation using both Logistic Regression and XGBoost models on a real-world dataset.

Dataset
Source: Churn_Modelling.csv
Target variable: Exited (1 = Customer left the bank, 0 = Stayed)

 Models Implemented
✅ Logistic Regression (5 Features)
Features: CreditScore, Balance, HasCrCard, IsActiveMember, EstimatedSalary

Techniques:
Polynomial Interaction Features
SMOTE (to balance classes)
GridSearchCV for hyperparameter tuning
Evaluation metrics and confusion matrix
