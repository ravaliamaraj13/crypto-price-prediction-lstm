# crypto-price-prediction-lstm
“Bitcoin price forecasting using LSTM with Power BI visualizations”
 
 ## PROJECT OVERVIEW 

Cryptocurrency Price Forecasting using LSTM 
This project focuses on predicting the next 30 days of cryptocurrency prices like Bitcoin (BTC), Ethereum (ETH), Monero (XMR), Stellar (XLM), Bitcoin Cash (BCH), and Ripple (XRP) using LSTM (Long Short-Term Memory) deep learning model. All results are visualized using Power BI for better understanding and insights.

 ## FILES IN THE PROJECT

| File Name | Description |

| [`cryptocurrency_prediction.py`](./cryptocurrency_prediction.py) | Python script for data cleaning, LSTM training, and forecasting |
| [`bitcoin_future_predictions.csv`](./bitcoin_future_predictions.csv) | 30-day forecasted prices for Bitcoin |
| [`Dashboard.pbix`](./Dashboard.pbix) | Power BI dashboard showing historical and forecasted prices |
| [`coin_Bitcoin.csv`](./coin_Bitcoin.csv) | Historical Bitcoin price dataset |

 **Dataset Source**: [Click here to view the Kaggle dataset](https://www.kaggle.com/datasets/jessevent/all-crypto-currencies)

 
## PROJECT STEPS 
Data cleaning – removed missing or zero values and scaled prices properly.
Built the LSTM model – used the past 60 days’ prices to predict the next day.
Made 30-day future forecasts for each cryptocurrency.
All forecasts were saved in one file for easy use in Power BI.
Dashboard created to compare actual vs predicted prices.

 ## MODEL HIGHLIGHTS ## PROJECT STEPS 

- Preprocessed the data (scaling, shaping)
- Built LSTM model for time-series forecasting
- Evaluated predictions and plotted comparison graphs
- Saved future predictions to a CSV file

## POWER BI DASHBOARD 

Visualized: Historical price trend of Bitcoin  
-  Forecasted prices for the upcoming 30 days  
-  Actual vs Predicted comparison chart  
-  Price category classification (Low, Medium, High, Very High)  
-  Summary cards for maximum, minimum, and average prices  
“This dashboard presents 30-day forecasts for Bitcoin prices using LSTM. It compares predicted values with actual trends to provide valuable insights for future planning and crypto analysis.”

 ## HOW TO RUN 
1. Clone this repo
2. Run `bitcoin_model.ipynb` in Jupyter or Colab
3. This will generate the bitcoin_future_predictions.csv file.
4. Open Power BI Dashboard
Open Dashboard.pbix in Power BI Desktop
Refresh the data to view updated trends and forecasts

  ## FUTURE WORK 
Extend the model to other cryptocurrencies like ETH, XRP, etc.
Add real-time API integration for live updates
Enhance model performance using additional features (volume, sentiment, etc.)



