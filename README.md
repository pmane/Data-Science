# Data-Science
Time Series Experiments
Project Motivation -

The project explains how the CRISP-DM process can be applied to financial time series data. CRISP-DM is the cross-industry process for data mining. It is a structured approach to planning a data mining project. Code along with the medium article (https://disruptivenext.medium.com/crisp-dm-for-financial-time-series-b4e01fcb4e8b) explains how meaningful patterns can be detected in Financial time series data. Project further proposes key questions that can help the investor to make investment decisions.


Libraries used 
DataAgreegator - Program to download data from yahoo finance  
1.yfinance library to download market data 
2.TA-lib is used to add more features to capture various aspects like momentum, volatility , moving averages, etc.

EDA - Exploratory data analysis for financial time series
1.Standard DS libs like Numpy, Panda , seaborn, matplot and 		 scikitplot
2.Statsmodels for SimpleExpSmoothing
3.Sklearn 

Model - Simple linear regression model for financial time series 
1.Standard DS libs like Numpy, Panda , seaborn, matplot and 		 scikitplot,Sklearn

Data source used
Basic data is downloaded from yfainance then augmented with additional features using TA-Lib.

 Questions asked
a.What is the level of risk — nature of the distribution of returns?
b.What is the contribution of trend, seasonality, and noise (risk)?
c.Which features are co-related most with a price?
d.Does price have some memory of past — autoregressive structure?
e.Can we predict stock price directional movement or price itself?

 Acknowledgment
All of the content is purely based on my work experience in the financial field. API documentation from respective libraries is used to understand how to use the API.
