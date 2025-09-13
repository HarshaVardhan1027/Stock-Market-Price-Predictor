# Stock Price Predictor (LSTM)

A Python-based tool to forecast stock prices for Indian stocks using **LSTM**.  
Users can enter a stock name or symbol and the number of days to forecast. The tool predicts realistic stock prices using **log-returns** to avoid unrealistic spikes.

## Features
- Predicts next N days of stock prices
- Uses 5 years of historical data from Yahoo Finance
- LSTM model trained on log-returns for stable predictions
- Plots historical and forecasted prices
- Outputs forecast rounded to 2 decimal places
