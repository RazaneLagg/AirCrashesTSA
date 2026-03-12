# ✈️ Airplane Crashes — Time Series Analysis

> Statistical time series analysis and forecasting on historical airplane crash data to identify trends, seasonality and predict future incident patterns.

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?style=flat-square&logo=pandas)
![Statsmodels](https://img.shields.io/badge/Statsmodels-TSA-green?style=flat-square)

---

## 📌 Overview

This individual project applies classical **time series analysis techniques** to historical airplane crash data — decomposing the series, testing for stationarity, and building forecasting models to predict future trends.

---

## 🔧 Analysis Steps

```
1. Data Exploration     →  EDA, missing values, temporal distribution
2. Decomposition        →  Trend, seasonality, residuals
3. Stationarity Testing →  ADF test, KPSS test
4. Transformations      →  Differencing, log transform
5. Forecasting          →  ARIMA / SARIMA model fitting
6. Evaluation           →  MAE, RMSE, residual analysis
```

---

## 📁 Project Structure

```
airplane-crashes-tsa/
├── AirplaneCrashesTSA.ipynb   # Main notebook
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

```bash
git clone https://github.com/razanelagagna/airplane-crashes-tsa
cd airplane-crashes-tsa
pip install pandas numpy matplotlib statsmodels jupyter
jupyter notebook AirplaneCrashesTSA.ipynb
```

---

## 👩‍💻 Author

**Razane Lagagna** — Individual project — ENSIA, 2024
