# Vehicle Price Prediction and Feature Selection Using Multiple Linear Regression

## Overview

This project explores multiple linear regression techniques to predict used vehicle prices using the Toyota Corolla dataset. The analysis focuses on building predictive models, evaluating model performance, selecting significant features, and comparing regularized regression approaches.

The project demonstrates the complete predictive analytics workflow, including data preparation, model development, feature selection, validation, and statistical interpretation.

## Objective

Develop a predictive model capable of estimating vehicle sale prices based on vehicle characteristics such as age, mileage, horsepower, fuel type, weight, and tax information.

## Tools and Technologies

* Python
* Pandas
* Scikit-Learn
* Statsmodels
* NumPy
* Matplotlib
* DMBA Package

## Techniques Applied

### Data Preparation

* Data cleaning and preprocessing
* One-hot encoding of categorical variables
* Training and validation dataset creation
* Feature engineering

### Predictive Modeling

* Multiple Linear Regression
* Ordinary Least Squares (OLS)

### Feature Selection

* Exhaustive Search
* Backward Elimination
* Forward Selection
* Stepwise Selection

### Regularization Methods

* Lasso Regression
* Ridge Regression
* Bayesian Ridge Regression

### Model Evaluation

* Adjusted R²
* AIC (Akaike Information Criterion)
* BIC (Bayesian Information Criterion)
* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)
* MAPE (Mean Absolute Percentage Error)
* Residual Analysis

## Key Findings

The linear regression model achieved strong predictive performance with an Adjusted R² of approximately 0.85, indicating that the selected features explained a significant portion of the variation in vehicle prices.

Feature selection methods consistently identified the following variables as the most influential predictors:

* Vehicle Age
* Mileage (KM)
* Horsepower
* Weight
* Fuel Type
* Quarterly Tax
* Transmission Type

Model comparison showed that the standard multiple linear regression model performed competitively against several regularized regression approaches.

## Skills Demonstrated

* Predictive Analytics
* Statistical Modeling
* Regression Analysis
* Feature Selection
* Machine Learning Fundamentals
* Data Visualization
* Model Validation
* Python Programming
* Business Data Analytics

## Dataset

Toyota Corolla vehicle sales dataset containing vehicle specifications and historical pricing information.

## Author

Kimberly Crews

Master of Science in Information Technology

Focus Areas: Data Analytics, Business Intelligence, Predictive Modeling, and Financial Systems Analysis
