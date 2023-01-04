# Time-series-forecasting

In this project we will predict the live stock prices of the top 100 companies listed in wikipedia using Yahoo finance and scikit learn. Along the way, we will create a new dataset with company names and its corresponding stock symbol appended to the data. This means our model will predict the prices starting from the 9:30 am to 4:00 pm on any day, which is the time peroid the stock market functions.  Also we  will include the evaluation metrics to judge the behaviour of the model for th etime series data. Finally we will see how the daily news have an important impact on the stock prices by taking the twitter acquisition example.

The main purpose in doing this is project is, it contains some concepts that I believe has a greater impact and applications in the real world. The majority of people turn to the performance of a country’s stock market as the best indicator of how well that economy is doing. Stock markets cover all industries across all sectors of the economy. This means they serve as a metric of what cycle the economy is in and the hopes and fears of the population who generate growth and wealth.

Time series:
According to the statisitics, time series is a collection of observations of well-defined data items obtained through repeated measurements over time. For example, measuring the value of retail sales each month of the year would comprise a time series. 

Components for Time Series Analysis:
There are four categories of the components of time series. They are
•	Trend
•	Seasonal Variations
•	Cyclic Variations
•	Random or irregular Movements

Problem statement
In this project, we are predicting whether the future price of a stock goes upward or downward (depicted as “Target”-(1/0)) based on past values of the data.

Libraries
1.	Yahoo finance
2.	Pandas
3.	Numpy
4.	Matplotlib
5.	Scikit Learn
6.	Datetime
7.	Seaborn (Visualization)



Data Characteristics

•	Independent Variables: DateTime, Stock Symbol, Company, Open, High, Close, Low, AdjClose, Volume.
•	Dependent Variable: Target
•	Model Type: Binary Classification
•	Method: Supervised Learning

