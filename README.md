# Stock_Price_Prediction
Stock Price Prediction Using LSTM

In this project, we employ Long Short-Term Memory (LSTM), a deep learning model, to forecast stock prices. The project is implemented in Python, making use of the Keras library for model creation and training. Here's an outline of the project:

•	Data Retrieval: We commence by importing historical stock price data from a CSV file.

•	Data Preprocessing: The data is thoroughly examined and preprocessed. This includes scaling the data to a range between 0 and 1, enhancing the model's performance.

•	Model Construction: The core of the project revolves around a neural network composed of four LSTM layers, augmented by dropout layers. These layers are meticulously designed to capture and learn intricate patterns within the stock price data.

•	Training: The model is trained using a segment of the data, specifically the initial 70%, to acquire the knowledge required for making predictions.

•	Testing and Prediction: The remaining 30% of the data is reserved for testing the model's performance. This is where the model predicts stock prices.

•	Assessment: We evaluate the model by comparing its predictions with the actual stock prices and generate visual representations to gauge the model's accuracy.

This project serves as a showcase of how advanced deep learning techniques can be harnessed to predict stock prices based on historical data. 

