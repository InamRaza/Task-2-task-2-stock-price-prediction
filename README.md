# Task-2-task-2-stock-price-prediction
Short-term stock price prediction using historical market data.
# Task 2: Short-Term Stock Price Prediction

## Objective
To predict the next day’s closing stock price using historical stock market data.

## Dataset
- Source: Yahoo Finance
- Stock: Apple (AAPL)
- Data retrieved using the yfinance Python library

## Features Used
- Open
- High
- Low
- Volume

## Model Used
- Linear Regression

## Work Done
- Fetched historical stock data using API
- Selected relevant numerical features
- Split data into training and testing sets
- Trained regression model
- Predicted closing prices
- Plotted actual vs predicted prices for comparison

## Evaluation Metric
- Mean Absolute Error (MAE)

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- yfinance
- Scikit-learn

## Outcome
The model successfully predicts short-term stock price trends and demonstrates regression modeling on time-series data.
task-2-stock-price-prediction/
│
├── data/
│   └── stock_data.csv   (optional)
│
├── notebook/
│   └── stock_prediction.ipynb
│
├── images/
│   └── actual_vs_predicted.png
│
├── README.md
└── requirements.txt
