# BankCustomerChurnPrediction

Every bank wants to hold their customers for sustaining their business so the ABC Multinational bank. 

About Dataset:
This dataset is taken from Kaggle: https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset/data.
This dataset is for a Multistate bank with following columns:

column name, usage in the project
customer_id, unused variable.
credit_score, used as input.
country, used as input.
gender, used as input.
age, used as input.
tenure, used as input.
balance, used as input.
products_number, used as input.
credit_card, used as input.
active_member, used as input.
estimated_salary, used as input.
churn, used as the target. 1 if the client has left the bank during some period or 0 if he/she has not.

Aim of the project is to Predict the Customer Churn for the Bank using Machine Learning algorithms. Since this is a binary classification problem, I used Random Forest Classifier, Decision Tree Classifier, and Logistic Regression in the project. Random Forest Classifier has the better accuracy so that algorithm has been used to fit and evaluate the dataset. Next, an app was created using streamlit to have a front-end local website where the user can input the values and check the prediction.
