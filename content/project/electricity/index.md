---
title: Electricity Forecasting System
date: 2025-02-20
tags:
  - Python
  - Forecasting
  - Time Series
  - LSTM
  - SARIMAX
  - Energy
---

Built a multi-time series forecasting system to predict daily electricity usage for 370 clients using 15-minute interval data.

- Cleaned and preprocessed raw data, handled daylight saving time gaps/overlaps, and converted kW to kWh.  
- Engineered lag and rolling features (7d/14d), cyclical time variables, cluster labels, and merged daily weather data as exogenous inputs.  
- Used DTW-based clustering to group users by usage behavior and added cluster labels to improve prediction.  
- Trained and compared SARIMAX, LSTM, and HistGradientBoostingRegressor using recursive multi-step forecasting.  
- Final model achieved MAE: 655.66, RMSE: 779.34, and MAPE: 30.2%.

<!--more-->

