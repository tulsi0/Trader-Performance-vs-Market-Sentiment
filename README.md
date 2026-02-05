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



trader-performance-vs-sentiment/
│
├── README.md
│
├── data/
│   ├── raw/
│   │   ├── fear_greed.csv
│   │   └── hyperliquid_trades.csv
│   │
│   └── processed/
│       ├── daily_trader_metrics.csv
│       ├── sentiment_labeled.csv
│       └── analysis_dataset.csv
│
├── notebooks/
│   └── trader_performance_vs_sentiment.ipynb
│
│
├── outputs/
│   ├── tables/
│   │   ├── win_rate_by_sentiment.csv
│   │   ├── trade_size_by_sentiment.csv
│   │   ├── trade_frequency_by_sentiment.csv
│   │   ├── leverage_segment_performance.csv
│   │   └── frequency_segment_performance.csv
│   │
│   └── charts/
│       ├── win_rate_by_sentiment.png
│       ├── trade_size_by_sentiment.png
│       ├── trades_per_day_by_sentiment.png
│       ├── leverage_vs_sentiment.png
│       └── frequency_vs_sentiment.png
│
├── report/
│   └── analysis_summary.md
│
├── requirements.txt
│
└── .gitignore
