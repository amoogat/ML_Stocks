# ML_Stocks
This Repo uses Supervised ML to predict the price action of a stock. Starting with tickers imported from a stocks discord, the algorithm searches through all past trading history and creates columns that are likely to have impact on future price. Calculates popular technical indicators such as MACD, RSI, ATR ratio, etc. Currently, the code is ~85% accurate (see [Supersupervised.ipynb](https://github.com/amoogat/ML_Stocks/blob/main/Supersupervised.ipynb)). After finding support and resistance in 3 different ways, the algo puts together a summary chart for easy viewing (see [Summary](https://github.com/amoogat/ML_Stocks/blob/main/spreadsheets/Summary%2026-01-2021.xlsx)). 

# Coming soon:
- Pythonic notification through email when price drops under the support to a preferred buy zone, or rises above resistance to possible sell or gap up zone.
- Deployment to Heroku/ Flask.
- Adding pattern detection of things like wedges, double bottoms, morning/evening stars, etc.
