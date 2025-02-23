Customer Churn & Salary Prediction using Deep Learning

Overview

This project aims to predict customer churn and employee salary using Deep Learning Artificial Neural Network (ANN) models. The churn model takes several customer attributes as input and predicts the likelihood of churn, helping businesses improve customer retention strategies. The salary prediction model estimates employee salaries based on relevant features.

Features Used

Customer Churn Prediction

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

Salary Prediction

The following attributes are used for salary prediction:

Geography (One-Hot Encoded)
Gender (Label Encoded)
Age (Continuous)
Balance (Continuous)
Credit Score (Continuous)
Exited (Binary)
Tenure (Discrete)
Number of Products (Discrete)
Has Credit Card (Binary)
Is Active Member (Binary)

Project Structure

Create a virtual environment and install dependencies:

python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
pip install -r requirements.txt

Data Preprocessing

Encoding categorical features (Geography, Gender)

Normalizing numerical features

Handling missing values (if any)

Splitting dataset into training and test sets

Model Architecture

The ANN models consist of:

Input layer corresponding to the feature set

Hidden layers with ReLU activation

Output layer:

For Churn Prediction: Sigmoid activation for binary classification

For Salary Prediction: Linear activation for continuous regression

Training

Models are trained using deep ANN models

Model performance is evaluated using:

Churn Prediction: Accuracy

Salary Prediction: Mean Squared Error (MSE), Mean Absolute Error (MAE)

Deployment

The trained models are deployed using a Streamlit web application. To run the app:

streamlit run app.py

Usage

Enter customer or employee details via the Streamlit UI.

Click "Predict" to see the churn probability or salary estimation.

Interpret results to take necessary business actions.

Conclusion

This project enables businesses to anticipate customer churn and estimate employee salaries accurately. Future improvements include hyperparameter tuning, feature engineering, and the integration of additional factors for better predictions.