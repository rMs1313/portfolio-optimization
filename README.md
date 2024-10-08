# Portfolio Optimization Using Modern Portfolio Theory (MPT)

## Description
This project applies Modern Portfolio Theory (MPT) to construct an optimized financial portfolio, aiming to maximize returns while minimizing risk. The project includes risk-return analysis, Efficient Frontier visualization, and Sharpe Ratio calculations. By combining less correlated stocks, we attempt to build a more diversified portfolio with better risk-adjusted returns.

## Features
- Historical stock price analysis using Yahoo Finance data.
- Portfolio optimization based on mean-variance analysis.
- Visualizations: Efficient Frontier, stock correlation, and risk-return profiles.
- Monte Carlo simulation to explore potential portfolio weight distributions and identify the optimal allocation.

## Methodology
1. **Import Stock Data**: Using the Yahoo Finance API (`yfinance`), stock data is imported for analysis.
2. **Preprocess Data**: The data is cleaned and prepared to make it usable for portfolio analysis (e.g., filling missing values, selecting relevant columns).
3. **Analyze Closing Prices**: Explore and visualize the stock closing prices.
4. **Plot Return Distribution**: Visualize the distribution of returns across different stocks.
5. **Plot Correlation Matrix**: Analyze the correlation between stocks to inform diversification strategies.
6. **Modern Portfolio Theory (MPT) Application**:
   - Use MPT concepts to combine stocks in a way that maximizes risk-adjusted returns.
     a. **Expected Returns**: Calculated using the Capital Asset Pricing Model (CAPM).
     b. **Volatility**: Standard deviation of returns is used to measure stock volatility.
     c. **Sharpe Ratio**: The risk-free rate is subtracted from the expected returns to compute the Sharpe Ratio, a key metric for optimizing portfolios.
7. **Efficient Frontier**: Plot the Efficient Frontier to visualize optimal portfolios with different risk-return profiles.
8. **Monte Carlo Simulation**: Simulate various weight combinations and evaluate the portfolio’s performance to find the most optimized asset allocation.

## Data Source
1. Made use of Yahoo Finance API to collect stock market data.
2. set Install yfinance API and import it in the following way:
   ```python
   !pip install yfinance
   import yfinance as yf

## Results
- The project outputs the optimal portfolio allocation, including the weight distribution of each stock in the portfolio based on risk and return metrics.
- Visualizations include:
   - **Efficient Frontier**: A plot showing optimal portfolios across different risk levels.
   - **Return Distributions**: A plot showing the distribution of returns for individual stocks in the portfolio.
   - **Stock Correlation Matrix**: A heatmap showing the correlation between different stocks, helping to identify diversification opportunities.

  
