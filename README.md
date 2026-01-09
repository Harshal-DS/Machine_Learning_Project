# Customer Churn Prediction
Project Overview
In today's highly competitive business environment,retaining customers is a critical factor for long-term success.
Predicting customer churn can help organizations take proactive steps to retain customers, thus minimizing revenue loss.
In this project i build a machine learning model that can predict whether a customer will
churn based on their demographic, account, and service-related data.

*Dataset Information*
Binary Classification Problem
independent variable=( customerID, gender, SeniorCitizen,Partner,Dependents,tenure,PhoneService,MultipleLines,InternetService,OnlineSecurity ,
OnlineBackup,DeviceProtection,TechSupport,StreamingTV,StreamingMovies,Contract ,PaperlessBilling,PaymentMethod, MonthlyCharges ,TotalCharges)
dependent variable: Churn = Yes or No

Data Preprocessing
Converted TotalCharges to numeric
Dropped rows with missing values
Applied Label Encoding and One-Hot Encoding
Scaled numerical columns using StandardScaler
Addressed class imbalance using SMOTE
Data Cleaning & Handling Missing Values
Ensured no nulls remained using and drop unwanted column

Outliers & Label Encoding
Checking outliers in numeric columns
label encoding to categorical column
checking count of categorical columns

Feature Selection,scalling and spliting
Ploting correlation
Feature Scaling especially for Models like KNN and SVM
Splitting the Data in train_test_split

Model Training:
Logistic Regression
Decision Tree
Random Forest
K-Nearest Neighbors
Support Vector Machine

training model with SMOTE technique

Cross-Validation
valuated model stability using 5-fold cross-validation
Focused on recall as the scoring metric

Chosen Model: Random Forest
Highest recall and F1-score
Strong cross-validation recall (84.6%)
Suited for Best balance of performance for providing business value and fulfilling objective
no knn and decision tree as knn is unstable and it will not provide good result in real world data while decision tree model shown overfitting
