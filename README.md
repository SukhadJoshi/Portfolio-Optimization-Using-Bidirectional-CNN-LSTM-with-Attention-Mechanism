# Portfolio-Optimization-Using-Bidirectional-CNN-LSTM-with-Attention-Mechanism

This project utilized a CNN-LSTM bi-directional model with an attention mechanism to predict stock prices by analyzing historical data. The combination of convolutional layers and LSTM layers with attention allowed the model to identify patterns in the data and learn trends over time. Preprocessing techniques, such as normalization and feature scaling, ensured the data was prepared effectively for modeling. Metrics like moving averages and daily returns were used to extract meaningful insights from the data, aiding in the model's understanding of trends.
This work demonstrates the effectiveness of deep learning models for stock price prediction by uncovering patterns that traditional methods may not detect. It uses the Yahoo Finance API to collect stock data and applies advanced models like CNN-LSTM with attention mechanisms to improve accuracy.

## Data Source
- **Yahoo Finance API**: Historical stock data for AAPL and XLC.
- **Date Range**: October 31, 2023 - October 31, 2024.
- **Features**: Open, High, Low, Close, Adjusted Close, and Volume.

## Methods
- **Data Preprocessing**:
  - Fill missing data with forward-fill.
  - Normalize features using MinMaxScaler.
  - Use a 60-day look-back period for historical trends.
- **Model**:
  - Combined CNN for feature extraction and LSTM for time series analysis.
  - Used an attention mechanism to focus on key patterns.
  - Optimized using Adam and Mean Squared Error (MSE).

## Results
- **Performance**:
  - CNN-BiLSTM with Attention: MSE = 6.42 (best).
  - CNN-LSTM: MSE = 9.74.
  - SARIMA-CNN-LSTM: MSE = 38.53.
- **Visualizations**:
  - Line graphs showed predicted vs. actual prices.
  - Candlestick charts highlighted daily stock trends.
