Retail Demand Forecasting using Random Forest

📌 Project Overview 

Retail businesses need accurate demand forecasts to manage inventory efficiently. Incorrect predictions can lead to stockouts or excess inventory.

This project builds a machine learning model using Random Forest Regression to predict retail product sales based on historical store data, promotions, transactions, and product categories.

The model helps retailers optimize inventory planning and understand key drivers of sales demand.

🎯 Project Objectives

Predict retail product sales using historical data

Identify key factors influencing demand

Perform exploratory data analysis (EDA) to understand sales patterns

Train and evaluate a machine learning model

Deploy a simple web application using Streamlit

📊 Dataset

Dataset used: Store Sales – Time Series Forecasting

Files used in this project:

train.csv – Historical sales data

stores.csv – Store information

transactions.csv – Customer transactions per store

holidays_events.csv – Holiday and event information

Target variable:

sales
⚙️ Technologies Used
Tool	Purpose
Python	Programming language
Pandas	Data preprocessing
NumPy	Numerical computations
Matplotlib / Seaborn	Data visualization
Scikit-learn	Machine learning
Random Forest	Prediction model
Streamlit	Web application deployment
GitHub	Project version control
📈 Exploratory Data Analysis (EDA)

Key analyses performed:

Sales distribution analysis

Sales trends over time

Promotion impact on sales

Store performance comparison

Customer transaction impact

Key Insights

Grocery products have the highest impact on sales

Customer transactions strongly correlate with sales

Promotions increase product demand

Seasonal and weekly patterns affect sales trends

🤖 Machine Learning Model

Algorithm used:

Random Forest Regressor

Why Random Forest?

Handles complex relationships in data

Robust against overfitting

Works well with mixed features

Model training pipeline:

Data Cleaning
↓
Feature Engineering
↓
EDA
↓
Train/Test Split
↓
Random Forest Model
↓
Model Evaluation

📊 Model Performance

Metric	Value

RMSE	347.84

R² Score	0.9048

The model explains ~90% of the variance in sales, indicating strong predictive performance.

🔍 Feature Importance

Top factors influencing sales prediction:

Grocery product category

Store transactions

Beverage product category

Promotions

Produce products

These insights highlight how product category and customer traffic strongly influence retail demand.

🚀 Deployment

A simple Streamlit web application was built to predict sales.

Users can input:

Transactions

Promotions

Month

Day of week

The model then outputs the predicted sales value.

Run locally:

streamlit run app.py

📁 Project Structure

Store_Sales_Project

│
├── app.py
├── sales_prediction_model.pkl
├── requirements.txt
├── notebooks
│   └── EDA_and_Model.ipynb
└── README.md
📌 Future Improvements

Use advanced forecasting models (XGBoost / LightGBM)

Add time-series features (lag variables, rolling averages)

Improve Streamlit UI

Deploy application on cloud platform

👩‍💻 Author

Shalini Guggilla

Aspiring Data Scientist passionate about solving real-world business problems using machine learning and data analytics.
