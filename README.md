# Online Food Delivery Prediciton

## Overview
This README is for the IE0005 mini project, which involves the analysis of a food delivery dataset. The original dataset can be found on Kaggle at [Food Delivery Dataset](https://www.kaggle.com/datasets/gauravmalik26/food-delivery-dataset?select=train.csv).

## Problem Motivation
- The food delivery time prediction model plays a crucial role in the food delivery industry, where prompt and accurate delivery is of utmost importance. Delivery time directly impacts customer satisfaction and influences their overall experience.

## Problem Definition
- Can we predict the estimated time of delivery based on the delivery rider's attributes?

## Walk-Through

1. Data Preparation and Cleaning

- Outliers (Age/Ratings/Latitude/Longitude)
- Empty/NaN/Null Data
- Column Names were all renamed to Camel Case

2. Exploratory Data Analysis, Data-Driven Insights & Recommendations

- Distribution/Correlation of Numeric Columns
- Plotting of orders geographically with a heatmap
- Using a line chart to observe the average delivery time throughout the day.
- Feature Engineering - Distance

3. Machine Learning Techniques to solve the problem
- Predicting Time Taken
- Linear Regression (For numerical data only)
- One-Hot Encoding (for non ordinal data) & Label encoding (for ordinal data)
- Decision Trees
- Random Forest
- Lasso Regression
- XGBoost
- Model Evaluation (R^2 and MSE Score)

## Conclusion
- The XGBoost model we implemented to estimate delivery time has a 83% accuracy.


