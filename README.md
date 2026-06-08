
# Historical Volatility Analysis for Crypto & Equities

Built quantitative finance models in Python to analyze historical volatility, log returns, ATR, drawdowns, and rolling statistical indicators for crypto and equity markets using Pandas and NumPy for quantitative trading research, market behavior analytics, and risk assessment.

## Repository Structure

```
├── BTC_TimeSeries.csv
├── cryptoVolatilityAnalysis.py
└── equityVolatilityAnalysis.py
```

## Overview

These scripts perform historical volatility analysis for cryptocurrency and equity time series.

### Crypto Historical Volatility Analysis

The `cryptoVolatilityAnalysis.py` script processes Bitcoin historical time series data from `BTC_TimeSeries.csv` and performs:

- Data cleaning and preprocessing
- Log return calculations
- Normalized candle height calculations
- All-time high and all-time low analysis
- Percentage drawdown from all-time highs
- Rolling high/low range analysis
- Range-over-price calculations
- Log return Z-score calculations
- Candle height Z-score calculations
- Rolling average log returns
- Rolling standard deviation of log returns
- Rate of change calculations
- Average True Range (ATR) calculations
- ATR percentage calculations
- Efficiency metrics
- Correlation matrix generation

### Equity Historical Volatility Analysis

The `equityVolatilityAnalysis.py` script retrieves equity time series data using Yahoo Finance and performs:

- Log return calculations
- Adjusted price calculations
- Normalized candle height calculations
- All-time high and all-time low analysis
- Percentage drawdown from all-time highs
- Rolling high/low range analysis
- Range-over-price calculations
- Log return Z-score calculations
- Candle height Z-score calculations
- Rolling average log returns
- Rolling standard deviation of log returns
- Rate of change calculations
- Average True Range (ATR) calculations
- ATR percentage calculations
- Efficiency metrics
- Correlation matrix generation

## Technologies Used

- Python
- NumPy
- Pandas
- yahoo_fin
````
