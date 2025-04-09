# Air Quality Index (AQI) Prediction Project

## Overview

This project focuses on predicting the Air Quality Index (AQI) based on a dataset containing air pollutant concentrations and meteorological factors. The analysis explores the relationships between these features and the AQI using two different machine learning models: Linear Regression and Decision Tree Regression. The goal is to understand the key drivers of AQI and build a predictive model.

## Project Structure

The repository contains the following files:

* `data/`: This directory contains the AQI dataset used for the project (e.g., `aqi_data.csv`).
* `notebooks/`: This directory contains the Jupyter Notebook (`aqi_prediction.ipynb`) with the code for data exploration, model building, training, evaluation, and analysis.
* `README.md`: This file (the current one) provides an overview of the project.
* `requirements.txt`: Lists the Python libraries required to run the code.

## Code Description

The Jupyter Notebook (`aqi_prediction.ipynb`) includes the following steps:

1.  **Data Loading and Exploration:**
    * Loading the AQI dataset.
    * Initial exploration of the data (e.g., descriptive statistics, data visualization).
    * Handling missing values (if any).
    * Feature selection and engineering (if applicable).

2.  **Data Preprocessing:**
    * Splitting the data into training and testing sets.
    * Scaling or encoding features as needed for the models.

3.  **Model Building and Training:**
    * **Linear Regression:** Training a linear regression model on the training data.
    * **Decision Tree Regression:** Training a decision tree regression model on the training data.

4.  **Model Evaluation:**
    * Evaluating the performance of both models on the test set using relevant regression metrics (e.g., MAE, MSE, RMSE, R-squared).
    * Visualizing the predictions and residuals for both models.

5.  **Model Analysis and Interpretation:**
    * **Feature Importance:** Extracting and visualizing feature importance from the Decision Tree model.
    * **Hyperparameter Tuning (Decision Tree):** Performing hyperparameter tuning (e.g., using GridSearchCV) to optimize the Decision Tree's performance.
    * **Residual Analysis:** Examining the distribution of residuals for the Decision Tree model to understand the error patterns.
    * **Comparison of Models:** Comparing the performance and characteristics of the Linear Regression and Decision Tree models.

6.  **Recommendations:**
    * Providing recommendations based on the findings, such as areas for further research or key features for monitoring.

## Requirements

To run the code in the `notebooks/aqi_prediction.ipynb` file, you will need to have Python and the following libraries installed. You can install these using pip:

```bash
pip install -r requirements.txt
