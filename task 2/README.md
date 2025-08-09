📊 Customer Churn Prediction
CODSOFT Internship – Task 2

📌 Project Overview
This project aims to predict whether a customer will churn (leave a service) based on demographic, account, and usage data.
Customer churn prediction is crucial for businesses to identify at-risk customers and take preventive action to improve retention.

We use the Telco Customer Churn Dataset and train a Random Forest Classifier to model the relationship between customer attributes and churn behavior.

📂 Dataset
Source: Telco Customer Churn – Kaggle

Dataset Columns:

customerID – Unique customer identifier

gender, SeniorCitizen, Partner, Dependents – Demographic details

tenure, PhoneService, InternetService, Contract – Service details

MonthlyCharges, TotalCharges – Payment info

Churn – Target variable (Yes/No)

🛠️ Technologies Used
Python

Pandas, NumPy – Data manipulation

Scikit-learn – Machine learning & evaluation

Matplotlib – Visualization

🚀 Steps Followed
Data Loading & Exploration

Read CSV file, check dataset shape & missing values.

Data Preprocessing

Convert TotalCharges to numeric and handle missing values.

Encode categorical variables using Label Encoding.

Scale numerical features with StandardScaler.

Model Training

Train a Random Forest Classifier with default parameters.

Evaluation

Accuracy score

Precision, Recall, and F1-score

Confusion Matrix

Feature Importance plot

Custom Predictions

Predict churn for sample customer data.

📊 Results
Accuracy: ~79.8%

Class 0 (No Churn): High recall (0.91) → correctly identifies most non-churn customers.

Class 1 (Churn): Lower recall (0.48) → could be improved with balancing techniques.

Most important features: TotalCharges, MonthlyCharges, tenure, Contract.

📈 Future Improvements
Use class_weight='balanced' in Random Forest to handle imbalance.

Apply oversampling (SMOTE) to improve churn recall.

Try Gradient Boosting models like XGBoost or LightGBM.

Feature engineering (interaction features, tenure grouping).
