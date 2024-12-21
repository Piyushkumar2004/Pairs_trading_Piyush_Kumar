# Statistical Arbitrage Trading Strategy

This repository contains a Python-based implementation of a **Statistical Arbitrage (Pairs Trading)** strategy. The strategy leverages statistical techniques to identify and trade pairs of stocks that exhibit a mean-reverting relationship. It includes data analysis, signal generation, backtesting, and performance evaluation components.

---

## Features
- **Stock Data Retrieval**: Automatically fetches historical stock data using the Yahoo Finance API.
- **Trading Signal Generation**: Utilizes z-scores to detect buy/sell opportunities.
- **Data Visualization**: Visualizes stock prices with trading signals for better analysis.
- **Backtesting Framework**: Simulates trading on historical data to evaluate strategy performance.
- **Performance Metrics**: Computes financial KPIs like:
  - Strategy Returns
  - Sharpe Ratio
  - Maximum Drawdown

---

## Prerequisites

Ensure you have the following libraries installed:
```bash
pandas
numpy
matplotlib
seaborn
statsmodels
yfinance
```

Install them using:
```bash
pip install pandas numpy matplotlib seaborn statsmodels yfinance
```

## Strategy Workflow

1. **Data Import**:
   - Fetch closing prices of selected stock pairs.

2. **Statistical Testing**:
   - Check for cointegration to ensure mean-reverting behavior.

3. **Signal Generation**:
   - Use z-scores to determine trading thresholds.

4. **Backtesting**:
   - Simulate trading and track portfolio performance.

5. **Performance Evaluation**:
   - Compute returns, Sharpe ratio, and drawdowns.

---

## Results

The strategy aims to generate consistent returns with controlled risk by leveraging statistical relationships between stock pairs.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact

For queries or feedback, feel free to reach out:
- **Email**: piyushkumar38010@gmail.com
- **GitHub**: [Piyush Kumar](https://github.com/your-github-profile)

---

### Happy Trading!
