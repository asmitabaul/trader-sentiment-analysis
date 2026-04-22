# Trader Behavior vs Market Sentiment Analysis

## Objective
This project analyzes how market sentiment (Fear vs Greed) influences trader behavior and performance. The aim is to identify patterns in profitability, trading activity, and risk-taking, and derive data-driven strategies.

---

## Dataset
- Historical trading data containing PnL, trade size, and timestamps  
- Fear & Greed Index representing market sentiment

## Data

Dataset is not included due to size constraints.  
To run the notebook, place the required CSV files in the project directory. 

---

## Methodology (Summary)

- Converted trade-level data into daily metrics (PnL, win rate, trade size, trading frequency)
- Engineered behavioral features such as long ratio and PnL volatility
- Merged trading data with sentiment data using date alignment
- Performed:
  - Sentiment-based analysis
  - Behavioral analysis
  - Correlation analysis
  - Trader segmentation

---

## Key Insights

- Fear conditions produce the highest average PnL (~48k) but with high volatility  
- Extreme Greed results in very low profitability (~2.7k) despite optimistic sentiment  
- Trading activity increases during fear, while trade size increases during greed  
- High-activity traders achieve higher returns but with significantly higher risk  
- Smaller traders outperform larger traders in both profitability and efficiency  

---

## Strategy Recommendations

- Reduce exposure during Extreme Greed to avoid overconfidence-driven losses  
- Increase participation during Fear while maintaining risk control  
- Prefer smaller position sizes in volatile conditions  
- Balance high-risk and stable trading strategies  

---

## Bonus: Predictive Modeling

A logistic regression model was used to predict next-day profitability.

- Accuracy: ~68%  
- The model predicts all days as profitable and fails to identify loss-making days  
- This indicates class imbalance and limited predictive power  

Conclusion:  
Behavioral features are more useful than sentiment alone, and simple models are insufficient for reliable financial prediction.

---

## How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook PT_ai.ipynb
