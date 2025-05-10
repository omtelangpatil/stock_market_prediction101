# 📈 Stock Market Prediction 101

**Predicting stock prices for upcoming days with the help of machine learning and sentiment analysis.**

---

## 🧐 Project Overview

This project demonstrates how to build a simple yet effective stock price prediction pipeline using:

1. **Historical price data** (e.g., OHLCV from Yahoo Finance)  
2. **Twitter sentiment analysis** to gauge market mood  
3. **Machine learning models** to forecast next-day closing prices  

All steps are contained within a Jupyter Notebook for easy exploration and learning.

---

## 🚀 Key Features

- **Data Collection**  
  - Fetches historical stock data via `yfinance`  
  - Pulls tweets mentioning your target ticker using the Twitter API

- **Sentiment Analysis**  
  - Cleans and preprocesses tweet text  
  - Uses a pre-trained model (e.g., `TextBlob` or `VADER`) to score sentiment  

- **Feature Engineering**  
  - Creates technical indicators (MA, RSI, MACD, etc.)  
  - Merges sentiment scores with price features

- **Modeling & Evaluation**  
  - Trains regression models (e.g., Random Forest, Linear Regression, LSTM)  
  - Splits data into train/test sets, evaluates MAE/RMSE  
  - Visualizes actual vs. predicted prices

---

## 🛠️ Tech Stack & Dependencies

- **Language**: Python 3.8+  
- **Notebook**: Jupyter  
- **Core Libraries**:  
  - `pandas`, `numpy`  
  - `scikit-learn`, `tensorflow` (or `keras`)  
  - `yfinance` for price data  
  - `tweepy` / `snscrape` for Twitter data  
  - `TextBlob` / `NLTK` / `VADER` for sentiment  

> **Tip:** It’s best practice to install these in a virtual environment.

---

## 📦 Installation & Setup

1. **Clone the repo**  
   ```bash
   git clone https://github.com/omtelangpatil/stock_market_prediction101.git
   cd stock_market_prediction101
