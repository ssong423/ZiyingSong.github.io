---
title: Online Retail Sales Forecasting
date: 2025-03-10
external_link: https://github.com/yourusername/retail-forecasting-project
tags:
  - Python
  - Forecasting
  - Time Series
  - XGBoost
  - NLP
---

Forecasted weekly product-level sales using over 1 million online transaction records.

- Forecasting weekly product-level sales using online retail transaction data from over 1 million records.
- Cleaned and preprocessed the dataset by removing canceled orders, duplicates, and products with short shelf life; created new features like sales, seasonality flags, and cluster labels.
- Used GPT API to clean product descriptions, generated embeddings (TF-IDF, BERT), and applied dimensionality reduction (PCA, t-SNE) for K-Means clustering.
- Built forecasting models (SARIMAX, Prophet, XGBoost) using rolling window splits with cluster-level predictions and disaggregated results to 45 individual products.
- Engineered lag features, rolling stats, price momentum, top-k sales signals, and categorical encodings; XGBoost achieved the best MAPE at the product level across 26 rolling windows.

<!--more-->
