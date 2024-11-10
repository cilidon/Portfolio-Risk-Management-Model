# Portfolio Risk Management Model

## Project Overview
This project implements a comprehensive risk management model for a diversified investment portfolio. It demonstrates advanced financial analysis techniques, including Value at Risk (VaR) calculation using Monte Carlo simulations, stress testing, and interactive data visualization.

## Background
In today's volatile financial markets, effective risk management is crucial for investors and portfolio managers. This project aims to provide a robust framework for assessing and visualizing portfolio risk, enabling informed decision-making in portfolio management.

## Data and Methodology
### Data Source
Historical price data for six assets (AAPL, MSFT, JNJ, AGG, GLD, DBC) obtained from Alpha Vantage API
5-year daily OHLVC data including open, high, low, close, and volume
### Data Manipulation
Calculated daily returns using closing prices
Computed correlation matrix and summary statistics
Implemented Monte Carlo simulations for VaR calculation
Conducted stress tests based on historical and hypothetical scenarios

### Portfolio Composition
- AAPL (Apple Inc.): 20%
- MSFT (Microsoft Corporation): 20%
- JNJ (Johnson & Johnson): 15%
- AGG (iShares Core U.S. Aggregate Bond ETF): 25%
- GLD (SPDR Gold Shares): 10%
- DBC (Invesco DB Commodity Index Tracking Fund): 10%

## Executive Summary
The risk management model provides key insights into the portfolio's risk profile:
- Value at Risk (VaR): 95% 1-day VaR of $16,300.21 (1.63% of portfolio value)
- Stress Test Results: Varied portfolio performance under different market conditions
- Asset Volatility: Highest for tech stocks (AAPL, MSFT), lowest for bonds (AGG)
- Diversification Benefits: Evident in stress test scenarios and overall risk metrics

## Key Insights and Recommendations
- Tech Exposure: High allocation to tech stocks contributes significantly to portfolio volatility
- Diversification: Bonds and commodities provide some protection against market downturns
- Downside Protection: Moderate risk based on VaR, but potential for larger losses in extreme scenarios
- Scenario Planning: Prepare for tech sector downturns and global crises
- Upside Potential: Portfolio shows resilience in certain market conditions

## Recommendations:
- Consider reducing tech stock exposure
- Explore adding more defensive stocks
- Regularly update stress test scenarios
- Implement more granular risk analysis (e.g., Expected Shortfall)
- Create a dynamic, real-time risk monitoring dashboard

## Caveats and Assumptions
- Limited Historical Data: 5-year timeframe may not capture all market cycles
- Simplified Asset Selection: Limited to six assets, may not represent a fully diversified portfolio
- Static Weights: Assumes constant portfolio allocation without rebalancing
- Normal Distribution Assumption: VaR calculation assumes normally distributed returns
- Limited Stress Scenarios: May not cover all possible market conditions
- No Transaction Costs or Taxes: Model does not account for these real-world factors

## Future Enhancements
- Incorporate more assets and asset classes
- Implement dynamic portfolio optimization
- Integrate machine learning for predictive risk analytics
- Develop real-time data feeds and risk monitoring
- Include more sophisticated risk metrics and regulatory compliance features
