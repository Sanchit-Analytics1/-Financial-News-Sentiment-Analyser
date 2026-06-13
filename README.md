# Financial News Sentiment Analyser

Analysed 50 financial news headlines using NLP and mapped sentiment scores 
against Nifty 50 daily price movements to identify correlations.

## Tools Used
Python | Pandas | TextBlob | yfinance | Matplotlib | NewsAPI

## What I Built
- Fetched live financial news headlines using NewsAPI
- Scored each headline as Positive / Negative / Neutral using TextBlob (NLP)
- Pulled Nifty 50 historical data using yfinance
- Merged sentiment scores with daily stock price % change
- Built a dual-axis chart showing sentiment vs market movement

## Key Findings
- Negative sentiment days correlated with Nifty downward movement
- 50% Neutral | 38% Positive | 12% Negative headlines overall
- High positive sentiment days generally aligned with green market days

## Files
- `sentiment_analyser.ipynb` — main Python notebook
- `sentiment_vs_nifty.png` — chart output  
- `sentiment_nifty_analysis.csv` — merged dataset

