# Implied Volatility Prediction – NKSR Hackathon 🧠📈

![Hackathon Rank](https://img.shields.io/badge/Rank-4th%20Place-blueviolet)
![Python](https://img.shields.io/badge/Made%20with-Python-3776AB?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📝 Description

4th place solution for predicting implied volatility surfaces in the **Volatility Curve Hackathon** hosted by **NK Securities Research**, using high-frequency NIFTY50 options data. The goal was to reconstruct the market’s volatility smile by predicting missing implied volatility (IV) values based on anonymized per-second features.

---

## 🧠 Competition Overview

The challenge focused on forecasting implied volatilities (IVs) for **NIFTY50 index options**, a crucial aspect of options pricing and market sentiment analysis. Participants were given:

- Per-second historical market data with missing IV entries.
- Anonymized engineered features from real-world trading environments.

The task: **build a model that accurately fills in missing IV values across different strike prices and maturities.**

**Evaluation Metric:**  
Mean Squared Error (MSE) between the true and predicted implied volatility values.

---

## 🚀 My Approach

- ✅ Feature engineering from per-second anonymized data
- ✅ Tree-based regressors and neural nets with careful validation
- ✅ Curve smoothing and post-processing to preserve volatility structure
- ✅ Emphasis on consistency across strike-maturity combinations

---

## 📚 Key Learnings

- Deepened understanding of **Black-Scholes** and implied volatility behavior.
- Learned how to handle **high-frequency financial time series data**.
- Balanced **model performance** with **domain logic** in a noisy, nonlinear setting.
- Developed robust ML pipelines for **real-world quantitative finance challenges**.

---
