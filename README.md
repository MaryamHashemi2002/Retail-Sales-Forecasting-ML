# RetailPulse — Retail Sales Forecasting API

An end-to-end machine learning project focused on predicting daily retail store sales using historical data, store characteristics, promotional activities, and temporal patterns.

## Overview

Accurately forecasting sales is an important challenge in the retail industry. Reliable sales predictions can help businesses make better decisions regarding inventory management, resource allocation, promotional planning, and overall store operations.

RetailPulse aims to address this problem by developing a machine learning solution that estimates daily sales across multiple retail stores based on historical sales records and relevant business information.

The project uses the Rossmann Store Sales dataset, which provides historical sales information alongside store-specific attributes, promotional activities, and calendar-related features.

The objective is to build a complete machine learning workflow, starting with data exploration and preprocessing, followed by feature engineering, model development, and performance evaluation. The final model will be integrated into a REST API using FastAPI, allowing users to submit store and date-related information and receive sales predictions.

## Project Objectives

- Explore and understand historical retail sales patterns.
- Perform data cleaning and handle missing values.
- Identify meaningful relationships between sales, promotions, holidays, and store characteristics.
- Develop relevant temporal and business-related features.
- Train and compare different machine learning regression models.
- Evaluate model performance using appropriate regression metrics.
- Build a REST API using FastAPI to serve sales predictions.
- Develop a modular and reproducible machine learning pipeline.

## Dataset

This project uses the Rossmann Store Sales dataset.

The dataset includes information such as:

- Historical daily sales records.
- Store characteristics, including store type and assortment.
- Distance to the nearest competitor.
- Promotional activities and campaign information.
- Public holidays and school holidays.
- Date-related information.

The primary prediction target is `Sales`, representing the daily sales of a retail store.

## Methodology

The project follows a structured machine learning workflow:

1. **Exploratory Data Analysis (EDA):** Investigating sales distributions, temporal patterns, missing values, and relationships between variables.
2. **Data Preprocessing:** Cleaning the data, handling missing values, merging datasets, and preparing features.
3. **Feature Engineering:** Extracting date-related information and creating meaningful business features.
4. **Model Development:** Training and comparing regression algorithms.
5. **Model Evaluation:** Assessing predictive performance using MAE, RMSE, and R².
6. **API Development:** Integrating the selected model into a FastAPI application.
7. **Testing and Deployment:** Testing prediction endpoints and preparing the application for deployment.

## Technology Stack

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Development Environment:** Jupyter Notebook, VS Code
- **API Framework:** FastAPI
- **Version Control:** Git, GitHub

## Project Structure

```text
retail-pulse/
├── data/
├── notebooks/
├── src/
├── app/
├── models/
├── tests/
├── requirements.txt
├── .gitignore
└── README.md
```

## Project Status

Currently in development.

The initial focus is on exploratory data analysis, data preprocessing, and feature engineering. Model development and API implementation will follow.

## Future Improvements

- Experiment with advanced gradient boosting algorithms.
- Perform hyperparameter optimization.
- Analyze feature importance and prediction errors.
- Improve API validation and testing.
- Containerize the application using Docker.
- Deploy the prediction API.

## Author

Developed as a personal machine learning engineering project.