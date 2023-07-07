# Stock-Price-Prediction-Meta
Stock Price Prediction
The Stock Price Prediction project focuses on predicting stock prices using historical stock data. It includes several steps, such as data fetching, data preprocessing, data visualization, model training, and evaluation.

# Data Fetching
The project uses the "yfinance" library to fetch historical stock data. The ticker symbol and date range are specified to retrieve the desired stock data.

# Data Preprocessing
Data preprocessing involves handling missing values, selecting relevant features, and performing feature scaling. Missing values are dropped, relevant features such as Open, High, Low, and Close prices are selected, and MinMax scaling is applied to normalize the data.

# Data Visualization
The project includes various visualizations to provide insights into the stock data. Line plots show the time series of closing, opening, high, and low prices. Histograms display the distribution of closing, opening, high, and low prices. Scatter plots depict the relationship between volume and closing, opening, high, and low prices.

# Model Training and Prediction
The project employs a Long Short-Term Memory (LSTM) model for stock price prediction. The model is built and trained using the preprocessed data. The training and test datasets are split, and the input data is reshaped for LSTM input. The model is trained on the training dataset and used to predict stock prices for the test dataset. Evaluation metrics such as mean squared error (MSE), root mean squared error (RMSE), mean absolute error (MAE), and R-squared (R2) are calculated to assess the model's performance.

# Data Visualization (Actual vs. Predicted)
The project also provides a line plot that compares the actual and predicted stock prices. This visualization helps visualize the accuracy of the predictions and provides insights into the model's performance.

# Usage
To run the Stock Price Prediction project:
Install the required dependencies mentioned in the requirements.txt file.
Fetch the historical stock data using the desired ticker symbol and date range.
Execute the main script or run the Jupyter notebook to preprocess the data, train the LSTM model, and make predictions.
Visualize the stock data using various plots to gain insights into the historical trends and compare actual vs. predicted prices.

# Conclusion
The Stock Price Prediction project demonstrates the use of historical stock data and an LSTM model to forecast future stock prices. It provides visualizations and evaluation metrics to evaluate the model's performance. This project can be a starting point for further exploration and improvement in the field of stock price prediction.

# Acknowledgements
The project utilizes the "yfinance" library for fetching historical stock data. The analysis and modeling approach are inspired by the goal of accurate stock price prediction using machine learning techniques.

