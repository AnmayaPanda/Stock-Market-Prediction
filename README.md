# Stock Price Prediction with LSTM

This project utilizes Long Short-Term Memory (LSTM) networks to predict stock prices. The model is trained on historical stock data and then tested on a more recent dataset to evaluate its accuracy.

## Prerequisites

Before running the code, make sure you have the required libraries installed:

- NumPy
- Matplotlib
- Pandas
- yfinance
- TensorFlow
- scikit-learn

You can install them using:

```bash
pip install numpy matplotlib pandas yfinance tensorflow scikit-learn
```
## Getting Started
1. Clone the repository:
```bash
git clone https://github.com/your-username/stock-price-prediction.git
cd stock-price-prediction
```
2. Run the Python script:
```bash
python stock_prediction.py
```
This will train the LSTM model, test it on existing data, and make predictions for the next day.

## Usage
- Adjust the company, start, and end variables to select the desired stock and time range for training data.
- Tweak hyperparameters such as units and epochs in the LSTM model for experimentation.
- The predicted vs. actual stock prices will be displayed in a Matplotlib plot.
  
## Results
The script generates a plot showing the actual stock prices and the model's predicted prices. Additionally, it prints the prediction for the next day.

## Contributing
Feel free to contribute to this project by forking and submitting pull requests.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Special thanks to the yfinance library for simplifying Yahoo Finance data retrieval.
Inspired by the potential of LSTM networks for time-series prediction.
