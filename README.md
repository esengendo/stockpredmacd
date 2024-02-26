# Stock Price Analysis with LSTM and MACD Signals

## Overview

This repository hosts an exploratory data science project focused on analyzing and predicting stock price movements, particularly for NVIDIA Corporation (NVDA). The project incorporates machine learning techniques, traditional technical indicators like Moving Average Convergence-Divergence (MACD), and modern machine learning models, specifically Long Short-Term Memory (LSTM) networks.  

This data science project aims to explore the application of machine learning, specifically Long Short-Term Memory (LSTM) networks, in predicting stock price movements. The analysis focuses on NVIDIA Corporation (NVDA) stock, utilizing historical stock data obtained through the `yfinance` Python package for stock data  retrieval and incorporating tools like Moving Average Convergence-Divergence (MACD) and Long Short-Term Memory (LSTM) networks, the project aims to provide insights. 

Additionally, there is a Streamlit representation of this process available, allowing users to interactively explore the analysis by running the `app.py` script.

The project is exclusively educational and exploratory, with a focus on fostering understanding and experimentation. It is important to note that this initiative is not intended for providing investment advice or making actual investment decisions.

## Objective

To conduct a comprehensive analysis and prediction of NVIDIA Corporation (NVDA) stock prices using LSTM, and classical technical indicators such as MACD. The project seeks to leverage historical data and interactive tools like Streamlit for an educational exploration into the capabilities of predictive analytics in stock market trends, aiming to enhance understanding and application of data science in financial analysis without the intent of providing investment guidance.

### Features

- **Data Retrieval:** Utilizes `nvda.csv`, `X_backtest.csv`, and `y_backtest.csv` for historical stock data.
- **Technical Indicators:** Calculates and visualizes technical indicators like MACD and Bollinger Bands.
- **Machine Learning Model:** Implements an LSTM-based model for stock price prediction.
- **Interactive Exploration:** Features a Streamlit app (`app.py`) for exploring the analysis.

## Usage

### Dependencies

Ensure you have the required dependencies installed:
pip install -r requirements.txt

### Data Science Process

### Data Collection
Historical stock data is sourced from nvda.csv, X_backtest.csv, and y_backtest.csv.
Feature Extraction
Extracts features from stock prices, including various technical indicators and relevant metrics.

### Model Training and Evaluation
Trains and evaluates the LSTM model.
The saved model (my_lstm_model.keras) is loaded for backtesting.

### Project Files


nvda.csv: Historical stock data for NVIDIA Corporation.

X_backtest.csv: Feature data for backtesting.

y_backtest.csv: Target data for backtesting.

scaler.joblib: The scaler used in the project.

stockpred.ipynb: The full Jupyter notebook for the project.

app.py: Streamlit app for interactive exploration.

my_lstm_model.keras: Saved LSTM model used for backtesting.


### Conclusion
In conclusion, this educational and exploratory project provides insights into the application of both traditional technical indicators like MACD and modern machine learning models such as LSTM networks for stock price prediction. Interactive tools, such as the Streamlit app, enhance the accessibility of the analysis, allowing users to engage interactively with the findings. 

Please note that this project is not intended to provide investment advice or make actual investment decisions.


Feel free to further customize it based on your preferences and any additional details you'd like to include.



### Running the Interactive App

To interactively explore the analysis, run the provided Streamlit app:

```bash
streamlit run app.py

