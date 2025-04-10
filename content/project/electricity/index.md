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

<!-- 📄 [Download Project Report (PDF)](/static/uploads/electricity_report.pdf)  
📊 [Download Presentation Slides (PDF)](/static/uploads/electricity_slide.pdf) -->

📄 [Download Project Report (PDF)](https://ssong423.github.io/ZiyingSong.github.io/uploads/electricity_report.pdf)

📊 [Download Presentation Slides (PDF)](https://ssong423.github.io/ZiyingSong.github.io/uploads/electricity_slide.pdf)

- Built a scalable multi-time series forecasting model to predict daily electricity usage for 370 clients using 15-minute interval data.
- Handled daylight saving time gaps and overlap, converted units (kW → kWh), and cleaned datetime values for consistency.
- Engineered lag and rolling features (7d/14d), cyclical time variables, cluster labels, and merged daily weather data (avg temp) as exogenous inputs.  
- Used DTW-based clustering to group users by usage behavior and added cluster labels to improve prediction.  
- Used DTW-based clustering to group users by usage patterns and added cluster labels to models.
- Trained and compared SARIMAX, LSTM, and HistGradientBoostingRegressor; final model achieved MAE: 655.66, RMSE: 779.34, and MAPE: 30.2% using recursive multi-step forecasting.


<!--more-->

