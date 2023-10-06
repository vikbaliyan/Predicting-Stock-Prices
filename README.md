[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/LaCb-Cwa)

## Team Members

Jazbi Izhar 101419010
Vikas Baliyan 101414477

# Final Project

Title: Predicting Stock Prices Using LSTM

Introduction and Goal

The objective of this project is to apply Long Short-Term Memory (LSTM), a type of Recurrent Neural Network (RNN), to predict the closing stock prices of a corporation using the past 60-day stock price. Given the volatile nature of the stock market, it poses an interesting and challenging problem for time series prediction. Our main focus will be on applying deep learning techniques and understanding the impact of hyperparameters on the model's performance.

Dataset

We will use the Yahoo Finance dataset for a particular corporation. The dataset will consist of different stock attributes like Open, High, Low, Close, and Adjusted Close prices, and the Volume of stocks traded for each day. Our target variable will be the 'Close' price.

Methodology

    • Data Collection: We will use the pandas_datareader library to fetch the stock prices data from Yahoo Finance.
    • Data Pre-processing: We will pre-process the data to create a suitable time-series dataset for our LSTM model. This involves    scaling the data and converting it into a format where the model is trained on 60 days of historical prices to predict the next day's closing price.
    • Model Construction: We will use Keras, a deep learning library, to build an LSTM model. The model will contain LSTM layers followed by dense layers to output the predicted closing price.
    • Training: We will train our LSTM model on the processed dataset.
    • Evaluation: The performance of the trained model will be evaluated by comparing the predicted stock prices against the actual prices.
    • Hyperparameter Tuning: To optimize our LSTM model, we will experiment with various hyperparameters (e.g., number of LSTM layers, number of neurons, dropout rate, optimizer, learning rate) and model configurations.



Tools

Python will be the primary language for this project. We'll use libraries such as pandas for data manipulation, Keras for model building, and Matplotlib for data visualization.


Expected Outcomes

Our goal is to build an LSTM model that can accurately predict the stock prices. We will present the performance of the model with appropriate metrics and visualizations. This project will help us understand the strengths and limitations of LSTM models when applied to time-series prediction problems.


Timeline

The project will be completed within a week from May 30th to June 8th, with the following tentative schedule:
    • May 30th - June 1st: Data collection and pre-processing
    • June 2nd - June 3rd: Model construction and training
    • June 4th - June 5th: Model evaluation and hyperparameter tuning
    • June 6th - June 7th: Conclusion and finalizing the report
    • June 8th: Submission


References:

    • Understanding LSTM Networks
    • Time Series Prediction with LSTM

## This proposal gives a clear direction to our project, setting achievable goals and providing a feasible timeline.
