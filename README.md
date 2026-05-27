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

## Portfolio Note

This is a public portfolio version prepared from academic analytics work. Student IDs, course-submission wording, and private submission details have been removed.
