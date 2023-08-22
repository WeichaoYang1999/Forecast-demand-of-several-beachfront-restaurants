# Forecast-demand-of-several-beachfront-restaurants
# Beach Demand Forecasting

This repository contains notebooks and code for forecasting beach demand using various techniques. The project aims to predict demand by removing seasonality, providing better accuracy than naive predictions.

## Notebooks

### 1. [Naive Forecasting](beach-demand-naive-forecast.ipynb)

This notebook includes a naive approach to forecasting beach demand. It includes:

- Data loading and preprocessing
- Visualization of raw sales by date
- Detrending of sales data

### 2. [XGBoost Forecasting](xgboost.ipynb)

This notebook contains code for using XGBoost to forecast beach demand. It includes:

- Data loading and preprocessing
- Date and weekday calculations
- Sorting person data

### 3. [Seasonal Analysis](beach-seasonal.ipynb)

This notebook provides a seasonal analysis of beach demand. It includes:

- Predicting demand by removing seasonality
- Line graph of all sales over a 3-year timespan
- Detrending analysis

## Data

The data used in these notebooks includes information about sales, items, restaurants, and people.

## Requirements

- Pandas
- NumPy
- Matplotlib
- Plotly

## Usage

To run the notebooks, you can clone the repository and open the notebooks in Jupyter Notebook or Google Colab.
