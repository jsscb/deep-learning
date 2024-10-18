# Stock Price Prediction using LSTM and GRU
## Project Overview
This project focuses on predicting the stock prices of Facebook and IBM using deep learning techniques. The datasets used consist of historical stock data, and the experiment used different architectures, such as **LSTM** (Long Short-Term Memory) and **GRU** (Gated Recurrent Units), to capture temporal dependencies.

## Datasets
**FB.csv**: Facebook stock prices from May 18, 2012, to April 1, 2020.

**IBM.csv**: IBM stock prices from January 2, 1962, to April 1, 2020.

## Model Performance
**Facebook:**
RMSE, MAE, and MAPE showed slight variations across architectures, with GRU performing slightly better in terms of MAPE.
**Best Accuracy:** 89% with the LSTM baseline model.
**IBM:**
The IBM dataset showed overfitting in modified architectures, suggesting that further tuning is needed.
**Best Accuracy:** 87% with the LSTM baseline model.

## Conclusion
The LSTM and GRU models demonstrated solid performance in predicting stock prices, with the GRU providing comparable accuracy while maintaining stable training. The LSTM baseline model performed best, achieving up to 89% accuracy for Facebook stock predictions.
