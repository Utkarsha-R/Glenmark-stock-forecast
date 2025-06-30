# Glenmark Pharmaceuticals Stock Forecast Using ARIMA

This project analyzes the historical stock price of Glenmark Pharmaceuticals Ltd. and forecasts its short-term trend using ARIMA (AutoRegressive Integrated Moving Average) time series modeling. The dataset spans over 1200 trading days and includes daily closing prices.

---

## Project Overview

The goal of this project is to create a reliable 30-day forecast of Glenmark’s stock price, helping financial stakeholders gain insight into short-term movement. The model used is ARIMA, selected through AIC minimization, and validated through stationarity testing and visual diagnostics.

---

## Analysis Process

**1. Data Preparation**  
- Loaded and cleaned historical price data  
- Converted date column to datetime format and sorted chronologically  

**2. Time Series Visualization**  
- Visualized daily closing prices to observe trends  
- Decomposed the time series to isolate trend, seasonality, and residuals  

**3. Stationarity Check**  
- Conducted the Augmented Dickey-Fuller (ADF) test  
- Differenced the series to make it stationary for ARIMA modeling  

**4. ARIMA Modeling**  
- Used `pmdarima.auto_arima()` to identify the best model  
- ARIMA(0,1,0) was selected, indicating a trend-following process with drift  

**5. Forecasting**  
- Generated a 30-day forecast  
- Plotted predictions with confidence intervals  

---

## Forecast Summary

- **Model Used:** ARIMA(0,1,0)  
- **Forecast Period:** 30 business days  
- **Expected Price Movement:** ₹1450 → ₹1530 (approx.)  
- **Confidence Interval:** Narrow, indicating low short-term volatility  

---

## Visuals

**Overview of stock prices**

![Screenshot 2025-06-30 154601](https://github.com/user-attachments/assets/d86811c5-48ad-4984-ae2f-672b7e245d93)

**Average of closing prices**

![Screenshot 2025-06-30 154626](https://github.com/user-attachments/assets/aafdeade-a237-450b-9e97-8cfa5c34b2ca)

**Decomposition of Time series**

![Screenshot 2025-06-30 154703](https://github.com/user-attachments/assets/e2478421-57cc-4b24-a65a-180d3cde111a)

**Perdiction chart**

![Screenshot 2025-06-30 154801](https://github.com/user-attachments/assets/a1c2087c-48cf-468c-b035-e188dace2ec7)

---

## Business Value

This project simulates a real-world application of time series forecasting in finance. The insights can support short-term trading decisions, monthly financial planning, or serve as a component of a broader market prediction system.

---

## Key Skills Demonstrated

- Time Series Analysis  
- ARIMA Modeling with `pmdarima`  
- Python: pandas, matplotlib, statsmodels  
- Data cleaning, visualization, and interpretation  
- Business-oriented data storytelling  

---

## Files

Download the jupyter notebook [here](https://github.com/Utkarsha-R/Glenmark-stock-forecast/blob/main/Glenmark%20Pharmaceuticals%20Ltd%20Stock.ipynb)
  
---

**Author:** Utkarsha R  
**Date:** June 2025
