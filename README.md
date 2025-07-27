# Projects

# Multiple Linear Regression on Ecommerce Customers Dataset

## Project Overview
This project demonstrates the application of multiple linear regression to analyze the relationship between customer behavior metrics (e.g., time spent on the website/app, session length, membership duration) and their yearly spending on an e-commerce platform. The goal is to build a predictive model to estimate yearly spending based on customer behavior.

Dataset Description
📊 E-commerce Customer Data (Source: [Kaggle](https://www.kaggle.com/datasets/kolawale/focusing-on-mobile-app-or-website))

Key Features
Rows: 500 | Columns: 8

Target Variable: Yearly Amount Spent (Continuous, float64)

Predictors:

Avg. Session Length (float64)

Time on App (float64)

Time on Website (float64)

Length of Membership (float64)

Non-Numeric Columns:

Email (object)

Address (object)

Avatar (object)

Data Quality
✔ No missing values (Confirmed via df.info())
✔ All numeric predictors are float64 (suitable for regression).

## Steps Performed
1. **Data Loading and Exploration**: Loaded the dataset and performed initial exploration to understand its structure.
2. **Exploratory Data Analysis (EDA)**: Visualized relationships between variables using joint plots and other visualizations.
3. **Data Preprocessing**: Split the data into training and testing sets.
4. **Model Training**: Trained a Linear Regression model on the training data.
5. **Model Evaluation**: Evaluated the model using metrics like RMSE and MAE.
6. **Insights**: Derived insights from the model coefficients to understand feature importance.

## Dependencies
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

