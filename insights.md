# Stock Analysis Summary: TSLA, SPY, and BND (2015–2025)

This document provides key insights on the price trends, returns behavior, and stationarity test results of Tesla (TSLA), S&P 500 ETF (SPY), and Vanguard Bond ETF (BND) based on data from July 2015 to July 2025.

---

## 1. Tesla (TSLA)

### Overall Price Trend
- Tesla’s stock price surged from around **$9.5** in 2015 to nearly **$480** by 2025.
- Shows a **strong bullish long-term trend** with significant appreciation.
- The price series is **non-stationary** (ADF p-value ≈ 0.57), meaning the stock price follows a trend and is not mean-reverting.

### Returns Behavior
- Daily returns exhibit **high volatility**, with many days showing swings above ±10%.
- Returns are **stationary** (ADF p-value ≈ 0), fluctuating around a constant mean.
- High volatility indicates **high risk and potential high reward**, reflecting Tesla’s growth and market speculation.

### Implications
- Price trending upwards but unpredictable short-term movements.
- Investors should use returns for modeling, not raw prices.
- Requires risk management and portfolio diversification.

---

## 2. S&P 500 ETF (SPY)

### Overall Price Trend
- SPY price rose steadily from about **$155** in 2015 to over **$630** in 2025.
- The price series is **non-stationary** (ADF p-value ≈ 0.99), indicating a trending behavior typical of broad market indices.

### Returns Behavior
- Daily returns have **moderate volatility**, much lower than Tesla.
- Returns are **stationary** (ADF p-value ≈ 0), suitable for predictive modeling.
- More stable compared to Tesla but still sensitive to market fluctuations.

### Implications
- Reflects overall market performance and is a good proxy for diversified market exposure.
- Suitable for long-term investment and lower volatility risk than Tesla.

---

## 3. Vanguard Bond ETF (BND)

### Overall Price Trend
- BND price ranged narrowly between approximately **$60** and **$77** over the 10-year period.
- The price series is **non-stationary** (ADF p-value ≈ 0.52), though less volatile in trend compared to equities.

### Returns Behavior
- Returns exhibit **low volatility**, reflecting bond market stability.
- Returns are **stationary** (ADF p-value ≈ 0), ideal for time series analysis.
- Low risk and steady income characteristics.

### Implications
- Serves as a **stabilizer in portfolios**, reducing overall risk.
- Suitable for conservative investors seeking steady returns.

---

## Summary of Stationarity Tests

| Asset | Series        | ADF Statistic | p-value          | Stationary?               |
|-------|---------------|---------------|------------------|--------------------------|
| TSLA  | Price         | -1.42         | 0.573            | No (non-stationary)      |
| TSLA  | Returns       | -34.68        | 0.0              | Yes (stationary)         |
| SPY   | Price         | 0.69          | 0.99             | No (non-stationary)      |
| SPY   | Returns       | -16.26        | 3.5e-29          | Yes (stationary)         |
| BND   | Price         | -1.54         | 0.52             | No (non-stationary)      |
| BND   | Returns       | -9.89         | 3.5e-17          | Yes (stationary)         |

---

## Key Takeaways

- **Price series for all assets are non-stationary** — indicating trends over time. Modeling should focus on **returns** or differenced data.
- **Returns for all assets are stationary**, making them suitable for time series forecasting and risk modeling.
- Tesla’s returns show the **highest volatility**, indicating greater risk and potential reward.
- SPY returns show **moderate volatility**, representing diversified market risk.
- BND returns are **least volatile**, providing stability and low risk.

---

## Recommendations for Analysis and Investment

- Use **returns (differenced prices)** for statistical modeling like ARIMA to meet stationarity assumptions.
- Combine Tesla’s growth potential with SPY’s diversification and BND’s stability for balanced portfolios.
- Employ risk measures and volatility forecasting due to Tesla’s high fluctuations.
- Bonds (BND) act as a cushion against equity volatility, reducing portfolio risk.

---

*Prepared with data from Yahoo Finance (2015-2025) and Augmented Dickey-Fuller stationarity tests.*

