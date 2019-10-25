# PutStrategyImplementation
The main algorithm for put strategy implementation developed with the help of SUNY Distinguished Prof. Chunming Qiao, Dr. Charles Tirone, Prof. Zhen Liu and Jay Schwartzkopf

Steps:
1. Point and Figure arrays implementation that gives us the resistance and support levels.
2. SMA and MACD values for current date taken from Alpha Vantage API. MACD contains an extra step of slope calculation to see if the prices are going up or down.
3. RSI value taken from Alpha Vantage API.
4. Stocks filtering on the basis of Earnings Date.
5. Contracts extraction from TDAmeritrade API on the basis of specific tested extraction parameters.
