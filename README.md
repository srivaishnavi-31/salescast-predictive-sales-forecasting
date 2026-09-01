# salescast-predictive-sales-forecasting
Predictive sales forecasting using historical sales data with Python, Random Forest and Power BI.
# SALESCAST – Predictive Sales Forecasting

## Project Overview

SALESCAST is a predictive analytics project designed to analyze historical sales data and forecast future sales trends.

The project combines Python-based predictive modeling with Power BI dashboard development to provide both analytical insights and future sales forecasts.

## Problem Statement

Build a predictive model to forecast future sales trends using historical sales data.

### Key Objectives

- Clean and preprocess historical sales data
- Perform exploratory data analysis
- Engineer time-based and lag features
- Build predictive models
- Compare model performance
- Forecast future sales
- Visualize historical and predicted sales using Power BI

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Power BI

## Machine Learning Models

Two models were evaluated:

1. Improved Linear Regression
2. Random Forest Regression

## Model Performance

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Improved Linear Regression | 1.48M | 1.85M | -0.1657 |
| Random Forest | 1.29M | 1.74M | -0.0357 |

Random Forest performed better than Improved Linear Regression based on MAE, RMSE and R².

However, the negative R² indicates that the model has limited predictive strength and could be improved with additional historical data and feature engineering.

## Power BI Dashboard

### Page 1 – Sales Analytics

![Sales Analytics Dashboard](images/page1_dashboard.png)

### Page 2 – Predictive Forecasting

![Predictive Forecasting Dashboard](images/page2_forecasting.png)

## Key Features

- Historical sales trend analysis
- Category-wise sales analysis
- Regional sales performance
- Customer segment analysis
- Actual vs predicted sales comparison
- 12-month sales forecasting
- Model performance metrics

## Project Structure

salescast-predictive-sales-forecasting/

├── data/

├── notebooks/

├── powerbi/

├── images/

├── requirements.txt

└── README.md

## Conclusion

The project demonstrates how historical sales data can be transformed into predictive insights using machine learning and Power BI.

The Random Forest model provided better performance than the Linear Regression model, while the Power BI dashboard presents historical trends, model predictions and future sales forecasts in an interactive format.
