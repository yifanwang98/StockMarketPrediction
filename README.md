## Stock Market Prediction

The aim of this project is to test a data source (signal, second column in data.csv) which claims to be predictive of future returns of the SP500 index (spy_close_price, third column in data.csv). We use SPY (SPDR S&P 500 ETF) as a proxy for the SP500 index.

The signal and spy_close_price are both received at the same time at the end of the day on the date listed in column 1. We do not know how the signal is generated or have a prior conviction about the forecast horizon over which the signal is supposed to be effective, nor its stationarity.
