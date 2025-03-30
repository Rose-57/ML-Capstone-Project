# ML-Capstone-Project
Customer Churn Prediction

Project Overview:
Customer churn prediction is crucial for businesses to retain customers and enhance customer satisfaction. The goal is to develop a machine learning model that predicts whether a customer will churn based on various attributes such as call usage, service plans, and customer demographics.

Objective:
To build a predictive model that identifies customers at risk of churning using machine learning techniques.

Data Description:
Source: https://data.world/bob-wakefield/call-center-data
Features: The dataset contains customer-related features, including:
total_day_minutes, total_eve_minutes, total_night_minutes: Call duration in different time segments.
total_day_charge, total_eve_charge, total_night_charge: Charges for calls.
international_plan, voice_mail_plan: Subscription details.
churn: Target variable (1 = Churn, 0 = No Churn).

Key Features
✅ Automated Data Preprocessing – Handles missing values, scales numerical data, and encodes categorical variables.
✅ Machine Learning Pipeline – Uses a Gradient Boosting Classifier for high-accuracy predictions.
✅ Model Persistence – Saves and loads trained models using Joblib for future use.
✅ Unseen Data Prediction – Allows real-time predictions on new customer data.
✅ Scalability & Future Improvements – Designed to integrate new features and improve accuracy over time.

Technologies Used

Python: Pandas, NumPy, Scikit-learn
Machine Learning: Gradient Boosting Classifier
Data Handling: StandardScaler, OneHotEncoder, SimpleImputer
Model Storage: Joblib


Project Workflow

1. Data Preprocessing

Handle missing values with mean/mode imputation.

Scale numerical data using StandardScaler.

Encode categorical variables with OneHotEncoder.


2. Model Training & Evaluation

Train a Gradient Boosting Classifier on preprocessed data.

Evaluate model performance using accuracy, precision, recall, and F1-score.


3. Unseen Data Prediction

Generate and preprocess unseen customer data.

Use the trained model to predict churn likelihood.


4. Model Deployment & Future Enhancements

Save and reload the trained model for real-time predictions.

Improve accuracy using deep learning models or resampling techniques.

Conclusion:

The Gradient Boosting Classifier successfully predicts customer churn, enabling proactive decision-making. However, model performance depends on data quality, class balance, and feature selection. Regular updates and advanced techniques can further enhance accuracy.
