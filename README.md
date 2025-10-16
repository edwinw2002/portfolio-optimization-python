📈 Portfolio Optimization in Python

A concise implementation of Modern Portfolio Theory (MPT) to build an optimal portfolio that maximizes the Sharpe ratio using historical market data.
Inspired by Ryan O’Connell — Portfolio Optimization in Python.

⚙️ Overview

Fetches historical prices via yfinance

Computes log returns and covariance matrix

Uses SciPy’s SLSQP to maximize the Sharpe ratio

Visualizes optimal weights with a pie chart

Example Results:

Expected Annual Return: 14.62%

Annual Volatility: 14.24%

Sharpe Ratio: 0.82 (vs. S&P ~0.6, Bonds ~0.3–0.4)

🧠 Key Insight

A Sharpe ratio of 0.82 indicates solid risk-adjusted performance —
the portfolio earns 0.82 units of excess return for each unit of risk taken.

🛠️ Built With

Python · NumPy · Pandas · SciPy · Matplotlib · yfinance
