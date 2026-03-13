# Trader Performance vs Market Sentiment Analysis

## Objective
This project analyzes the relationship between Bitcoin market sentiment (Fear vs Greed) and trader behavior on the Hyperliquid platform. The goal is to understand how sentiment impacts trading activity and profitability.

## Datasets
1. Bitcoin Fear and Greed Index dataset
2. Hyperliquid historical trader dataset containing trade information such as account, trade size, direction, and closed PnL.

## Methodology
Both datasets were cleaned and processed using Python. Timestamps were converted and aligned by date. The sentiment dataset was merged with trader activity data to analyze how market sentiment influences trading behavior and performance.

Key metrics analyzed:
- Profit and Loss (PnL)
- Trade frequency
- Position size
- Long vs Short ratio

Visualization techniques were used to compare trader behavior during Fear vs Greed market conditions.

## Key Insights
1. Trading activity tends to increase during Greed sentiment periods.
2. Larger position sizes are often observed during Greed market conditions.
3. Profit and loss variability appears higher during Fear periods, indicating unstable market behavior.

## Strategy Recommendations
1. Traders should reduce leverage and position size during Fear sentiment periods to minimize risk.
2. During Greed sentiment periods, traders may increase trade frequency to capitalize on momentum.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
