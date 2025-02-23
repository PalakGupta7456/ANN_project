Customer Churn Prediction using Deep Learning

Overview

This project aims to predict customer churn using a Deep Learning Artificial Neural Network (ANN) model. The model takes several customer attributes as input and predicts the likelihood of churn, helping businesses improve customer retention strategies.

Features Used

The following customer attributes are used for prediction:

Geography (One-Hot Encoded)
Gender (Label Encoded)
Age (Continuous)
Balance (Continuous)
Credit Score (Continuous)
Estimated Salary (Continuous)
Tenure (Discrete)
Number of Products (Discrete)
Has Credit Card (Binary)
Is Active Member (Binary)

Data Preprocessing

Encoding categorical features (Geography and Gender)
Normalizing numerical features (Age, Balance, Credit Score, etc.)
Handling missing values (if any)
Splitting dataset into training and test sets
Model Architecture

The ANN model consists of:

Input layer corresponding to the feature set
Hidden layers with ReLU activation
Output layer with a sigmoid activation for binary classification

Training

The model is trained using ANN model and sigmoid activation function for binary classification.

Model performance is evaluated using accuracy and validation score.

Deployment

The trained model is deployed using a Streamlit web application. To run the app:

streamlit run app.py

Usage

Enter customer details via the Streamlit UI.

Click "Predict" to see the churn probability.

Interpret results to take necessary business actions.

Conclusion

This project enables businesses to anticipate customer churn and implement proactive retention strategies. Future improvements include hyperparameter tuning and feature engineering for enhanced accuracy.

Snapshot:
