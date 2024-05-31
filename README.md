# forex-pridection-using-Random-Forest-Classifier-model
forex prediction using Random Forest Classifier model in python
This repository contains Python code for predicting forex trading signals using historical data and machine learning techniques. It uses the yfinance library to download historical forex data and the pandas_ta library to add technical analysis features. The machine learning model is implemented using the scikit-learn library, specifically a Random Forest Classifier.

# Installation
Clone the repository:
sh
Copy code
git clone https://github.com/your-username/forex-trading-predictor.git
Install the required Python libraries:
sh
Copy code
pip install -r requirements.txt
# Usage
Run the main.py file to train the model and make predictions.
sh
Copy code
python main.py
The script downloads historical forex data for the specified currency pair (default: EUR/USD) from Yahoo Finance, adds technical analysis features, and trains a Random Forest Classifier to predict trading signals based on these features.
The accuracy of the model is printed to the console, along with a classification report.
# Configuration
To change the currency pair or the date range of the historical data, modify the currency_pair and start/end parameters in the main.py file.
To modify the features used for prediction, update the features list in the main.py file.
To experiment with different machine learning models or hyperparameters, edit the model initialization and hyperparameter tuning sections in the main.py file.
