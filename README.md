# Stock-Price-Prediction-using-LSTMs
This notebook implements a Long Short-Term Memory (LSTM) neural network for predicting stock prices based on historical data. It includes data loading, normalization, model training, and evaluation using Mean Absolute Error (MAE). The model is designed to forecast future stock prices effectively.


## LSTM Architecture Overview:
**Input Layer:** Accepts sequences of features (e.g., historical stock prices).

**LSTM Layers:** The model contains multiple LSTM layers, each capable of learning complex temporal patterns by retaining information over time. This is achieved through:

*Cell State:* Maintains a memory of previous inputs.</br>
*Forget Gate:* Decides what information to discard from the cell state.</br>
*Input Gate:* Determines what new information to store in the cell state.</br>
*Output Gate:* Controls the output of the LSTM layer.</br>
*Output Layer:* Produces the predicted stock price based on the learned patterns.</br>

The notebook includes data loading, preprocessing (such as normalization), model training, and evaluation using Mean Absolute Error (MAE) to assess performance. This approach allows for effective forecasting of future stock prices, leveraging the capabilities of LSTM networks to handle sequential data.
