# Bitcoin Price Prediction using LSTM

## Objective :

The goal is to predict the next day close price of Bitcoin using deep learning techniques, specifically Long Short Term Memory (LSTM).

## Steps Taken :

### Data Exploration :

We used the all-time historical data of Bitcoin from Yahoo Finance, checked the data types of each column, and plotted several columns to identify patterns.

### Data Preprocessing :

Doing some feature selection and engineering, create a some technical indicator like Exponential Moving Average, RSI, Bollinger Bands, and On Balance Volume. Check and handled missing values, created the target variable, normalized the features, converted features and target into sequences, and split the data into training and testing sets.

### Model Evaluation :

The model was evaluated using Mean Squared Error (MSE) as the loss function, which measures how well the model predicts. The goal was to minimize the loss on both the training and validation sets.

## Conclusion :

The LSTM model was able to predict the next day's Bitcoin closing price with a reasonable degree of accuracy. Through careful feature engineering and selection, the model learned from historical data, although its performance may vary depending on market volatility. Further tuning of model hyperparameters and additional data could improve the prediction accuracy.
