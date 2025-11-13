# GenAI-Stock-Insight-Strategy-Copilot

An AI-powered financial analysis tool that combines **real-time stock data**, **technical indicators**, **strategy backtesting**, and an optional Generative AI layer to produce simple, human-readable insights about market trends, risk, and trading performance.

This project demonstrates how Finance + Python + GenAI-style workflows can be used together in a practical, end-to-end pipeline. When no API key is configured, it falls back to a rule-based explanation (offline mode), so everything runs without external services.

- ✨ Features

- 🔹 Fetches recent stock data using `yfinance`
- 🔹 Computes technical indicators:
  - SMA-20  
  - SMA-50  
  - Daily returns
- 🔹 Implements a **momentum strategy** (SMA20 > SMA50) with backtesting
- 🔹 Calculates important risk metrics:
  - Volatility  
  - Max drawdown  
  - Sharpe ratio  
- 🔹 Generates an explanation of trend, risk, and strategy performance
  - Offline rule-based summary (no API key required)
- 🔹 Visualizes stock price trends and strategy vs buy-and-hold curves

---

## 🧠 Project Workflow
Data Fetching → Indicator Calculation → Strategy Backtesting →
Risk Metrics → Explanation Generation → Visualization

---

## 🛠 Tech Stack

- Python  
- Pandas  
- yfinance  
- Matplotlib  
- (Optional) OpenAI / Gemini for real LLM integration  
- Google Colab / Jupyter Notebook


## 🚀 How to Run
1. Open the notebook in Google Colab  
2. Set your stock ticker (ex: `"AAPL"` )  
3. Run all cells  
4. View metrics, charts, and offline explanation  

---

## 📂 Files
- `GenAI_Stock_Insight_Copilot.ipynb`
- `README.md`


---

## ⚠️ Note
No API key required — project works fully in offline explanation mode.

---

## 📜 Disclaimer
For educational use only. Not financial advice.



