# amzn_model
# LSTM-based Stock Price Prediction

This project utilizes a Long Short-Term Memory (LSTM) neural network to predict the closing prices of Amazon stock using historical data.

## Project Overview

The primary objective of this project is to demonstrate the application of LSTM networks for time series forecasting. The model is trained on historical stock prices and aims to predict future stock prices based on past data.

## Project Structure

- **Data Preparation**: The data is loaded, preprocessed, and transformed to be suitable for training the LSTM model.
- **Model Definition**: An LSTM model is defined using PyTorch.
- **Training and Validation**: The model is trained on the training set and validated on the test set.
- **Results Visualization**: The predicted stock prices are plotted against the actual prices to evaluate the performance of the model.

## Installation

To run this project, you need to have Python installed along with the following libraries:
- pandas
- numpy
- matplotlib
- torch
- scikit-learn

You can install these dependencies using pip:
```sh
pip install pandas numpy matplotlib torch scikit-learn
