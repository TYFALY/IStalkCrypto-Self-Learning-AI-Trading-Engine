# 🤖 IStalkCrypto: Self-Learning AI Trading Engine

![Status](https://img.shields.io/badge/Status-Live-green)
![Category](https://img.shields.io/badge/Category-Algorithmic--Trading-blue)
![Logic](https://img.shields.io/badge/Logic-ML--Linear--Regression-orange)

**IStalkCrypto** is a professional-grade AI trading signal engine built in Python. Unlike standard "buy/sell" indicators, this system uses a weighted machine learning model and real-time sentiment analysis to identify high-probability entries while prioritizing capital preservation.

---

## 🧠 The Logic
The engine utilizes a **Weighted Linear Regression** model that prioritizes recent price action (last 24h) while cross-referencing:
* **Relative Strength Index (RSI)** for overbought/oversold conditions.
* **SMA 50** for trend confirmation.
* **Google News RSS Sentiment Analysis** to detect market-moving news before the price reacts.

### 🛡️ Capital Preservation Mode
The bot features a **0.75 Confidence Threshold**. If the AI "certainty" is below this level, the bot remains in **⚖️ HOLD**. This protected our users during the recent New Year volatility, avoiding "fake-out" pumps and unnecessary exchange fees.

---

## 📈 Track Record (Dec 2025 - Jan 2026)
* **Dec 26:** Successfully flagged `PRO SELL` at **$87,034** (Market Top).
* **Dec 27 - Jan 2:** Maintained **⚖️ HOLD** status during holiday sideways chop.
* **Status:** Currently outperforming manual "hope-based" trading strategies.

---

## 🚀 Get the Alpha
There are two ways to access the IStalkCrypto technology:

### 1. Own the Source Code ($49)
Get the full Python source code. No monthly fees. Run it on your own machine.
👉 [**Buy Source Code on Whop**](https://whop.com/istalkcrypto/istalkcrypto-python-autobot/)

### 2. Join the Signal Alpha ($19/mo)
Don't want to code? Get the AI's real-time signals delivered directly to your Telegram 24/7.
👉 [**Join the Signal Channel**](https://whop.com/istalkcrypto/istalkcrypto-ai-signal-alpha/)

---

## 🛠️ Requirements (For Source Code users)
* Python 3.10+
* Dependencies: `pandas`, `yfinance`, `textblob`, `numpy`, `scikit-learn`, `requests`

---

## ⚖️ Legal Disclaimer
*This software is for educational purposes only. Cryptocurrency trading involves high risk. Past performance is not indicative of future results.*

**Developed by IStalkCrypto. Logic over luck. 💅**
