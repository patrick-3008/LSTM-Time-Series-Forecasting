# LSTM Time Series Forecasting

This project demonstrates time series forecasting of Microsoft stock prices using an LSTM (Long Short-Term Memory) neural network in Python. The workflow includes data loading, visualization, preprocessing, model building, training, and evaluation.

## Features

- Loads and visualizes historical Microsoft stock data
- Preprocesses data and applies feature scaling
- Builds and trains an LSTM-based neural network for price prediction
- Evaluates and visualizes model predictions vs. actual prices

## Requirements

- Python 3.7+
- TensorFlow / Keras
- pandas, numpy, matplotlib, seaborn, scikit-learn

## Usage

1. Place `MicrosoftStock.csv` in the project directory.
2. Run the notebook cells sequentially to reproduce the analysis and results.

## File Structure

- `lstm-time-series-forecasting.ipynb`: Main notebook for data analysis and modeling
- `MicrosoftStock.csv`: Input dataset (not included)

## References

- [TensorFlow LSTM documentation](https://www.tensorflow.org/api_docs/python/tf/keras/layers/LSTM)
- [Keras Sequential API](https://keras.io/guides/sequential_model/)
