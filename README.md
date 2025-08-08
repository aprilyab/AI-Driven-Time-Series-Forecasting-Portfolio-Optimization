# Time Series Forecasting for Portfolio Management Optimization  
**Date:** 06 Aug - 12 Aug 2025  

---

## Table of Contents  
- [Business Objective](#business-objective)  
- [Situational Overview](#situational-overview)  
- [Data Description](#data-description)  
- [Project Tasks and Workflow](#project-tasks-and-workflow)  
- [Expected Outcomes](#expected-outcomes)  
- [Team and Key Dates](#team-and-key-dates)  
- [Instructions and Deliverables](#instructions-and-deliverables)  
- [References](#references)  
- [License](#license)  
- [Contact](#contact)  

---

## Business Objective  
Guide Me in Finance (GMF) Investments aims to leverage advanced time series forecasting techniques to improve portfolio management strategies. By predicting market trends and optimizing asset allocation, GMF intends to help clients maximize returns while managing risk effectively. This project focuses on building forecasting models using historical financial data and using those insights to enhance portfolio decisions.  

---

## Situational Overview  
As a Financial Analyst at GMF, your goal is to:  
- Extract and preprocess historical financial data from YFinance.  
- Explore and analyze asset price trends and volatility.  
- Develop and compare forecasting models (ARIMA/SARIMA and LSTM).  
- Use forecasts to recommend portfolio adjustments grounded in Modern Portfolio Theory (MPT).  
- Backtest the proposed strategy against a benchmark portfolio to validate its effectiveness.  

The project recognizes the challenges posed by the Efficient Market Hypothesis, using forecasting models as one of several inputs into investment decisions rather than relying on direct price predictions.  

---

## Data Description  
The project utilizes historical daily data for three assets spanning July 1, 2015, to July 31, 2025:  

| Asset | Description | Risk Profile | Source |  
|-------|-------------|--------------|--------|  
| Tesla (TSLA) | High-growth stock in the automobile sector | High volatility, high potential returns | YFinance |  
| Vanguard Total Bond Market ETF (BND) | Bond ETF providing income and stability | Low risk, stable returns | YFinance |  
| S&P 500 ETF (SPY) | Tracks the S&P 500 index | Moderate risk, diversified market exposure | YFinance |  

Data includes daily Open, High, Low, Close prices, Volume, and Adjusted Close prices to adjust for dividends and splits.  

---

## Project Tasks and Workflow  

### Task 1: Preprocess and Explore the Data  
- Extract data for TSLA, BND, and SPY using the YFinance Python library.  
- Clean data by checking for missing values and appropriate data types.  
- Perform Exploratory Data Analysis (EDA):  
  - Visualize price trends and calculate daily returns.  
  - Analyze volatility via rolling statistics.  
  - Detect outliers and analyze extreme returns.  
- Perform stationarity tests (Augmented Dickey-Fuller) and apply differencing as needed.  
- Calculate risk metrics including Value at Risk (VaR) and Sharpe Ratio.  

### Task 2: Develop Time Series Forecasting Models  
- Build and tune at least two forecasting models:  
  - Classical Statistical Model: ARIMA or SARIMA.  
  - Deep Learning Model: LSTM.  
- Split data chronologically into training (2015–2023) and testing (2024–2025) sets.  
- Optimize model parameters using techniques such as grid search and auto_arima.  
- Compare model performance with metrics like MAE, RMSE, and MAPE.  

### Task 3: Forecast Future Market Trends  
- Generate 6-12 month forecasts using the best-performing model.  
- Visualize forecasts with confidence intervals.  
- Interpret forecasted trends, volatility, and risk.  
- Identify potential market opportunities and risks.  

### Task 4: Optimize Portfolio Based on Forecast  
- Use forecasted returns for TSLA and historical average returns for BND and SPY.  
- Calculate the covariance matrix for the assets.  
- Run portfolio optimization simulations to plot the Efficient Frontier.  
- Identify and mark key portfolios: Maximum Sharpe Ratio and Minimum Volatility.  
- Recommend an optimal portfolio with weights, expected return, volatility, and Sharpe Ratio.  

### Task 5: Strategy Backtesting  
- Define a backtesting window (e.g., Aug 2024 - Jul 2025).  
- Create a benchmark portfolio (e.g., 60% SPY / 40% BND).  
- Simulate portfolio performance using your strategy and benchmark.  
- Compare cumulative returns and Sharpe Ratios.  
- Summarize results and viability of the strategy.  

---

## Expected Outcomes  

### Skills Developed  
- Fetching and preprocessing financial data using APIs (YFinance).  
- Data wrangling with pandas and data normalization/scaling.  
- Feature engineering (returns, rolling volatility).  
- Building and tuning ARIMA/SARIMA and LSTM models.  
- Model evaluation with multiple metrics.  
- Portfolio optimization using Modern Portfolio Theory principles.  
- Simulation and backtesting of investment strategies.  

### Knowledge Gained  
- Characteristics of different asset classes.  
- Implications of the Efficient Market Hypothesis.  
- Importance of stationarity in time series modeling.  
- Interpretation of the Efficient Frontier and portfolio selection.  
- Understanding backtesting and benchmarking.  

### Analytical Abilities  
- Critical evaluation of forecasting models.  
- Data-driven decision-making for portfolio management.  
- Synthesizing business objectives into actionable insights.  

---

## Team and Key Dates  

**Tutors:**  
- Mahlet  
- Rediet  
- Kerod  
- Rehmet  

**Key Dates:**  
- Discussion on the case: Wednesday 06 Aug 2025 (#all-week11 channel)  
- Interim Solution Submission: Sunday 10 Aug 2025, 20:00 UTC  
- Final Submission Deadline: Tuesday 12 Aug 2025, 20:00 UTC  

---

## Instructions and Deliverables  
- Follow the tasks as outlined above.  
- Submit code on GitHub with clear documentation and instructions.  
- Provide a professional PDF report or detailed technical blog post as final deliverable.  
- Include visuals, insights, and code screenshots as appropriate.  

---

## References  

### Data Science & Time Series Forecasting  
- [GeeksforGeeks: Time Series Analysis](https://www.geeksforgeeks.org/time-series-analysis-and-forecasting/)  

### Portfolio Optimization  
- [Portfolio Optimization in R](https://miltonfmr.com/the-complete-guide-to-portfolio-optimization-in-r-part1/)  

### Financial Concepts  
- [Investopedia: Efficient Market Hypothesis](https://www.investopedia.com/terms/e/efficientmarkethypothesis.asp)  

---

## License  
This project is for educational purposes under the 10 Academy AI Mastery challenge guidelines.  

---

## Contact  
For questions or feedback:  
**Author:** Henok Yoseph  
**Email:** henokapril@gmail.com  
**GitHub:** [https://github.com/aprilyab](https://github.com/aprilyab)  

---

*Thank you for your interest in the Time Series Forecasting and Portfolio Optimization project.*
