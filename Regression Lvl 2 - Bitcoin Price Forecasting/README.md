# Bitcoin Price Prediction Using LSTM

## Project Overview

This project applies **Long Short-Term Memory (LSTM)** networks to predict the price of Bitcoin based on historical price data. LSTMs are a type of Recurrent Neural Network (RNN) designed to work well with sequential and time-series data. The project demonstrates how deep learning techniques can be used for financial forecasting, specifically for volatile assets like Bitcoin.

## Key Features

- **Data Preprocessing**: Loads Bitcoin historical data, scales the features, and prepares it for the LSTM model.
- **LSTM Architecture**: Builds an LSTM model to handle sequential data and make time-series predictions.
- **Training and Evaluation**: Trains the model on historical Bitcoin price data and evaluates the performance using standard metrics.
- **Future Forecasting**: Uses the trained LSTM model to predict future Bitcoin prices.

## Requirements

To run the project, you’ll need the following packages:
- Python 3.x
- TensorFlow 2.x
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

Install the dependencies with:

pip install tensorflow pandas numpy matplotlib scikit-learn

## Running the Project

1. Clone this repository:
   git clone https://github.com/bnikolaosb21/bitcoin-lstm-forecast
   cd bitcoin-lstm-forecast

2. Load the dataset (`lstm_variables.csv`) and the Python notebook (`Bitcoin_LSTM_Forecasting.ipynb`).

3. Run the notebook to preprocess the data, train the LSTM model, and visualize the predictions.

4. The notebook will produce a plot of the predicted versus actual Bitcoin prices, allowing you to evaluate the model's performance.

## Conclusion

This project provides a practical application of LSTM networks for time-series forecasting in the financial domain. While Bitcoin prices are inherently volatile, the model shows how deep learning techniques can be applied to predict future price movements. With further tuning and feature engineering, the model’s accuracy can potentially be improved.

