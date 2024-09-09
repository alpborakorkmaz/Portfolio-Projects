# Netflix Subscriptions Forecasting using Python

## Overview
This project demonstrates how to forecast the number of Netflix subscriptions using time series forecasting techniques in Python. The goal is to predict future subscription counts to aid in business planning and strategy formulation.

## Project Workflow

### Data Collection
- Historical data on Netflix subscriptions from 2013 to 2023 is collected in a CSV file.

### Data Preprocessing
- The `Time Period` column is converted to a datetime format for better analysis.
- Quarterly and yearly growth rates of subscriptions are computed and visualized.

### Exploratory Data Analysis
- Visualization of quarterly subscription growth and growth rates using Plotly.
- Analysis of the subscription growth rate trends over time.

### Time Series Forecasting
- ARIMA (AutoRegressive Integrated Moving Average) model is used for forecasting.
- The model is trained on historical subscription data to predict future subscriptions for the next five quarters.

### Results Visualization
- Forecasts are compared with the historical data to visualize future subscription trends.

## Key Features
- **Data Visualization:** Interactive graphs showing subscription growth and growth rates.
- **Time Series Analysis:** Implementation of ARIMA for forecasting future subscription counts.
- **Forecasting:** Predictions for the next five quarters based on historical trends.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Plotly
- Statsmodels
