# BTC Price Prediction using LSTM

This project predicts future Bitcoin (BTC) prices using a Long Short-Term Memory (LSTM) neural network. The model is trained on historical BTC price data fetched from the CoinGecko API. It can predict BTC prices for the next 10 days (hourly predictions).

## Project Overview

- **Fetch BTC Data:** Historical BTC prices are fetched from the CoinGecko API.
- **Preprocess Data:** The data is normalized and split into training and testing sets.
- **Build and Train Model:** An LSTM model is trained on the preprocessed data.
- **Predict Future Prices:** The model predicts future BTC prices for the next 10 days.
- **Visualization:** The historical, validation, and predicted future prices are plotted for visualization.

## Requirements

- Python 3.6+
- TensorFlow 2.x
- Pandas
- NumPy
- scikit-learn
- Matplotlib
- Requests

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/btc-price-prediction.git
   cd btc-price-prediction
