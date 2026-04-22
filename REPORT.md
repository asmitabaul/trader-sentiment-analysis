# Trader Behavior vs Market Sentiment — Report

## Objective  
This study examines how market sentiment (Fear vs Greed) influences trader behavior and performance. The goal is to identify patterns in profitability, trading activity, and risk-taking, and derive actionable strategies.

---

## Methodology  

### Data Preparation  
Trading data was aggregated from transaction-level to daily-level metrics. Missing values and duplicates were removed, and timestamps were standardized.

### Feature Engineering  
Key features were constructed to capture both performance and behavior:
- Daily PnL  
- Win Rate  
- Average Trade Size  
- Trades per Day  
- Long Ratio  
- PnL Volatility (7-day rolling standard deviation)  

### Data Integration  
Trading data was merged with sentiment data using date alignment, enabling analysis across sentiment categories (Extreme Fear to Extreme Greed).

### Analytical Approach  
Performance and behavioral metrics were analyzed across sentiment conditions using statistical summaries and visualizations. Correlation analysis was used to understand relationships between variables.

### Segmentation  
Traders were segmented into:
- High vs Low Activity  
- Large vs Small Traders  
- Consistent vs Volatile Traders  

Each segment was analyzed independently and in relation to sentiment.

---

## Key Findings  

- Fear conditions produce the highest average profits (~48k) but also show high volatility  
- Extreme Greed leads to significantly lower profitability (~2.7k), indicating overconfidence  
- Trading frequency increases during fear, while trade size increases during greed  
- High-activity traders outperform but exhibit higher risk  
- Smaller traders demonstrate better efficiency than large traders  

---

## Strategy Recommendations  

- Reduce exposure during Extreme Greed to avoid overconfidence-driven losses  
- Increase participation during Fear while maintaining strict risk control  
- Prefer smaller position sizes in volatile conditions  
- Balance high-risk strategies with stable, consistent approaches  

---

## Conclusion  

Market sentiment influences trader behavior more than direct profitability.  
Disciplined and adaptive strategies that manage risk and avoid emotional decision-making lead to better trading outcomes.
