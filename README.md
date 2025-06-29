# Raise The Stakes 

## Team Members
- **Chinmay Agarwal** - 23BCE0715  
- **Veeksha Anne** - 24BCE0628  
- **Mahalakshmi Manikandan** - 24BEE0093  

---

## Problem Statement
Investing in the stock market is risky due to its unpredictable nature. Our project leverages Machine Learning to assist users in making better stock decisions by analyzing the last 10 minutes of market data.

---

## Goal
Help investors and stock market enthusiasts make **smarter, more informed trading decisions** using real-time ML predictions.

---

## How It Works

### 1. **Data**
- Collects data from the **National Stock Exchange (NSE) and other historical data extraction sites** at second-level intervals.
- Extracts financial indicators such as:
  - Momentum
  - LFV (Liquidity, Flow, Volume)
  - Volatility Index (VIX)
  - Market Sentiment

### 2. **LSTM**
- **LSTM** for short-term trend analysis predictions:
    - RaiseTheStakes_LSTM: Using LSTM for price prediction:
        - For the dataset :0941.HKHKD_Candlestick_1_s_BID_16.06.2025-16.06.2025.csv
        - Which can be downloaded from https://www.dukascopy.com/trading-tools/widgets/quotes/historical_data_feed
    - LSTM2: Adding droupout layer in LSTM & training on a bigger dataset

### 3. **Reinforcement Learning(DQN) + LSTM hybrid**
- Model acts as an agent that:
  - **-1** = Short (predicts price fall)
  - **0** = Hold
  - **1** = Long (predicts price rise)
- Agent receives rewards based on prediction accuracy.

### 3. **Multi Head Axial Attention**
- Minimizes a combined loss:
  - CNN
  - RNN
  - Multi head Attention


---

## 🔍 Similar Projects
- [pskrunner14/trading-bot](https://github.com/pskrunner14/trading-bot)

---
