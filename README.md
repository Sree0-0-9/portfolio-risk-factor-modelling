# Portfolio Risk Factor Modelling

This project estimates portfolio risk and factor exposure for a buy-and-hold technology portfolio using simulation, monthly return construction, and the Fama-French three-factor model.

## Business Problem

Investors and analysts need to understand whether portfolio returns are explained by broad market, size, and value factors, and how well a factor model captures realised performance. This project builds a portfolio return series and evaluates model fit using regression-based risk factor analysis.

## What This Project Demonstrates

- Vectorized Monte Carlo simulation for a stochastic stopping-time problem
- Buy-and-hold portfolio construction using monthly adjusted closing prices
- Monthly return calculation and excess-return preparation
- Fama-French three-factor model estimation
- Regression diagnostics including fitted values, residuals, and model interpretation
- Python-based financial analytics workflow

## Key Findings

- Factor modelling helps explain how portfolio returns relate to market, size, and value risk factors.
- Regression diagnostics are important for assessing whether a factor model meaningfully explains realised returns.
- Combining simulation, return construction, and factor regression demonstrates an end-to-end financial analytics workflow.

## Business Recommendation

Use factor exposure analysis to support portfolio review, risk communication, and performance attribution, while recognising that model results should be interpreted alongside market context and investment objectives.

## Tools Used

- Python
- pandas
- NumPy
- statsmodels
- scikit-learn
- Matplotlib
- yfinance

## Repository Structure

```text
.
├── data/
│   └── FF3F_Monthly.csv
├── notebooks/
│   └── portfolio_risk_factor_modelling.ipynb
└── README.md
```
