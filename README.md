# Trader Performance vs Market Sentiment (Hyperliquid)

## Project Overview
This project analyzes how market sentiment (Fear & Greed Index) relates to trader behavior and performance on Hyperliquid.  
The goal is to uncover behavioral patterns and propose data-driven trading strategies based on sentiment regimes.

The analysis focuses on:
- Trader performance (PnL, win rate)
- Behavioral changes (trade frequency, position size, leverage proxy)
- Segment-level differences (leverage, frequency)
- Simple predictive modeling for next-day profitability

---
## Environment Setup

### Requirements
- Python 
- pandas
- numpy
- matplotlib
- scikit-learn

---

## Reporsitory Structure

```
trader-performance-vs-sentiment/
│
├── README.md
│
├── data/
│   |
│   │── fear_greed.csv
│   │── hyperliquid_trades.csv
│  

│
├── notebooks/
│   └── trader_performance_vs_sentiment.ipynb
│
│
├── outputs/
│   ├── tables/
│   │   ├── winrate_by_sentiment.csv
│   │   ├── size_by_sentiment.csv
│   │   ├── leverage_segment_performance.csv
│   │   |── frequency_segment_performance.csv
|   |   |── consistency_segment_performance.csv
|   |   |── trades_count_by_sentiment.csv
│   │
│   └── charts/
│       ├── win_rate_by_sentiment.png
│       ├── size_by_sentiment.png
│       ├── trades_count_by_sentiment.png
│       └── pnl_by_sentiment.png
│
├── summary.md


