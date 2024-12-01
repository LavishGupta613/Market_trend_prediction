## Dataset Overview

This project utilizes **3 years of daily closing price data** for a financial asset to calculate technical indicators and predict market trends. Below are the details of the dataset and its usage:

### Data Source
- The historical price data was obtained from platforms like [Yahoo Finance](https://finance.yahoo.com) or similar financial APIs.
- Covers the period: **January 2021 - December 2023**.

### Data Features
The dataset includes the following columns:
- **`Date`**: The trading date.
- **`Close`**: The daily closing price of the asset.

### Data Format
The data is provided in **CSV format**, with clean, structured rows for easy preprocessing and analysis.

---

## Technical Indicators

The following key technical indicators were computed using the dataset:

1. **Moving Averages (MA)**:
   - Simple Moving Average (SMA)
   - Exponential Moving Average (EMA)

2. **Relative Strength Index (RSI)**:
   - Identifies overbought and oversold conditions.

3. **Bollinger Bands**:
   - Measures price volatility and potential breakout levels.

4. **MACD (Moving Average Convergence Divergence)**:
   - Helps identify trend strength and reversals.

---

## Usage in the Project

- **Data Preprocessing**: Cleaned and normalized the data for accurate indicator calculation.
- **Correlation Analysis**: Analyzed relationships between technical indicators and market trends.
- **Trend Prediction**: Developed a combined indicator using weighted averages to forecast **bullish** or **bearish** trends.

This dataset formed the backbone for building and evaluating the predictive model's accuracy in forecasting market movements.

---
