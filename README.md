# 💹 Pairs Trading Algorithm for Financial Markets (FC24OPS2)

## 📘 Project Overview
This project implements a **Pairs Trading Algorithm** based on statistical arbitrage principles to detect and exploit temporary price discrepancies between correlated assets in financial markets. Pairs trading involves simultaneously going long on one asset and short on another, anticipating that their prices will revert to a mean relationship over time.

---

## 🎯 Objectives
- Identify and select asset pairs exhibiting **cointegration** or **mean-reversion** behavior.
- Collect and clean historical price data across stocks, ETFs, or cryptocurrencies.
- Perform **correlation and spread analysis** to find profitable trading opportunities.
- Implement a trading strategy based on defined thresholds for entry and exit signals.
- Backtest the algorithm to evaluate **profitability, risk-adjusted returns, and drawdowns**.
- Optimize model parameters and optionally integrate **machine learning** for adaptive trading.

---

## 📦 Deliverables
- 🧠 **Trading Algorithm**: Implemented in a clean, modular Python notebook.
- 📊 **Backtesting Report**: Visual and statistical evaluation of strategy performance.
- 📘 **User Guide**: Instructions to run the algorithm, adjust inputs, and interpret signals.
- 🛠 **Parameter Tuning Module**: For refining thresholds and optimization.

---

## 🛠 Tech Stack & Tools
- Python (Pandas, NumPy, SciPy, Statsmodels)
- Jupyter Notebook
- Matplotlib, Seaborn (for visualization)
- yfinance / Alpha Vantage / Crypto APIs (for data)
- Scikit-learn (for optional ML integration)

---

## 🔍 Methodology
1. **Data Collection**: Fetch historical daily closing prices.
2. **Pair Selection**: Use Pearson correlation, cointegration tests (ADF), and spread analysis.
3. **Signal Generation**: Define entry and exit thresholds based on spread Z-scores.
4. **Backtesting**: Simulate trades and evaluate metrics such as Sharpe ratio, CAGR, and max drawdown.
5. **Optimization**: Fine-tune parameters like lookback window and threshold levels.
6. **Explainability**: Optionally apply ML for dynamic thresholding and pattern recognition.

---

## ⚠️ Constraints
- Data limitations (e.g., survivorship bias, low liquidity assets)
- Model risks like overfitting or false positives
- Computational load for large backtests
- Real-world factors (slippage, transaction costs) not accounted in basic backtests

---

## 🔗 References & Learning Resources
- [Investopedia – Pairs Trading](https://www.investopedia.com/terms/p/pairstrade.asp)
- [Pairs Trading – YouTube Guide](https://www.youtube.com/watch?v=JTucMRYMOyY)
- [SSRN Research Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=141615)


## 📌 License
This repository is intended for educational and non-commercial purposes only.

---

