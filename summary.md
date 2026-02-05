
---

#  Summary


## Methodology

The analysis combines daily market sentiment data with trade-level Hyperliquid data. Trader executions were aggregated to a daily level and aligned with the Fear & Greed Index. Sentiment was categorized into Fear, Neutral, and Greed regimes using standard thresholds.

Key performance metrics included daily PnL and win rate, while behavioral metrics captured trade frequency, average trade size (used as a leverage proxy), and directional bias. Traders were further segmented into high vs low leverage and frequent vs infrequent groups to examine heterogeneous responses to sentiment. A simple logistic regression model was also used to test whether sentiment and behavior could predict next-day profitability.

---

## Key Insights

1. **Performance varies by sentiment, but not linearly**  
   Win rates are highest during Greed, yet higher accuracy does not consistently translate into better profitability. Loss magnitude and volatility play a larger role than win rate alone.

2. **Behavior changes significantly with sentiment**  
   Fearful markets trigger higher trade frequency and larger position sizes, indicating stress-driven activity. Greedy markets are characterized by smaller, more selective trades. Directional bias remains structurally long across all regimes.

3. **Trader style moderates sentiment impact**  
   Frequent traders using smaller position sizes consistently outperform infrequent traders. High leverage strategies perform best during neutral sentiment and deteriorate during extreme optimism.

4. **Predictability is asymmetric**  
   A simple predictive model shows that profitable days are more predictable than losing days, suggesting downside risk is driven by external shocks not captured by sentiment alone.

---

## Strategy Recommendations

- **Execution Strategy:**  
  During Neutral and Greed periods, favor higher trade frequency with smaller position sizes. Avoid large, infrequent trades during Fear unless supported by strong conviction and strict risk controls.

- **Leverage Management:**  
  Deploy higher leverage primarily in Neutral markets. Reduce leverage exposure during Fear and Greed, when volatility and crowded positioning increase drawdown risk.

---

## Conclusion

Market sentiment meaningfully influences how traders behave, but performance outcomes depend more on execution style and risk management than on sentiment alone. Disciplined, frequent trading with controlled position sizing proves more resilient across sentiment regimes than aggressive, high-risk strategies.
