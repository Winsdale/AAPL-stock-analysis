README template 
# AAPL Stock Price & Volume Analysis

## 1. Problem & User
This project analyzes Apple Inc. (AAPL) one-year stock price and trading volume trends, to help understand its price movements and market activity.

## 2. Data
- **Source**: Historical stock data CSV from Yahoo Finance
- **Access Date**: April 2026
- **Key Fields**: Date, Open/High/Low/Close prices, Volume

## 3. Methods
1.  Load and clean CSV data (remove `$` symbols, convert date format)
2.  Calculate daily returns and moving averages (MA5, MA20)
3.  Visualize price trend with moving averages
4.  Plot daily trading volume
5.  Generate summary statistics

## 4. Key Findings
- The stock rose steadily from mid-2025 to late 2025, peaking at ~$286
- Moving averages show clear upward momentum in the growth phase
- Trading volume spiked around key price peaks, indicating increased market activity
- The stock saw moderate volatility in early 2026, but remained above $250
- The average daily return over the period was positive (~0.13%)

## 5. How to run
1.  Clone the repository
2.  Ensure `pandas` and `matplotlib` are installed
3.  Open `AAPL analysis.ipynb` in Jupyter Notebook
4.  Run all cells to reproduce the analysis and charts

## 6. Product link / Demo
GitHub repository: https://github.com/Winsdale/AAPL-stock-analysis

## 7. Limitations & next steps
- The analysis does not include fundamental factors (e.g., earnings reports)
- No predictive modeling was performed
- Next steps could include adding Bollinger Bands or volume-based indicators
