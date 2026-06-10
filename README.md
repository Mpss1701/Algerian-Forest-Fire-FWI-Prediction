
## Overview

This project aims to predict the **Fire Weather Index (FWI)** using the Algerian Forest Fires dataset. The workflow includes data preprocessing, exploratory data analysis (EDA), feature selection, model training, hyperparameter tuning, and performance evaluation using multiple regression techniques.

## Problem Statement

The Fire Weather Index (FWI) is an important indicator used to assess the risk and intensity of forest fires. Accurate prediction of FWI can help authorities and environmental agencies make informed decisions regarding wildfire prevention and management.

## Dataset

The project uses the Algerian Forest Fires dataset, which contains meteorological and fire-related observations collected from different regions of Algeria.

### Features

* Temperature
* Relative Humidity (RH)
* Wind Speed (Ws)
* Rain
* FFMC
* DMC
* DC
* ISI
* BUI
* Classes
* Region

### Target Variable

* Fire Weather Index (FWI)

## Project Workflow

### 1. Data Preprocessing

* Handling missing values
* Data cleaning
* Encoding categorical variables
* Feature scaling

### 2. Exploratory Data Analysis (EDA)

* Distribution analysis
* Correlation analysis
* Outlier detection
* Feature relationship visualization

### 3. Feature Selection

* Correlation-based feature analysis
* Removal of redundant features
* Multicollinearity assessment

### 4. Model Building

The following regression models were implemented and compared:

* Linear Regression
* Ridge Regression
* Lasso Regression
* Elastic Net Regression

### 5. Hyperparameter Tuning

* Cross-validation using Scikit-Learn
* Optimal alpha selection for regularized models

### 6. Model Evaluation

Performance was evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook / Google Colab



## Key Learnings

* Regression modeling and evaluation
* Regularization techniques (Ridge, Lasso, Elastic Net)
* Feature selection and multicollinearity handling
* Hyperparameter tuning using cross-validation
* End-to-end machine learning workflow

## Future Improvements

* Deploy the model using Flask or Streamlit
* Experiment with ensemble-based regression models
* Automate the machine learning pipeline
* Add model monitoring and performance tracking

## Author

Mahish Pratap Singh

If you found this project useful, feel free to star the repository.
