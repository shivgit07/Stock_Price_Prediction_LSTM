# Stock_Price_Prediction_LSTM
This is my project on Stock price Prediction which contains the code for a comprehensive stock price prediction and trading system implemented using LSTMs, PyTorch and deep learning techniques. The system aims to predict future stock prices or changes in prices and make trading decisions accordingly.
<br>
I have used the `sp500_tickers_A-D_1min_1pppix` data set for this project.
<br>
### Features:

1. **Data Visualization**: The system allows for visualizing minute-by-minute and day-by-day closing price series of selected stocks, as well as complete candlestick charts with volume.

2. **Data Normalization**: Various methods for normalizing stock prices and volumes over time and across companies have been implemented, ensuring robust model training.

3. **Scenario Decisions**: The system supports different trading scenarios including high-frequency trading, intra-day swing, inter-day trade, or long-term investment. It also considers factors such as buy-ask spread and trade commissions.

4. **LSTM Model Definition**: PyTorch modules are provided for defining LSTM models, with flexibility to adjust input dimension, number of units, and layers.

5. **Data Loader**: A flexible data loader is implemented for training the LSTM model, especially suitable for high-frequency data. It accepts inputs such as open, close, high, low, and volume of one or more stocks.

6. **Model Training**: The system allows for training or pre-training the LSTM model to predict future prices or changes in prices, with a flexible future horizon (e.g., one minute or 10 minutes into the future).

7. **Trading Module**: A trading module is set up to make logical decisions on buying, holding, or selling stocks based on the predictions generated by the LSTM model and considering factors like bid-ask spread and commissions.
