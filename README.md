# Financial News Sentiment Analyser

Built a Python project to analyse how financial news sentiment correlates 
with Nifty 50 stock movements.

Pulled 50 live headlines using NewsAPI, scored them using NLP (TextBlob), 
and merged the results with daily Nifty 50 price data from yfinance. 
Visualised the relationship using a dual-axis Matplotlib chart.

**Results:** 50% Neutral, 38% Positive, 12% Negative sentiment. 
Negative sentiment days generally aligned with market dips.

**Tools:** Python, Pandas, TextBlob, yfinance, Matplotlib, NewsAPI

