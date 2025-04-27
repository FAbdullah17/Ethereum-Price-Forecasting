# 📈 Ethereum Price Forecasting with ARIMA

Welcome to the Ethereum Price Forecasting project! This project aims to forecast future Ethereum (ETH/USD) prices using advanced time series analysis, particularly the ARIMA model with auto-tuned parameters.

## 📚 Project Overview

* **Objective:** Forecast Ethereum (ETH/USD) prices for the next 30 days based on historical data.
* **Techniques Used:**
  * Data Collection via yfinance
  * Exploratory Data Analysis (EDA)
  * Stationarity Testing (ADF Test)
  * ACF and PACF Analysis
  * ARIMA Modeling with auto_arima
  * 30-day Price Forecasting
  * Model Evaluation using RMSE and MAPE


## 🔥 How the Project Works

1. Downloaded Ethereum (ETH-USD) data from Yahoo Finance (2016–2025).
2. Performed EDA to understand trends, volatility, and price behaviors.
3. Applied ADF test and differencing to ensure stationarity.
4. Used auto_arima to automatically select the best ARIMA parameters.
5. Forecasted prices for the next 30 days with confidence intervals.
6. Evaluated predictions with RMSE and MAPE for accuracy.

## 📊 Key Results

* **Best Model:** ARIMA(1,1,0)
* **Forecast Horizon:** 30 days
* **Evaluation Metrics:**
  * RMSE ≈ 260
  * MAPE ≈ 6.6%

## 📄 Full Project Report

👉 [Click here to view the Full Project Report (PDF)](CA-M1-Arch-.pdf)

The report includes:
* Introduction
* Data Collection and Preparation
* EDA Visualizations
* Stationarity Testing Results
* Model Building Details
* Forecast Graphs
* Evaluation Metrics
* Insights and Learnings
* References



## 🧠 Future Work

* Implement SARIMA to capture any seasonal patterns.
* Try deep learning models like LSTM for nonlinear price behavior.
* Create an interactive dashboard using Plotly Dash or Streamlit.