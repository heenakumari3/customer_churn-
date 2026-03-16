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

# Customer demographics
# Services subscribed
# Account information
# Monthly charges
# Total charges
# Contract type
# Payment method
# Churn status

## Target variable:

## Churn

# Yes → Customer left the company
# No → Customer retained

## Project Workflow
1. Data Collection
2. 
The dataset was obtained from Kaggle and contains telecom customer records.

3. Data Cleaning

# Handled missing values
# Converted data types
# Removed unnecessary columns
# Encoded categorical variables

3. Exploratory Data Analysis (EDA)

EDA was performed to understand patterns in the data such as:

# Customer distribution
# Contract type vs churn
# Monthly charges vs churn
# Payment methods and churn behavior

4. Feature Engineering

Categorical variables were converted into numerical form using encoding techniques to prepare the data for machine learning models.

5. Model Building

Machine learning models were trained to predict customer churn.

models used:

# Random Forest

6. Model Evaluation

Models were evaluated using metrics such as:

# Accuracy
# Precision
# Recall
# Confusion Matrix


## Technologies Used

# Python
# Jupyter Notebook
# Pandas
# NumPy
# Scikit-learn


customer_churn
│
├── README.md
├── telco_customer_churn.ipynb
└── telco_customer_churn.csv
