🚗 Car Purchasing Prediction using Machine Learning

This project predicts the car purchase amount of customers based on their demographic and financial details using Machine Learning and Deep Learning models.

📌 Project Overview

Companies in the automobile sector rely on customer insights to target buyers effectively. By analyzing customer data such as income, age, gender, and debt, we can build a predictive model that estimates how much a customer is likely to spend on purchasing a car.

This project uses Python, Pandas, Scikit-learn, TensorFlow/Keras, and Matplotlib for data analysis, preprocessing, visualization, and model building.

📂 Dataset

File Name: Car_Purchasing_Data.csv

Features:

Customer Name

Customer e-mail

Country

Gender

Age

Annual Salary

Credit Card Debt

Net Worth

Car Purchase Amount (Target variable)

⚙️ Tech Stack

Programming Language: Python

Libraries:

Pandas, Numpy → Data preprocessing

Matplotlib, Seaborn → Visualization

Scikit-learn → ML models, metrics

TensorFlow/Keras → Deep Learning models

🧑‍💻 Implementation Steps

Data Loading & Exploration

Read dataset, check for null values, distributions, and correlations.

Data Preprocessing

Handle categorical data (Gender, Country) using encoding.

Normalize numerical features.

Train-test split.

Model Building

Linear Regression (baseline model)

Deep Learning (Keras Sequential Model with Dense layers)

Evaluation Metrics

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

📊 Results

Linear Regression: Baseline prediction with moderate accuracy.

Deep Learning: Improved performance with multiple dense layers and activation functions.

Note: Current model struggles with overfitting → needs tuning.
