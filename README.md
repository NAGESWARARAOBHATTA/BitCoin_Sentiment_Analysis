
# Bitcoin Sentiment and Trader Performance Analysis

This project investigates the relationship between *market sentiment* (Fear/Greed Index) and *trader performance* using historical trading data from Hyperliquid.

## Overview

The goal is to uncover hidden patterns and insights that can help build smarter trading strategies. We merge two datasets:
- *Bitcoin Market Sentiment* (Fear/Greed classification by date)
- *Historical Trader Data* (execution price, size, closed PnL, etc.)

## Key Objectives
- Analyze how market sentiment affects trader behavior and outcomes.
- Calculate win rates, average PnL, and trade volume across different sentiment conditions.
- Build a basic machine learning model to predict trade outcomes based on sentiment.

## Datasets
1. *Bitcoin Market Sentiment Dataset*
   - Columns: Date, Classification (Fear/Greed)

2. *Hyperliquid Historical Trader Data*
   - Columns: Execution Price, Size USD, Closed PnL, Side, Start Position, Fee, Timestamp, etc.

## Tools & Technologies
- Python (Pandas, NumPy, scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook

## Machine Learning
A Random Forest Classifier was trained using:
- Features: Sentiment (encoded), Size USD
- Target: Whether a trade is a win (Closed PnL > 0)

## Results
- Explored average closed PnL and win rates under Fear vs Greed sentiment
- Developed a classifier to predict trade outcome with accuracy insights

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/NAGESWARARAOBHATTA/BitCoin_Sentiment_Analysis.git
   cd BitCoin_Sentiment_Analysis
