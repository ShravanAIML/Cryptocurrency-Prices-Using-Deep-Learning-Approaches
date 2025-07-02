# Cryptocurrency-Prices-Using-Deep-Learning-Approaches
**Dataset Description: XRP Price Data**
This dataset contains historical pricing data for XRP (Ripple), a popular cryptocurrency. It includes daily market performance data, such as opening and closing prices, trading volume, and price fluctuations. The data can be used for time-series analysis, financial modeling, and predictive analytics in cryptocurrency markets.
Dataset Features
The dataset includes the following columns:
    Date: The date the data corresponds to (in YYYY-MM-DD format).
          Date Range: 01-01-2020 to 30-03-2024.
    Price: The closing price of XRP on the specific date (in USD).
    Open: The opening price of XRP at the start of the trading day (in USD).
    High: The highest price XRP reached during the day (in USD).
    Low: The lowest price XRP reached during the day (in USD).
    Vol.: The total trading volume of XRP for the day (in XRP units).
    Change %: The percentage change in the closing price of XRP from the previous day.

**In this project,The following deep learning models for predicting the XRP price:**

    LSTM (Long Short-Term Memory): A type of recurrent neural network (RNN) designed to capture long-term dependencies in time-series data, making it suitable for predicting cryptocurrency prices based on historical data.

    GRU (Gated Recurrent Unit): A simpler variant of LSTM that performs similarly in sequence prediction tasks but with fewer parameters, allowing for faster training.

    BiLSTM (Bidirectional LSTM): A variant of LSTM that processes the data in both forward and backward directions, capturing both past and future context, which improves prediction accuracy in certain time-series tasks.

    LSTM + GRU: A hybrid model that combines the strengths of both LSTM and GRU units to enhance prediction performance.    

![image](https://github.com/user-attachments/assets/c177b20a-561d-438a-90f0-26b7123060a0)

LSTM + GRU appears to perform the best across all three error metrics (RMSE, MAE, and MAPE). This model consistently shows the lowest error values for both MAE and MAPE, indicating that it has a better overall prediction accuracy compared to the other models. While the RMSE value for this model is not the lowest, it is still relatively competitive compared to the other models. Therefore, LSTM + GRU is likely the most balanced and effective model in terms of minimizing error.
