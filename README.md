# Trader Performance vs Market Sentiment Analysis

## Objective
Analyze how market sentiment (Fear/Greed) relates to trader behavior
and performance on Hyperliquid.

## Datasets
- Bitcoin Fear & Greed Index
- Hyperliquid historical trader data

## Methodology
- Performed data cleaning and validation
- Converted timestamps and aggregated trades at a daily trader level
- Attempted sentiment alignment at daily granularity
- Identified lack of temporal overlap between datasets
- Conducted trader performance and behavior analysis

## Key Insights
- Trader profitability is highly skewed, with a small subset of traders
  contributing most of the profits.
- Higher trading frequency does not guarantee better performance.
- Transaction fees materially impact net profitability.

## Notes
The provided sentiment dataset does not overlap temporally with the
trader dataset. The analytical framework remains valid and can be
directly applied when overlapping sentiment data is available.

## How to Run
1. Install Python 3.x
2. Install required libraries:
   pip install pandas numpy matplotlib seaborn
3. Run the Jupyter notebook.