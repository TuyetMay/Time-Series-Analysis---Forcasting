# Time-Series-Analysis---Forcasting
# Time-Series Analysis about Temperature

This project focuses on the analysis and forecasting of temperature time-series data. We investigate the stationarity of the data and evaluate the performance of various forecasting models.

## Project Goals

* To analyze the characteristics of the temperature time-series data.
* To assess the stationarity of the temperature data using the Augmented Dickey-Fuller (ADF) test.
* To build and compare the performance of Prophet, ARIMA, Decision Tree, Random Forest, and LightGBM models for temperature forecasting.
* To identify the most suitable model for predicting future temperature values.

## Methodology

The project involves the following steps:

1.  **Data Loading and Exploration:** Loading the temperature time-series data and performing initial exploratory data analysis (EDA) to understand its patterns and characteristics (e.g., trends, seasonality).
2.  **Stationarity Testing:** Applying the Augmented Dickey-Fuller (ADF) test to check if the temperature time series is stationary. If the data is non-stationary, appropriate differencing or other transformations will be applied.
3.  **Model Implementation and Training:**
    * Implementing and training the following time-series forecasting models:
        * Prophet
        * ARIMA (Autoregressive Integrated Moving Average)
        * Decision Tree
        * Random Forest
        * LightGBM
    * For tree-based models (Decision Tree, Random Forest, LightGBM), time-based features (e.g., day of the week, month, year, lag features) will be engineered.
4.  **Model Evaluation:** Evaluating the performance of each model using appropriate time-series forecasting metrics (e.g., Mean Squared Error - MSE, Root Mean Squared Error - RMSE, Mean Absolute Error - MAE).
5.  **Comparison and Analysis:** Comparing the forecasting accuracy of the different models and identifying the model that provides the best predictions for the temperature data.

