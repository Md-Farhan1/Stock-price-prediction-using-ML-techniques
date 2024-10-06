# Stock-price-prediction-using-ML-techniques
Developed a hybrid model combining Logistic Regression for trend classification and LSTM for capturing time series patterns to predict stock prices. Preprocessed historical stock data and achieved improved accuracy with the LSTM model, utilizing Python, TensorFlow, and scikit-learn.
Stock Price Prediction Using Logistic Regression and LSTM
This project focuses on predicting stock prices using two different models: Logistic Regression for trend classification and Long Short-Term Memory (LSTM) for time series forecasting. It leverages historical stock market data to predict future price movements.

Features
Logistic Regression: Used for classifying stock price trends (up or down).
LSTM Model: Captures sequential patterns in stock prices to forecast future values.
Data preprocessing includes feature engineering and normalization for better model performance.
Tech Stack
Python
TensorFlow / Keras
scikit-learn
pandas
NumPy
Installation
Clone the repository:

bash
Copy code
git clone <repository-url>
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Ensure you have the correct data files (e.g., stock price data in CSV format) in the appropriate directory.

Usage
Open the Jupyter Notebook Stock_Market_Prediction_Model_Creation.ipynb to run the project interactively, or use the Python scripts like app.py for execution.

For Logistic Regression:

Run app.py for training and evaluation of the Logistic Regression model.
For LSTM:

Execute Stock_Market_Prediction_Model_Creation.ipynb for step-by-step model training and prediction using LSTM.
Results
The Logistic Regression model provides a baseline by predicting stock price trends (up or down).
The LSTM model captures sequential patterns and predicts stock prices with improved accuracy.
Data
The project uses historical stock market data, which should be structured in a CSV format with relevant features such as Open, Close, Volume, etc.
