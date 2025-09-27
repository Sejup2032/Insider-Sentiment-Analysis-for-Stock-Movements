# Insider-Sentiment-Analysis-for-Stock-Movements
# 📰 Stock Market Sentiment Analysis Dashboard

This project analyzes the relationship between **news headlines sentiment** and **stock market performance**.  
It uses news data from multiple sources (CNBC, Guardian, Reuters) and stock price data from **Yahoo Finance**.

---

## 📊 Overview

The project performs the following steps:
1. **Collects News Data**  
   - Sources: CNBC, Guardian, and Reuters  
   - Cleans text data (removes stopwords, punctuation, converts to lowercase)

2. **Performs Sentiment Analysis**  
   - Uses `TextBlob` to calculate sentiment polarity scores  
   - Classifies headlines into: **Positive**, **Negative**, or **Neutral**

3. **Fetches Stock Data**  
   - From Yahoo Finance using the `yfinance` library  
   - Matches each news date with the stock's closing price

4. **Analyzes Relationship**  
   - Calculates **next-day stock price change**
   - Merges stock and news data for correlation analysis

5. **Visualizes Results**  
   - Sentiment distribution  
   - Average next-day stock change by sentiment  
   - Sentiment trend over time  
   - Combined stock price and sentiment plot  
   - Sentiment score density plot  

---

## 🧠 Tools & Libraries

| Library | Purpose |
|----------|----------|
| `pandas` | Data cleaning and merging |
| `numpy` | Numerical operations |
| `matplotlib` | Visualization |
| `seaborn` | Stylish visualizations |
| `textblob` | Sentiment analysis |
| `yfinance` | Stock data download |
| `nltk` | Text preprocessing |

---

## 📈 Dashboard Preview

The dashboard includes:
- **Sentiment Distribution:** Bar plot showing counts of Positive, Neutral, and Negative headlines  
- **Average Next-Day Change:** Stock movement based on sentiment  
- **Sentiment Over Time:** Line plot showing how average sentiment varies  
- **Stock vs Sentiment:** Dual-axis line chart comparing stock prices and sentiment  
- **Sentiment Density:** Distribution curve of sentiment polarity  

---


