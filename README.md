# Sales Prediction using Python

A machine learning project that forecasts product sales based on advertising spend 
and other influencing features. The project combines regression modeling with time 
series forecasting to deliver both predictive accuracy and forward-looking insights.

## Overview

Understanding what drives sales is critical for any business making budget decisions. 
This project analyzes an advertising spend dataset containing TV, Radio, and Newspaper 
channels to determine which factors most influence sales, then builds models to predict 
future outcomes. It also includes an ARIMA-based time series forecast when date 
information is available.

## What This Project Does

- Loads any sales CSV dataset with automatic missing value handling
- Encodes categorical columns and performs forward-fill imputation
- Generates a feature correlation heatmap to identify key sales drivers
- Selects the top features based on correlation with the sales target
- Trains a Linear Regression model on an 80/20 train-test split
- Evaluates the model using RMSE and R-squared score
- Plots actual vs predicted sales for visual comparison
- Applies ARIMA time series forecasting to project the next 12 sales periods
- Analyzes the direct impact of advertising spend on sales
- Outputs actionable business insights based on model findings

## Key Insights

- TV advertising spend shows the strongest positive correlation with sales
- Radio has a moderate influence while Newspaper shows minimal impact
- The model can be used to simulate what-if scenarios by adjusting ad spend inputs
- Time series forecasting provides a 12-step forward projection for planning purposes

## Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- Scikit-learn (Linear Regression, StandardScaler, LabelEncoder)
- Statsmodels (ARIMA time series forecasting)
- Google Colab

## Dataset

The project works with any sales CSV containing a Sales column as the target variable. 
It was developed and tested on an advertising dataset with TV, Radio, and Newspaper 
spend columns mapped against product sales figures.

## Author

M. Talal Bin Waheed
