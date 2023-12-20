# Singapore-Resale-Flat-Prices-Predicting


objective

The objective of this project is to develop a machine learning model and deploy it as a user-friendly web application that predicts the resale prices of flats in Singapore. This predictive model will be based on historical data of resale flat transactions, and it aims to assist both potential buyers and sellers in estimating the resale value of a flat

Scope:

Data Collection and Preprocessing: Collect a dataset of resale flat transactions from the Singapore Housing and Development Board (HDB) for the years 1990 to Till Date. Preprocess the data to clean and structure it for machine learning.


Feature Engineering: Extract relevant features from the dataset, including town, flat type, storey range, floor area, flat model, and lease commence date. Create any additional features that may enhance prediction accuracy.


Model Selection and Training: Choose an appropriate machine learning model for regression (e.g., linear regression, decision trees, or random forests). Train the model on the historical data, using a portion of the dataset for training.


Model Evaluation: Evaluate the model's predictive performance using regression metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), or Root Mean Squared Error (RMSE) and R2 Score.


Streamlit Web Application: Develop a user-friendly web application using Streamlit that allows users to input details of a flat (town, flat type, storey range, etc.). Utilize the trained machine learning model to predict the resale price based on user inputs.



The Modeling Process
The train dataset has all of the columns needed to generate and refine the models. The test dataset has all of those columns except for the target variable (resale price).

Generate regression model using the training data. This process consists of:

Data Cleaning
EDA
Data Visualization
Feature Engineering
Train-test split
Linear Regression
Lasso Regression
Ridge Regression

Refining Models
as a revisit to this project after the end of the Data Science Immersive course, I added in modelling with PyCaret to build a better model with higher R2 and lower RMSE
Predict the values for target column (resale price) in the test dataset

Use of train-test split, cross-validation, and unseen data
Evaluate models

Data used:
Data Source : https://beta.data.gov.sg/collections/189/view



