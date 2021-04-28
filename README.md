# Stock-Prediction-LSTM

Author: Brody Looney
Repository: Stock-Prediction-LSTM
Purpose: This is my final project for COS 470. This repository contains multiple .csv files and .ipynb files.
Created on: 4/28/2021

LSTM:
I have created a simple LSTM model on TensorFlow for predicting future stock prices. 
This model takes in 4 inputs, 'EMA10', 'EMA50', 'EMA200', and the 'Close' price.
The model makes a prediction on the 'Close' price.
I have fit the model with multiple stocks and I have changed the structure of the LSTM slightly for each different stock. 

STOCKS USED:
The stocks used are AAPL, AMZN, FB, GE, GOOGL, GS, IBM, JPM, MSFT, and TSLA. 
The .csv files for these tickers were downloaded from Nikhil Kohli's public dataset available on kaggle.

GITHUB REPOSITORY:
The repository is divided into two folders and this readme file. 

CSV Files: This folder contains all of the CSV files seperated by ticker. 
Source: This folder contains all of the .ipynb files that were created on Google Colab. 

Within the Source folder there are 11 .ipynb files, 10 of them have the structure of 
'ticker symbol' + '-LSTM.ipynb', with the ticker symbol being the ticker for the specific company.
The eleventh file is '10-LSTM.ipynb', this model trains on AAPL data and then makes predictions for all 10 companies.
