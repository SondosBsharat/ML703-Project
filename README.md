# LLM-Augmented Bayesian Time Series Forecasting:Integrating Market Sentiment and Volatility Shifts

This repository contains the code, datasets, and results for our ML703 final project, which investigates the integration of sentiment analysis, volatility indicators, and Bayesian change-point detection into financial time series forecasting.

## 🌐 Project Summary

We propose a unified Bayesian forecasting framework that combines:
- **FinBERT-derived sentiment** from financial news,
- **Volatility signals** such as the CBOE VIX, and
- **MCMC-based Bayesian change-point detection** to adapt to market regime shifts.

The goal is to evaluate whether incorporating qualitative sentiment data and probabilistic regime modeling can improve the prediction of daily S&P 500 returns.

## 🔍 Research Question

> Can return forecasting be improved by integrating sentiment and volatility signals, while dynamically adapting to structural changes in financial time series?

## 📦 Repository Structure

```bash
ML703-Project/
│
├── Datasets/                 # Raw and processed datasets (S&P 500, sentiment, VIX)
├── Bayesian Time Series Forecasting/    # Implementation 
├── Baselines/                  # Implementation               # Helper functions (e.g. sentiment scoring, preprocessing)
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation (you are here)
