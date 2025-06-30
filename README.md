This project implements an LSTM (Long Short-Term Memory) model to predict stock price movements using historical data and technical indicators. Indicators such as RSI, CCI, VWAP, and ROC are used to generate trading signals, which serve as inputs for training the model.

Data Loading & Preprocessing:
Historical stock data is sourced from Yahoo Finance. Technical indicators are computed, and trading signals are generated. Indicator columns are removed to prevent data leakage. The data is then split into training and testing sets, and normalized using MinMaxScaler.

Model Architecture:
An LSTM model is built using TensorFlow/Keras, featuring LSTM layers and Dropout for regularization. The model is trained to learn patterns in price movement.

Evaluation Metrics:

Sharpe Ratio: Evaluates risk-adjusted return.

RMSE: Measures prediction error.

Correlation: Analyzes the relationship between actual and predicted prices.
