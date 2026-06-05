# Bitcoin Market Sentiment vs Trader Performance Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using historical cryptocurrency trading data and the Bitcoin Fear & Greed Index.

The objective is to understand how market sentiment influences trading profitability, trading behavior, and decision-making. By combining trader activity data with sentiment indicators, the project uncovers patterns that can help traders make more informed decisions and improve risk management strategies.

---

## Problem Statement

Financial markets are heavily influenced by investor psychology. In cryptocurrency markets, periods of fear and greed often drive trading decisions and market movements.

This project investigates the following question:

**How does Bitcoin market sentiment affect trader performance, profitability, and trading behavior?**

---

## Datasets Used

### 1. Historical Trader Data

Contains:

* Trader account information
* Cryptocurrency traded
* Trade direction (Buy/Sell)
* Trade size
* Execution price
* Transaction fees
* Closed Profit and Loss (PnL)

### 2. Bitcoin Fear & Greed Index

Contains:

* Daily sentiment score
* Sentiment classification

  * Extreme Fear
  * Fear
  * Neutral
  * Greed
  * Extreme Greed

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* GitHub

---

## Project Workflow

### 1. Data Loading

Loaded historical trading data and Fear & Greed Index datasets.

### 2. Data Cleaning

* Checked missing values
* Converted timestamps into a common date format
* Verified data consistency

### 3. Data Integration

Merged both datasets using the date field to associate each trade with the corresponding market sentiment.

### 4. Exploratory Data Analysis (EDA)

Analyzed:

* Trade count by sentiment
* Average profit by sentiment
* Win rate by sentiment
* Trade size analysis
* Fee analysis
* Buy vs Sell activity

### 5. Deep Analysis

Performed:

* Coin performance analysis
* Top trader analysis
* Profit distribution analysis
* Correlation analysis

### 6. Insight Generation

Derived actionable insights and trading strategy recommendations.

---

## Key Analyses Performed

### Trade Count by Sentiment

Analyzed how trading activity varies across different sentiment categories.

### Average Profit by Sentiment

Compared profitability during Fear, Greed, and Neutral market conditions.

### Win Rate Analysis

Measured the percentage of profitable trades under different market sentiments.

### Trade Size Analysis

Examined whether traders increase or decrease position sizes based on market sentiment.

### Fee Analysis

Studied transaction fee patterns across sentiment categories.

### Buy vs Sell Analysis

Compared buying and selling activity under different market conditions.

### Coin Performance Analysis

Identified the most profitable cryptocurrencies.

### Top Traders Analysis

Ranked traders based on cumulative profitability.

### Profit Distribution Analysis

Visualized profit and loss distributions to understand trading risk.

### Correlation Heatmap

Explored relationships between numerical trading variables.

---

## Key Findings

* Market sentiment significantly influences trader behavior.
* Profitability varies across different sentiment conditions.
* Trading activity changes during Fear and Greed periods.
* Certain cryptocurrencies consistently outperform others.
* A small group of traders contributes a significant share of overall profits.
* Sentiment indicators can provide valuable context for trading decisions.

---

## Trading Strategy Recommendations

1. Monitor market sentiment before entering trades.
2. Use sentiment indicators as an additional confirmation signal.
3. Avoid emotional decision-making during extreme market conditions.
4. Apply proper risk management and position sizing.
5. Combine sentiment analysis with technical and fundamental indicators.
6. Continuously evaluate performance under different market environments.

---

## Repository Structure

```text
Bitcoin-Market-Sentiment-Analysis/
│
├── Bitcoin_Sentiment_Analysis.ipynb
├── Report.pdf
├── README.md
│
└── images/
    ├── profit_by_sentiment.png
    ├── win_rate.png
    ├── top_traders.png
    ├── profit_distribution.png
    └── correlation_heatmap.png
```

---

## Conclusion

This project demonstrates how data analytics can be used to understand the relationship between market sentiment and trading performance. By combining trading data with sentiment indicators, valuable insights can be generated to support more informed trading decisions and better risk management practices.

---
<img width="1071" height="813" alt="Screenshot 2026-06-05 194321" src="https://github.com/user-attachments/assets/d2b751b2-af50-464f-902f-4296cf7e035e" />
<img width="1031" height="846" alt="Screenshot 2026-06-05 200917" src="https://github.com/user-attachments/assets/75d3b192-de77-420c-8691-b50e7024a42b" />
<img width="827" height="776" alt="Screenshot 2026-06-05 200947" src="https://github.com/user-attachments/assets/7b8c5269-1953-48bd-8cd1-55a0bf3cf504" />
<img width="1036" height="847" alt="Screenshot 2026-06-05 194331" src="https://github.com/user-attachments/assets/f6dc4631-ffb1-4f99-8531-80821a45323f" />
<img width="1274" height="850" alt="Screenshot 2026-06-05 194349" src="https://github.com/user-attachments/assets/1f6427e4-36ee-490c-b39e-ef650748ae65" />
<img width="1333" height="790" alt="Screenshot 2026-06-05 194403" src="https://github.com/user-attachments/assets/026eef1b-e7e9-4813-bb58-07c134b85370" />




## Author

**Sanjana K**

Bachelor of Engineering (BE)

Interested in Data Science, Analytics, Machine Learning, Artificial Intelligence, and Generative AI.

