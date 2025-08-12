# Backtesting Results and Summary

---

## Performance Overview

| Metric                               | Strategy Portfolio | Benchmark Portfolio |
|------------------------------------|--------------------|---------------------|
| **Total Return**                   | 18.30%             | 12.47%              |
| **Annualized Sharpe Ratio**        | 0.94               | 1.02                |

---

## Interpretation of Results

### Total Return

The strategy portfolio achieved a **total return of 18.30%** over the backtesting period, outperforming the benchmark portfolio’s return of **12.47%**. This indicates that the model-driven strategy was able to generate higher absolute returns than the simple 60% SPY / 40% BND benchmark.

### Sharpe Ratio (Risk-Adjusted Return)

Despite the higher total return, the strategy’s **annualized Sharpe Ratio is 0.94**, which is slightly lower than the benchmark’s Sharpe Ratio of **1.02**. The Sharpe Ratio measures risk-adjusted performance, meaning the benchmark achieved better returns per unit of risk taken.

---

## Conclusion

- The backtest shows that the **strategy outperformed the benchmark in terms of total return**, suggesting the portfolio construction based on the forecast and optimization (from Task 4) is effective at generating growth over the backtesting period.

- However, the **strategy did not outperform the benchmark on a risk-adjusted basis**. The lower Sharpe Ratio indicates that the strategy may involve higher volatility or risk relative to the returns it delivers compared to the benchmark.

- This initial backtest implies that while the **model-driven approach has promise**, it may require further refinement to improve risk management and consistency. Potential improvements could include:
  - Incorporating risk constraints during optimization,
  - More frequent rebalancing or dynamic adjustments,
  - Expanding the universe of assets,
  - Incorporating alternative risk measures.



---

