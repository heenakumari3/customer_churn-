## Customer Churn Prediction
## Project Overview

Customer churn prediction is the process of identifying customers who are likely to stop using a company's service. In this project, machine learning techniques are used to analyze customer data and predict whether a customer will leave the company or stay.
The goal of this project is to help businesses identify at-risk customers and take proactive actions to improve customer retention.

## Problem Statement

Customer retention is one of the most important challenges for telecom companies. Acquiring new customers is more expensive than retaining existing ones.
This project predicts whether a customer will churn (leave the company) based on various customer attributes such as demographics, services subscribed, and billing information.

## Dataset
Dataset used: Telco Customer Churn Dataset
The dataset contains information about telecom customers including:

1.Customer demographics
2.Services subscribed
3.Account information
4.Monthly charges
5.Total charges
6.Contract type
7.Payment method
8.Churn status

## Target variable:

Churn

1.Yes → Customer left the company
2.No → Customer retained

## Project Workflow
1. Data Collection

The dataset was obtained from Kaggle and contains telecom customer records.

3. Data Cleaning

1.Handled missing values
2.Converted data types
3.Removed unnecessary columns
4.Encoded categorical variables

3. Exploratory Data Analysis (EDA)

EDA was performed to understand patterns in the data such as:

1.Customer distribution
2.Contract type vs churn
3.Monthly charges vs churn
4.Payment methods and churn behavior

4. Feature Engineering

Categorical variables were converted into numerical form using encoding techniques to prepare the data for machine learning models.

5. Model Building

Machine learning models were trained to predict customer churn.

models used:

*Random Forest

6. Model Evaluation

Models were evaluated using metrics such as:

1.Accuracy
2.Precision
3.Recall
4.Confusion Matrix


7. Technologies Used

1.Python
2.Jupyter Notebook
3.Pandas
4.NumPy
5.Scikit-learn


customer_churn
│
├── README.md
├── telco_customer_churn.ipynb
└── telco_customer_churn.csv
