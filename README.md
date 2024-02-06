# PAIRS-TRADING-STRATEGY
A statistical approach to mean reversion pairs trading. I work with 11 Financial companies in the ASX 200. 
Back-test for cointegration between pairs of stocks from 01-01-2022 to 01-08-2023 [IN SAMPLE DATA].
For pairs of stocks that showed they were statistically cointegrated at a 5% significance level, an OLS regression was conducted for them.
From the OLS regression, a spread was formulated between the stocks. 
The IN SAMPLE spreads were then tested for stationarity using as ADF test (10% significance level).
Spreads between pairs of stocks which were statistically stationary, were then tested on [OUT OF SAMPLE] data for stationarity via ADF test. 
