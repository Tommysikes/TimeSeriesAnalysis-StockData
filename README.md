# TimeSeriesAnalysis-StockData

This repository encompasses comprehensive Time Series analysis conducted on stock data, with a particular focus on utilizing the Prophet Modeling technique. The stock data for prominent companies such as IBM and Microsoft was meticulously extracted for the year 2021, encompassing a variety of essential metrics including Closing Prices, Adjusted Closing Prices, Opening Prices, and more.

## Analysis Highlights
The project entails a rigorous data cleaning process, leveraging the power of Pandas and NumPy, to ensure the dataset's reliability and accuracy. An array of analytical techniques were employed, including:

- **ARIMA Model**: Time-honored ARIMA modeling was executed to unveil underlying patterns and trends within the stock data.
- **Stationarity Test**: A crucial stationarity test was performed to validate the data's suitability for analysis.
- **Prophet Model**: The advanced Prophet Model, designed for forecasting time series data, was employed. The analysis was enriched by calculating Volume-Weighted Average Price (VWAP).
  ## Data Storage : AWS S3 Bucket

## Libraries Employed
The project harnesses a multitude of Python libraries to carry out different stages of the analysis:

- **Data Loading**: pandas, boto3, io
- **Data Cleaning**: Pandas, NumPy
- **Visualization**: mplfinance, matplotlib, seaborn
- **Data Modeling**: Statsmodels, Prophet, scikit-learn
- **Interactive Dashboard**:dash
  ## Model Deployment :Heroku

This repository serves as an insightful resource for delving into the intricacies of Time Series analysis and how it can be applied to real-world stock data. It provides an opportunity to explore the methodologies employed and gain valuable insights into the dynamics of stock price movements.
