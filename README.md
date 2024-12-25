# Optimal ETFs Portfolio Analysis

## Overview
This project focuses on constructing and analyzing the optimal ETFs portfolio using data-driven methodologies. By employing various financial and statistical techniques, the project aims to identify and validate a robust investment portfolio suitable for diverse economic conditions.

## Investor Background
- **Investment Horizon**: Long-term (10+ years)  
- **Risk Tolerance**: Moderate  
- **Preference**: Favor growth-oriented exposure to the technology sector while maintaining diversification with defensive assets such as consumer staples and gold.  

## Project Objective
The primary goal is to design an optimal portfolio of ETFs that balances risk and return effectively while maintaining stability across various economic scenarios. Key objectives include:
- Portfolio optimization using Monte Carlo simulations, Sharpe ratio maximization, and risk minimization.
- Validation through CAPM analysis, VaR, CVaR, stress testing, and scenario analysis.
- Comprehensive risk and return attribution for portfolio evaluation.

## Project Outline
1. **Data Collection**: Downloaded historical ETF data and preprocessed monthly returns.
2. **Preliminary Analysis**: Evaluated ETF performance, correlation matrices, and covariance stability.
3. **Portfolio Optimization**:
   - Balanced risk and return through Sharpe ratio optimization while ensuring reasonable weight allocation.
   - Monte Carlo simulations to visualize the efficient frontier.
   - Applied VaR (Value at Risk) and CVaR (Conditional Value at Risk) to evaluate tail risk.
4. **Validation**:
   - CAPM analysis to compute Alpha, Beta, and R-squared for market sensitivity and excess returns.
   - Stress testing to assess resilience under extreme market shocks.
   - Scenario analysis across economic periods (growth, recession, recovery).
   - Backtesting for historical performance evaluation.
5. **Attribution Analysis**: Risk and return contributions for each ETF in the optimal portfolio.

## Methodology
- **Monte Carlo Simulations**: Generated random portfolios to visualize the efficient frontier and compare against the optimized portfolio.
- **Sharpe Ratio Optimization**: Optimized portfolio weights to achieve a reasonable balance between risk-adjusted returns and practical weight allocation.
- **VaR and CVaR**: Quantified potential losses in extreme market conditions, assessing tail risk under historical and parametric assumptions.
- **CAPM Analysis**: Calculated Alpha (excess returns), Beta (market sensitivity), and R-squared (explanatory power) to evaluate the portfolio's performance relative to the market.
- **Stress Testing**: Simulated market shocks to evaluate portfolio resilience under adverse conditions.
- **Scenario Analysis**: Assessed portfolio performance across defined economic periods, including Global Growth, COVID-19 Recession, and Economic Recovery.
- **Attribution Analysis**: Quantified each ETF's contribution to portfolio risk and returns to ensure balanced diversification.

## Results
- **Optimal Portfolio Performance**:
  - Delivered the most balanced Sharpe ratio when compared to Monte Carlo-simulated portfolios, where the highest Sharpe ratio weights were deemed impractical due to concentrated risk allocations.
  - Demonstrated consistent performance across diverse economic scenarios.
  - Balanced risk-return contributions across growth and defensive assets.
- **Scenario Analysis**:
  - Maintained strong performance during Global Growth with minimal drawdowns.
  - Showed resilience in the COVID-19 Recession with solid returns and moderate volatility.
  - Adapted effectively during the Economic Recovery phase.
- **Risk Attribution**:
  - Technology sector (QQQ) drove returns but contributed the most risk.
  - Defensive sectors (IAU, XLP, XLV) balanced growth with stability.
- **Tail Risk Metrics**:
  - VaR and CVaR provided insights into potential losses during extreme market conditions, validating the portfolio's robustness under tail-risk scenarios.

## Conclusion
This project confirms that the selected optimal portfolio is robust, resilient, and well-diversified. While it does not achieve the absolute highest Sharpe ratio due to practical weight constraints, it delivers the most balanced performance, ensuring reasonable risk-return trade-offs. Its strong performance across CAPM analysis, VaR, CVaR, stress testing, and scenario evaluations validates its superiority over Monte Carlo-generated alternatives. The portfolio balances high returns from growth-oriented assets with stability from defensive sectors, making it a reliable choice for long-term investment.
