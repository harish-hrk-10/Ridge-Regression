Ridge Regression – EV Car Price Prediction
📌 Project Overview

This project uses Ridge Regression to predict the prices of Electric Vehicles (EVs) in India based on their specifications.

The project applies machine learning techniques such as:

Data preprocessing
Feature scaling
One-hot encoding
Train-test splitting
Ridge Regression
Model evaluation using MAE, RMSE, and R² score
📂 Dataset

The project uses the following dataset:

ev_car_India_dataset.csv

The features considered for prediction are:

Numerical Features
Range
Power
Battery
Categorical Features
Brand
Model
Target Variable
Price
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Google Colab / Jupyter Notebook
🔄 Project Workflow
Import the necessary Python libraries.
Load the EV dataset.
Explore the dataset and check for missing values.
Separate the features (X) and target variable (y).
Identify the numerical and categorical features.
Apply:
StandardScaler to numerical features
OneHotEncoder to categorical features
Divide the dataset into training and testing sets.
Train the Ridge Regression model using different alpha values:
0.01
0.1
1
10
100
Generate predictions using the trained model.
Evaluate the model using:
MAE
RMSE
R² Score
📊 Model Evaluation

The model is evaluated using both the training and testing datasets.

Evaluation Metrics

MAE (Mean Absolute Error)
Measures the average absolute difference between the actual and predicted prices.

RMSE (Root Mean Squared Error)
Measures the prediction error while giving greater importance to larger errors.

R² Score
Shows how well the model explains the variation in EV prices.

🚀 How to Run in Google Colab
Open the notebook in Google Colab.
Upload ev_car_India_dataset.csv to the Colab environment.
Run the notebook cells in sequence.
View the final Ridge Regression results and evaluation metrics.
🎯 Objective

The main objective of this project is to demonstrate how Ridge Regression can be used to predict EV prices based on vehicle specifications and categorical information.

👩‍💻 Project Type

Machine Learning – Regression

Algorithm: Ridge Regression

Dataset: Indian Electric Vehicle Dataset
