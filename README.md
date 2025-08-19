# TIme Series Analysis: Forecasting Total Order

## Overview
This project conducts an in-depth exploratory data analysis (EDA) and time series analysis of e-commerce sales data from 2019. The primary goal is to uncover temporal patterns, understand key business drivers, and build a solid foundation for developing accurate sales forecasting models. This analysis provides valuable insights for strategic decision-making in marketing and inventory management.

## Objectives
1.  **Data Exploration and Cleaning:** To load, inspect, and preprocess the dataset to ensure data quality and readiness for analysis.
2.  **Trend and Pattern Analysis:** To identify and analyze annual, monthly, and hourly patterns within the time series data.
3.  **Forecasting Model Development:** To build, evaluate, and compare various forecasting models to predict future sales.

## Tech Stack
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Time Series & Statistical Modeling:** statsmodels (Seasonal Decompose, ARIMA, Holt-Winters), Prophet
* **Machine Learning:** Scikit-learn, RandomForestRegressor

## Exploratory Data Analysis (EDA) & Key Findings

After data preparation and cleaning, a thorough EDA was performed to extract initial insights.

### 1. Annual Sales Trends (2019)
The analysis of sales data throughout 2019 revealed significant trends and seasonality.
* **Overall Performance:** The business generated a **Total Revenue of ~$34.4 million** from **~178k orders**, with a **Total Quantity of ~208k units sold**.

* **Seasonal Patterns:** The data exhibits a clear seasonal pattern: an upward trend from January to April, a decline until September, followed by a sharp and sustained increase until the end of the year.

* **Holiday Season Impact:** The dramatic sales surge in the final quarter (Q4) strongly suggests a powerful impact from the holiday shopping season, including events like Black Friday and Christmas.

* **Metric Correlation:** The patterns for Total Revenue, Total Orders, and Quantity Sold are nearly identical. This implies that sales fluctuations are primarily driven by the volume of transactions.


