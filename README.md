# Stock Price Prediction

## AIM

To develop a Recurrent Neural Network model for stock price prediction.

## Problem Statement and Dataset
We aim to build a RNN model to predict the stock prices of Google using the dataset provided. The dataset has many features, but we will be predicting the "Open" feauture alone. We will be using a sequence of 60 readings to predict the 61st reading.
Note: These parameters can be changed as per requirements.

## Neural Network Model

Include the neural network model diagram.

## DESIGN STEPS

## Step 1:
Read the csv file and create the Data frame using pandas.

## Step 2:
Select the " Open " column for prediction. Or select any column of your interest and scale the values using MinMaxScaler.

## Step 3:
Create two lists for X_train and y_train. And append the collection of 60 readings in X_train, for which the 61st reading will be the first output in y_train.

## Step 4:
Create a model with the desired number of nuerons and one output neuron.

## Step 5:
Follow the same steps to create the Test data. But make sure you combine the training data with the test data.

## Step 6:
Make Predictions and plot the graph with the Actual and Predicted values.
## PROGRAM

Include your code here

## OUTPUT

### True Stock Price, Predicted Stock Price vs time

Include your plot here

### Mean Square Error

Include the mean square error

## RESULT
