# Task 3 — Linear Regression (Simple & Multiple)
This task demonstrates how to implement simple and multiple linear regression using Python. The objective is to understand how regression models work, how to train them, evaluate them, and visualize the results.

# Objective

To apply Simple Linear Regression using one independent variable.

To apply Multiple Linear Regression using multiple independent variables.

To evaluate models using MAE, MSE, and R² score.

To visualize the regression line and interpret results.

# Tools & Libraries Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

# Dataset

The task uses the Housing.csv dataset which contains:

Price

Area

Bedrooms

Bathrooms

Stories

Parking

Furnishing status

Other categorical features
# Steps Performed
## 1. Import Libraries & Load Dataset

Read the CSV file using Pandas.

Display dataset and columns.

## 2. Simple Linear Regression

Feature: Area

Target: Price

Split dataset (80% training, 20% testing)

Train a LinearRegression model

Predict on test data

Evaluate using:

MAE

MSE

R² Score

Plot regression line

## 3. Multiple Linear Regression

Features used: Area, Bedrooms, Bathrooms, Stories, Parking

Same steps repeated:

Train model

Predict

Evaluate

# Evaluation Metrics Used
Metric	      Description
MAE        	 Average absolute error
MSE	         Average squared error
R² Score	   Accuracy of regression model

# Visualization

Scatter plot of test data

Regression line for simple linear regression

# Dependencies Installation
pip install pandas numpy scikit-learn matplotlib

# How to Run the Code
python linear_regression_task3.py

(or run cell-by-cell in Jupyter)

# Output

Trained regression model

Evaluation metrics

Graphs

Regression coefficients
