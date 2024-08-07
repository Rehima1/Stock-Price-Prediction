# Stock Price Prediction Model Performance Analysis

## Project Overview
This project focuses on developing and evaluating a model to predict Meta Inc.'s stock prices based on historical data. The model is trained on past stock price data and evaluated on how well it can predict future prices, with a specific focus on understanding its performance across different data splits (training, validation, and test).

## Dataset
The dataset used in this project consists of historical stock prices, which are split into training, validation, and test sets, the dataset can found [here](https://finance.yahoo.com/quote/META/history/?period1=1337347800&period2=1723021946)

## Python packages
matplotlib
pandas
numpy
scikit-learn
tensorflow

## Model
The model used for this project is a Long Short-Term Memory (LSTM) network.
Objective: To predict future stock prices of Meta Inc. based on past trends.
Features: Date, Close

## Result

### Training Data
The model accurately captured the trends in the training data, with predictions closely matching actual Meta stock prices.
![image](https://github.com/user-attachments/assets/4af15b12-87c7-4d3e-9ead-c6378eee9215)


### Validation Data
The model performed well on the validation data, indicating that it generalized effectively to new data.
![image](https://github.com/user-attachments/assets/f69da7b4-2aa3-45ed-a039-516fb3a4f7d4)


### Test Data
On the test data, the model followed the general trends in Meta stock prices, though there were some deviations during periods of high volatility.

## Conclusion
The LSTM-based Apple stock price prediction model shows strong performance in capturing long-term trends but has some limitations in predicting short-term fluctuations, particularly during volatile periods. This suggests the model can be a useful tool for trend-following strategies but might need further refinement for short-term trading applications
