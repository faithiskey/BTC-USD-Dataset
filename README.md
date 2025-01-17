**Project Description**

This project performs a time-series analysis of Bitcoin (BTC) market data using Python. It explores key historical patterns and trends in the cryptocurrency market, focusing on supervised and unsupervised techniques to derive meaningful insights from the data.

**Dataset**
The dataset contains historical BTC market data with the following columns:
-Date: The date of the record.
-Open: Opening price of Bitcoin on the given day.
-High: The highest price of Bitcoin on the given day.
-Low: The lowest price of Bitcoin on the given day.
-Close: Closing price of Bitcoin on the given day.
-Adj Close: Adjusted closing price considering stock splits or dividends.
-Volume: The volume of Bitcoin traded on the given day.
The dataset spans 2788 rows and covers data from September 17, 2014, to May 5, 2022.

**Tools**

-Programming Language: Python.
-Environment:Jupiter notebook.


**Exploratory Data Analysis**

The following steps were performed to understand the dataset:
 a) Data Types:
-Numerical: Open, High, Low, Close, Adj Close, Volume.
-Date: Categorical (datetime conversion applied).
b) Dataset Dimensions:
-Rows: 2788.
-Columns: 7.
 c) Feature Relevance:
-Examined statistical trends and correlations among features such as Open, Close, and Volume.


**Model Building**
1) Data Preprocessing:
-Missing values handled.
-Converted "Date" into a datetime object and set as the index for time-series analysis.
2) Analysis Techniques:
-Descriptive statistics calculated to understand data variability.
-Visualization of price trends over time using matplotlib.


**Model Performance**
-Evaluation metrics: N/A (focus was on exploratory analysis and trends rather than predictive modeling).


**About**
This project provides a detailed analysis of Bitcoin's historical data, helping stakeholders understand price movements and trading volumes over time.

**Resources**
-Readme: Included.
-Activity: Analyzing trends over time.
-Languages: Jupyter Notebook, Python.
