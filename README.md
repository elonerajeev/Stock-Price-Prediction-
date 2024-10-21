# Stock-Price-Prediction-
This Is Machine Learning Project In Which we try to predict the Prices of Google / tesla  Stock prices on the using the Modules

# Google Stock Price Prediction using RNN

This project implements a Recurrent Neural Network (RNN) to predict Google stock prices. It uses historical stock data to train the model and make future price predictions.

## Table of Contents
1. [Overview](#overview)
2. [Dependencies](#dependencies)
3. [Project Structure](#project-structure)
4. [How It Works](#how-it-works)
5. [Usage](#usage)
6. [Results](#results)

## Overview

This project uses a Long Short-Term Memory (LSTM) network, a type of RNN, to predict Google stock prices. The model is trained on historical stock data and can make predictions for future stock prices based on the patterns it learns.

## Dependencies

To run this project, you need the following libraries:
- numpy
- matplotlib
- pandas
- scikit-learn
- keras
- tensorflow (as backend for keras)

You can install these dependencies using pip:
## pip install numpy matplotlib pandas scikit-learn keras tensorflow


## Project Structure

The project consists of a single Python script that performs the following steps:
1. Data Preprocessing
2. Building the RNN
3. Making predictions and visualizing results

## How It Works

1. **Data Preprocessing**: 
   - The script loads historical Google stock price data.
   - It uses the MinMaxScaler to normalize the data.
   - The data is then structured into 60-day sequences for training.

2. **Building the RNN**:
   - A Sequential model is created using Keras.
   - It consists of four LSTM layers with Dropout for regularization.
   - The model is compiled using the Adam optimizer and mean squared error loss function.

3. **Making Predictions**:
   - The trained model is used to predict stock prices on a test dataset.
   - The results are then visualized, comparing the predicted prices with the actual prices.

## Usage

1. Clone this repository.
2. Ensure you have all the required dependencies installed.
3. Run the Python script:

## python stock_prediction.py

4. The script will train the model and display a graph showing the actual vs predicted stock prices.

## Results

The script outputs a graph that compares the real Google stock prices (in red) with the predicted stock prices (in blue). This visual representation helps in understanding how well the model performs in predicting stock prices.

---

Note: Stock market prediction is a complex task influenced by many factors. This project is for educational purposes and should not be used for actual trading decisions.



