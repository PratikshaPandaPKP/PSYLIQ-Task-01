The task involved predicting the stock price of Netflix using LSTM in Python. The process included:

1. **Data Exploration**:
   - Libraries were imported, and Netflix stock data was loaded from Yahoo Finance.
   - The shape, dimensions, and descriptive statistics of the data were analyzed to ensure data integrity.

2. **Data Visualization**:
   - Stock price trends were visualized using Plotly Express, depicting closing prices and average OHLC values.

3. **Data Preprocessing**:
   - OHLC averages were calculated, and the data was normalized between 0 and 1.
   - The data was split into training and testing sets for LSTM modeling.

4. **Modeling**:
   - An LSTM model with two LSTM layers and one dense output layer was constructed.
   - The model was compiled with a mean squared error loss function and Adam optimizer.
   - The model was trained on the training data for 50 epochs, achieving low training loss.

5. **Prediction**:
   - The trained model was used to predict future stock prices based on test data.
   - Model performance was evaluated using root mean square error (RMSE).
   - Predicted prices were compared with actual test data through visualization, showing a close alignment.

Overall, the LSTM model effectively predicted Netflix stock prices, offering insights into potential future trends.

**Video Link:-** https://www.loom.com/share/18466b81a74f417e813c9a86da8d56f2?sid=3373dcd5-5e33-4f86-aafe-975d52adba57
