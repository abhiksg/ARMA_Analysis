I utilized two key financial data series - the S&P 500 stock index prices and the 10-year U.S. Treasury bond yields - to conduct a comprehensive time series analysis. These data were retrieved from the Federal Reserve Economic Data (FRED) database maintained by the Federal Reserve Bank of St. Louis, which is a trusted source for a wide range of economic and financial time series data.

The motivation behind using these two variables was to explore the potential relationships and interactions between the equity markets, represented by the broad S&P 500 index, and the bond markets, specifically the widely-followed 10-year Treasury yield. This analysis could provide insights into how movements in stock prices might influence or be influenced by changes in long-term interest rates, and vice versa.

After acquiring the data series from FRED, I performed various time series analysis techniques, which may have included:

1. Visualizing the data over time to identify trends, patterns, and potential structural breaks.
2. Testing for stationarity using methods like the Augmented Dickey-Fuller test to check for unit roots.
3. Examining the autocorrelation and partial autocorrelation functions to determine the appropriate ARIMA model parameters.
4. Estimating and fitting ARIMA (Autoregressive Integrated Moving Average) or other time series models to capture the dynamics of the data.
5. Checking the residuals for white noise and conducting diagnostic tests to validate the model assumptions.

With the fitted time series models, I aimed to forecast future values of the 10-year Treasury yield, leveraging the information contained in both the yield itself and the S&P 500 index. This forecasting exercise could have potential applications in areas such as portfolio management, interest rate risk analysis, and economic forecasting.
