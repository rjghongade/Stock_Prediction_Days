# Stock Price Prediction with Linear Regression

This Python script uses the Yahoo Financials API to retrieve historical stock price data for a given stock and then uses linear regression to predict stock prices for a specified number of days into the future.

## Getting Started

### Prerequisites

Make sure you have Python installed. You can download it from [python.org](https://www.python.org/downloads/).

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/rjghongade/stock-prediction.git
   ```
Install the required libraries:
```
   pip install pandas numpy yahoofinancials mplfinance
```
### Usage

Run the script:
```
   python stock_prediction.py
```
When prompted, enter the stock symbol (e.g., AAPL for Apple Inc.).

The script will fetch historical data, perform linear regression, and predict stock prices for the next day.

### Acknowledgments
Yahoo Financials API
Python
scikit-learn


