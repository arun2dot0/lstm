# LSTM Stock Price Prediction

This project uses Long Short-Term Memory (LSTM) neural networks to predict stock prices based on historical data.

## Requirements

- Python 3.7+
- pip (Python package installer)


## Required Packages

The following packages are required and will be installed via the requirements.txt file:

- numpy
- pandas
- matplotlib
- scikit-learn
- tensorflow
- yfinance

You can also install them manually using pip:


## Installation

1. Clone this repository
2. Install the required packages , I have used pip for missing ones


## Usage

1. Data Collection:
   Run the data collection script to fetch stock data:
   This will create a CSV file with the stock data.

2. Model Training and Prediction:
Run the main script to train the LSTM model and make predictions:

3. Results:
The script will display plots showing the actual vs predicted stock prices and the prediction error. It will also print error metrics such as MSE, MAE, and RMSE.

## Customization

- To change the stock ticker, modify the `ticker` variable in `stockmarket.ipynb`.
- To adjust the time range of historical data, modify the `start_date` and `end_date` variables in `stockmarket.ipynb`.
- To change the LSTM model architecture or hyperparameters, modify the model definition in `stockmarket.ipynb`.

## Files

- `stockmarket.ipynb`: Script to fetch stock data using yfinance.
- `stockmarket.ipynb`: Main script for data preprocessing, model training, prediction, and visualization.
- `requirements.txt`: List of required Python packages.

## Notes

- Ensure you have a stable internet connection when running `collect_data.py` to fetch stock data.
- The performance of the model may vary depending on the chosen stock and time range.
- This project is for educational purposes and should not be used for actual financial decisions.

