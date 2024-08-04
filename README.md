Stock Prediction Chatbot
This project is a stock prediction chatbot built using Python, Gradio, and yfinance. The chatbot predicts the closing price of a stock for the next day based on historical data.

Project Overview
The chatbot uses historical stock data to train a simple Linear Regression model. It then predicts the next day's closing price and provides the mean squared error (MSE) of the model. This project is designed to run in Google Colab for ease of use and demonstration.

Features
Fetch Historical Data: Retrieves stock data using yfinance.
Model Training: Trains a Linear Regression model on historical data.
Prediction: Predicts the next day’s closing price.
Gradio Interface: Provides an interactive web interface to input stock data and view predictions.

Usage
Open the Gradio Interface:

After running the last cell, Gradio will provide a public URL. Click the URL to open the interactive web interface.

Input Data:

Stock Ticker: Enter the ticker symbol of the stock (e.g., AAPL).
Start Date: Enter the start date in the format YYYY-MM-DD (e.g., 2023-01-01).
End Date: Enter the end date in the format YYYY-MM-DD (e.g., 2023-12-31).
View Results:

The interface will display the predicted closing price for the next day and the model's mean squared error.
