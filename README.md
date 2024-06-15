# Computational Sequence Modelling - Analysis of Financial Time Series

This project focuses on analyzing and predicting stock values of various companies over a given duration using different time series models. The objective is to find an appropriate model for stock prediction, estimate the parameters, and compare the results with at least three different models. This analysis includes statistical tests and visualization to ensure robust model evaluation.

## Dataset

The dataset comprises stock prices of four major companies: Google (GOOG), Apple (AAPL), Microsoft (MSFT), and Amazon (AMZN), covering the period from August 1, 2014, to November 30, 2016.

## Objectives

1. Identify an appropriate model for predicting the stock prices of each company.
2. Estimate the parameters of the chosen models.
3. Compare the performance of different models.

## Methodology and Mathematical Background

### Methodology

Three different time series models were used to predict the stock prices:

- **LSTM (Long Short-Term Memory):** A type of recurrent neural network (RNN) designed to capture long-range dependencies in time series data.
- **GRU (Gated Recurrent Unit):** Another type of RNN similar to LSTM but with a simpler architecture.
- **ARIMA (Autoregressive Integrated Moving Average):** A statistical model commonly used for time series forecasting.

### Mathematical Background

1. **Closing Price:** The last price at which a stock trades during a regular trading session. It is crucial for trend identification and volatility assessment.
2. **Moving Average:** Used to smooth out fluctuations in time series data and identify trends. Helps in understanding the overall direction of stock prices.
3. **Trade Volume:** Represents the total number of shares traded in a given period, providing insights into market activity. Often used with price data to confirm trends or identify potential reversals.

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/angadbawa/Stock-Market-Price-Prediction
    cd Stock-Market-Price-Prediction
    ```

2. Create and activate the environment:
    ```bash
    conda create -n stock python=3.9
    conda activate stock
    ```

3. Install the requirements:
    ```bash
    pip install -r requirements.txt
    ```
