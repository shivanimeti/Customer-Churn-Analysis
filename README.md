# Customer Churn Analysis and Prediction

![Python](https://img.shields.io/badge/Python-Data%20Science-blue)
![SQL](https://img.shields.io/badge/SQL-Data%20Analysis-orange)
![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![MachineLearning](https://img.shields.io/badge/Machine%20Learning-Prediction-green)

## Project Overview

Customer churn prediction is crucial for businesses to retain customers and improve revenue.
This project analyzes customer data to identify churn patterns and builds a machine learning model that predicts whether a customer will leave the service.

The project demonstrates a **complete data analytics workflow** including SQL analysis, machine learning prediction, and dashboard visualization.

---

## Project Workflow

Data Collection → Data Analysis (SQL) → Data Processing → Machine Learning Model → Visualization → Dashboard

---

## Project Structure

Customer-Churn-Analysis
│
├── data
│   └── churn_data.csv

├── sql_queries
│   └── churn_analysis.sql

├── python_model
│   └── churn_prediction.py

├── visualizations
│   └── churn_prediction_plots.png

├── powerbi_dashboard
│   └── churn_dashboard.pbix

├── images
│   └── dashboard.png

└── README.md

---

## Dataset

The dataset includes customer demographics, service usage, and billing information.

Key features:

* Gender
* Contract type
* Monthly charges
* Total revenue
* Customer status
* State

Target variable:

Customer_Status (Churn / Active)

---

## SQL Data Analysis

SQL queries were used to perform exploratory analysis.

Key analyses include:

* Gender distribution
* Contract type distribution
* Customer churn status
* Revenue analysis
* State-wise customer distribution

Example SQL query:

SELECT Customer_Status, COUNT(*) AS TotalCustomers
FROM stg_Churn
GROUP BY Customer_Status;

---

## Machine Learning Model

A machine learning model was built using Python to predict customer churn.

Steps:

1 Data preprocessing
2 Feature encoding
3 Train-test split
4 Model training
5 Model evaluation

Libraries used:

* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn

Example model used:

Random Forest Classifier

Example evaluation metric:

Accuracy: 84%

---

## Visualizations

Data visualizations help understand churn patterns.

Examples:

* Customer churn distribution
* Contract type comparison
* Revenue impact analysis
* Feature importance

---

## Power BI Dashboard

An interactive dashboard was built to explore churn insights.

Dashboard features:

* Customer overview
* Contract type analysis
* Revenue insights
* State-wise customer distribution

Dashboard preview:

![Dashboard](images/dashboard.png)

---

## Key Insights

* Month-to-month contract customers have the highest churn rate.
* Customers with higher monthly charges are more likely to churn.
* Long-term contract customers show strong retention.
* Certain geographic regions show higher churn probability.

---

## Tools and Technologies

SQL
Python
Power BI
pandas
scikit-learn
matplotlib
seaborn

---

## How to Run the Project

1 Clone the repository

git clone https://github.com/yourusername/Customer-Churn-Analysis

2 Install required libraries

pip install -r requirements.txt

3 Run the prediction script

python churn_prediction.py

4 Open the Power BI dashboard file to explore insights

---

## Author

Shivani Meti
Electronics and Communication Engineering
Data Analytics and Machine Learning Enthusiast
