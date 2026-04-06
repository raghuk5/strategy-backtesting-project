# 📊 Strategy Building & Backtesting Project

## 🚀 Overview
This project implements a trading strategy based on the 50 EMA (Exponential Moving Average) using Python. It includes risk management, backtesting, and performance analysis.

## 📌 Strategy Logic
- Buy when Close Price > 50 EMA
- Exit only via:
  - Stop Loss
  - Target (No EMA exit)

## 💰 Risk Management
- 1% capital risk per trade
- Risk-Reward Ratio: 1:2
- Dynamic position sizing

## 📊 Data Source
- Yahoo Finance API (yfinance)
- NIFTY 50 historical data

## 📈 Results
- Equity curve shows consistent growth
- Controlled drawdown
- Strategy tested on 3 years data

## 📷 Output Graphs
- Price vs EMA
- Buy/Sell signals
- Equity Curve

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- yfinance

## ▶️ How to Run
```bash
pip install yfinance pandas numpy matplotlib
python Strategy_Builder_project.py
