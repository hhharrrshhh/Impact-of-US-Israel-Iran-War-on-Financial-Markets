<div align="center">

# 🌍 Geopolitical Shock Impact Analysis
### Time Series Analysis of the US–Israel–Iran Conflict on Indian Financial Markets

A comprehensive econometric and deep learning analysis of how geopolitical conflict propagates through crude oil markets and affects India's financial ecosystem using VAR, ARIMAX, GARCH, Prophet, and LSTM models.

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-LSTM-FF6F00?logo=tensorflow)
![Statsmodels](https://img.shields.io/badge/Statsmodels-Econometrics-blue)
![Prophet](https://img.shields.io/badge/Prophet-Time%20Series-0099cc)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

---

# 📌 Overview

Financial markets are highly sensitive to geopolitical instability. Military conflicts often trigger supply-chain disruptions, commodity price shocks, currency fluctuations, and increased market volatility.

This project investigates how the **US–Israel–Iran conflict** influenced key Indian financial indicators by combining traditional econometric models with modern deep learning techniques. The study models shock transmission from global crude oil prices to Indian equity markets, exchange rates, volatility, and gold prices.

Instead of relying on a single forecasting model, multiple complementary approaches were employed to understand both **market dynamics** and **future scenarios**.

---

# 🎯 Objectives

- Quantify the impact of geopolitical conflict on Indian financial markets
- Analyze crude oil as the primary transmission mechanism
- Forecast future market behaviour under sustained conflict
- Compare statistical and deep learning forecasting techniques
- Model volatility clustering during geopolitical events

---

# 📊 Dataset

### Time Period

**January 2024 – April 2026**

### Total Observations

**539 Daily Records**

### Financial Variables

- Brent Crude Oil
- NIFTY 50 Index
- USD/INR Exchange Rate
- India VIX
- Gold Prices

---

# ⚙️ Feature Engineering

The dataset was transformed using several financial preprocessing techniques:

- Log Returns
- Missing Value Handling
- Stationarity Testing
- Binary War Event Indicator (WarDummy)
- Time Series Normalization

WarDummy

```
0 → Before conflict

1 → During conflict
```

---

# 📈 Methodology

```
Financial Market Data
          │
          ▼
Data Cleaning
          │
          ▼
Feature Engineering
          │
          ▼
Stationarity Testing
          │
          ▼
Econometric Models
          │
          ▼
Deep Learning Models
          │
          ▼
Forecasting & Analysis
```

---

# 🤖 Models Used

## 📌 ARIMAX

Forecasted crude oil prices using geopolitical events as an exogenous variable.

**Purpose**

- Oil price forecasting
- Event impact estimation
- Quantifying war effects

---

## 📌 VAR (Vector AutoRegression)

Captured interdependencies between multiple macroeconomic variables.

Used for:

- Dynamic relationships
- Impulse Response Functions
- Forecast Error Decomposition

---

## 📌 Granger Causality

Determined causal relationships between financial variables.

Used to identify:

- Oil → INR
- Oil → NIFTY
- Oil → India VIX

---

## 📌 GARCH

Modeled volatility clustering during periods of geopolitical uncertainty.

Applications:

- Risk estimation
- Volatility forecasting
- Financial uncertainty measurement

---

## 📌 Prophet

Generated medium-term forecasts for financial indicators using trend and seasonality decomposition.

---

## 📌 LSTM Neural Network

Applied deep learning to capture long-term sequential dependencies in financial time series.

---

# 📊 Key Findings

### Oil as the Primary Transmission Channel

Crude oil was identified as the dominant channel through which geopolitical shocks propagated into Indian markets.

---

### Significant Impact on Oil Prices

ARIMAX estimated a statistically significant increase in oil prices associated with the conflict.

```
Coefficient

+6.56

p-value

0.024
```

---

### Market Forecast

Projected Brent crude oil range:

```
$90.76 – $106.45
```

Estimated impact on NIFTY 50:

```
8–12% structural decline
```

---

### Forecasting Performance

| Model | RMSE |
|--------|------|
| Prophet | 15.68 |
| LSTM | 17.83 |

---

# 📈 Analysis Techniques

- Augmented Dickey-Fuller Test
- Log Return Analysis
- Vector AutoRegression
- ARIMAX
- GARCH
- Prophet Forecasting
- LSTM Forecasting
- Granger Causality
- Impulse Response Functions
- Volatility Analysis

---

# 🛠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| Language | Python |
| Data Analysis | Pandas, NumPy |
| Econometrics | Statsmodels |
| Volatility Modeling | ARCH |
| Deep Learning | TensorFlow, Keras |
| Forecasting | Prophet |
| Visualization | Matplotlib, Seaborn |

---

# 📂 Project Structure

```
US-Israel-Iran-War-impact-Analysis/

├── AFTS project.ipynb
├── README.md
├── Project Report.pdf
└── datasets/
```

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/US-Israel-Iran-War-impact-Analysis.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter

```bash
jupyter notebook
```

Run

```
AFTS project.ipynb
```

---

# 💼 Applications

- Financial Risk Analysis
- Macroeconomic Forecasting
- Quantitative Finance
- Geopolitical Risk Assessment
- Investment Research
- Economic Policy Analysis
- Time Series Forecasting

---

# 🔮 Future Improvements

- Replace WarDummy with the Caldara–Iacoviello Geopolitical Risk Index
- Implement Vector Error Correction Models (VECM)
- Cointegration Analysis using Johansen Test
- Residual Diagnostics
- Bayesian Structural Time Series
- Real-time market monitoring dashboard
- Transformer-based forecasting models

---

# 👨‍💻 Author

**Harsh Gharat**

---

# 📚 References

- Yahoo Finance
- Statsmodels
- TensorFlow
- Prophet
- ARCH
- OECD Financial Data

---

# 📄 License

This project was developed for academic research purposes.

---

## ⭐ If you found this project useful, consider giving it a star!# Impact-of-US-Israel-Iran-War-on-Financial-Markets
