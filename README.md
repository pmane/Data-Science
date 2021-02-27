# Data-Science
Time Series Experiments

**Project Motivation -**

Financial time series is fundamental to the field, and predicting stock price has been a challenging problem to solve. I am going to attempt to use CRISP-DM approach to understand the patterns in data and answer some practical questions about investment decisions investors need to make.

 Questions asked
a.What is the level of risk — nature of the distribution of returns?
b.What is the contribution of trend, seasonality, and noise (risk)?
c.Which features are co-related most with a price?
d.Does price have some memory of past — autoregressive structure?
e.Can we predict stock price directional movement or price itself?

The project explains how the CRISP-DM process can be applied to financial time series data. CRISP-DM is the cross-industry process for data mining. It is a structured approach to planning a data mining project. Code along with the medium article (https://disruptivenext.medium.com/crisp-dm-for-financial-time-series-b4e01fcb4e8b) explains how meaningful patterns can be detected in Financial time series data. Project further proposes key questions that can help the investor to make investment decisions.


**Requirements**
1.TA_Lib==0.4.19
2.scikit_plot==0.3.7
3.yfinance==0.1.54
4.scipy==1.4.1
5.numpy==1.18.1
6.statsmodels==0.11.0
7,pandas==1.0.1
8.seaborn==0.10.0
9.matplotlib==3.1.3
10.scikit_learn==0.24.1
11.scikitplot==0.1.1
12.talib==0.1.1

**Files in the Repository**

**DataAgreegator.ipynb** - Program to download data from yahoo finance  
1.yfinance library to download market data 
2.TA-lib is used to add more features to capture various aspects like momentum, volatility , moving averages, etc.

**EDA.ipynb** - Exploratory data analysis for financial time series
1.Standard DS libs like Numpy, Panda , seaborn, matplot and scikitplot
2.Statsmodels for SimpleExpSmoothing
3.Sklearn 

**Model.ipynb** - Simple linear regression model for financial time series 
1.Standard DS libs like Numpy, Panda , seaborn, matplot and 		 scikitplot,Sklearn

Data source used
Basic data is downloaded from yfainance then augmented with additional features using TA-Lib.

**Results**
Summary has been elaboarted in https://disruptivenext.medium.com/crisp-dm-for-financial-time-series-b4e01fcb4e8b.

Acknowledgment
All of the content is purely based on my work experience in the financial field. API documentation from respective libraries is used to understand how to use the API.
