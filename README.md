# Bitcoin Volatility Forecasting & Risk Backtesting

## Project Overview

This project explores financial time-series forecasting and model risk validation using historical Bitcoin (BTC-USD) market data.

The goal is to investigate whether historical price movements and volatility patterns can help forecast future market volatility.

The project will emphasize reproducible machine learning, chronological validation, backtesting, and understanding model limitations.

**Status:** In development

## Objectives

- Collect and explore historical Bitcoin market data.
- Calculate daily returns and historical volatility.
- Engineer features using past market information.
- Develop a simple forecasting baseline and compare it with a machine learning model.
- Evaluate forecasting performance using chronological and walk-forward validation.
- Investigate look-ahead bias, model stability, and periods of changing market conditions.
- Document results, limitations, and potential improvements.

## Technologies

- **Python:** Primary programming language
- **pandas and NumPy:** Data processing and numerical calculations
- **scikit-learn:** Machine learning and model evaluation
- **Matplotlib and Seaborn:** Data visualization
- **yfinance:** Historical Bitcoin market data
- **pytest:** Automated testing
- **Jupyter:** Exploratory analysis
- **Git and GitHub:** Version control

## Project Structure

```text
bitcoin-volatility-risk-backtesting/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── results/
│   └── figures/
├── src/
│   ├── __init__.py
│   ├── data_loader.py
│   └── features.py
├── tests/
│   └── test_features.py
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
```

## Planned Methodology

1. **Data Collection:** Retrieve historical Bitcoin market prices.
2. **Exploratory Data Analysis:** Examine returns, volatility, and market behavior.
3. **Feature Engineering:** Calculate lagged returns and rolling volatility using historical information.
4. **Model Development:** Establish a baseline and train a predictive model.
5. **Backtesting:** Evaluate forecasts on later periods using time-aware validation.
6. **Model Validation:** Compare errors, investigate model failures, and document limitations.

## Reproducibility

Clone the repository and create a Python virtual environment.

```powershell
py -3.13 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
```

The project will use Python 3.13. Additional execution instructions will be documented as the modeling pipeline is implemented.

## Current Progress

- [x] GitHub repository initialized
- [x] Project folder structure created
- [x] Python environment configured
- [x] Dependencies installed
- [ ] Historical Bitcoin data collected
- [ ] Exploratory data analysis completed
- [ ] Features engineered
- [ ] Forecasting models developed
- [ ] Walk-forward backtesting completed
- [ ] Model results and limitations documented

## Limitations

This project is intended for educational and research purposes. Forecasting volatility is not equivalent to predicting market direction or generating profitable trading signals.

Model performance will need to be evaluated on unseen chronological data before drawing conclusions about forecasting reliability.

## Data Source

Historical Bitcoin market data will be retrieved using the `yfinance` Python library.

## Author

JeremyJay-Coding

GitHub: https://github.com/JeremyJay-Coding
