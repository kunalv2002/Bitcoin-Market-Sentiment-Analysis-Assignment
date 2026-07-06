
# Bitcoin Market Sentiment and Trader Performance Analysis

## 📌 Project Overview
This project analyzes the relationship between Bitcoin market sentiment and trader performance using:

1. Historical trading data from Hyperliquid
2. Bitcoin Fear & Greed Index data

The objective is to identify how different market sentiments (Fear, Greed, Extreme Fear, Extreme Greed, and Neutral) influence trading profitability and success rates.

---

## 🎯 Objectives

- Explore the relationship between market sentiment and trader performance.
- Measure profitability under different sentiment conditions.
- Calculate win rates across sentiment categories.
- Generate insights that can help build smarter trading strategies.

---
## 📂 Dataset Links

### Historical Trader Data
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

### Bitcoin Fear & Greed Index
https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

## 📂 Datasets Used

### 1. Historical Trader Data
Contains:
- Account
- Coin
- Execution Price
- Size Tokens
- Side
- Timestamp
- Closed PnL
- Fees
- Order ID
- Trade ID

### 2. Bitcoin Fear & Greed Index
Contains:
- Date
- Classification
- Sentiment Value

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- GitHub

---

## 🔄 Project Workflow

1. Data Loading
2. Data Cleaning
3. Date Conversion
4. Dataset Merging
5. Handling Missing Values
6. Exploratory Data Analysis
7. Profitability Analysis
8. Win Rate Analysis
9. Visualization
10. Business Insights and Conclusions

---

## 📊 Key Findings

### Average Profit by Market Sentiment

| Sentiment | Average Closed PnL |
|------------|-------------------|
| Extreme Greed | 67.89 |
| Fear | 54.29 |
| Greed | 42.74 |
| Extreme Fear | 34.54 |
| Neutral | 34.31 |

### Win Rate by Market Sentiment

| Sentiment | Win Rate (%) |
|------------|---------------|
| Extreme Greed | 46.49 |
| Fear | 42.08 |
| Neutral | 39.70 |
| Greed | 38.48 |
| Extreme Fear | 37.06 |

### Total Profit by Market Sentiment

| Sentiment | Total Profit |
|------------|-------------|
| Fear | 3,357,155 |
| Extreme Greed | 2,715,171 |
| Greed | 2,150,129 |
| Neutral | 1,292,921 |
| Extreme Fear | 739,110 |

---

## 💡 Insights

- Fear periods generated the highest cumulative profits.
- Extreme Greed periods achieved the highest average profit and win rate.
- Market sentiment significantly impacts trading outcomes.
- Combining sentiment indicators with trading strategies can improve decision-making.

---

## 📁 Repository Structure

```text
bitcoin-sentiment-trader-analysis/
│
├── Trader_Sentiment_Analysis.ipynb
├── report.pdf
├── README.md
```

---

## 🚀 Future Improvements

- Machine Learning based profit prediction.
- Sentiment forecasting using social media data.
- Trading strategy backtesting.
- Multi-cryptocurrency sentiment analysis.

---

## 👨‍💻 Author

**Kunal Kargwal**  
B.Tech – Artificial Intelligence and Data Science  
Vivekananda Global University, Jaipur

---

## 🔗 Submission

This repository contains the complete notebook, analysis, visualizations, and report for the Primetrade.ai Data Science Internship Assignment.
