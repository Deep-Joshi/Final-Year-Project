# Stock Price Trend Forecasting

Stock Market is an area of interest for lots of people maybe because of the perception that it is a good source to earn fast and make easy investments, however, this a myth. It takes years and years for the market’s big players to learn the art of trading, analyzing the stock prices and their trends. Lot of dedication and time is invested to acquire these skills of analyzing the stocks. Stock Market is one area where one will witness a lot of fluctuations and quite often, this makes the task of analyzing more complicated and challenging. An investment theory suggests that the stock price changes are reflection of all the relevant information about that stock. Basically, more the information we gather about the stock higher the chances of accurately analyzing the trend of that stock.

This project revolves around the same concept and focuses on providing an in-depth analysis about the stock indicators that might assist the users in making accurate decisions. A hybrid model has been developed based on various techniques, tools and concepts from the Machine Learning, Natural Language Processing, Sentiment Analysis and Time Series Forecasting to achieve two main objectives:

1.	Analyze the stock fundamentals through historical and real time data, and forecasting its future price 
2.	Analyze the public emotions, news headlines relating to a stock conveyed through Twitter and provide an optimal prediction about its future trend

In order to convey the analysis outcomes, predictions and stock indicators, an interactive web application has been built using the Flask framework. 

Python Libraries Used: numpy, pandas, matplotlib, nltk, scikit-learn, pygal, datetime, csv, stringio, zipfile, urllib, re, nsetools, nsepy, json, flask, ouath2, pickle, os, etc.

Keywords: Support Vector Machines, Hyperparameter Optimization, Natural Language Processing, Hodrick-Prescott Filtering, Time Series Forecasting, AFFIN, Twitter API, Flask

This repository contains all the relevant files contributing to the overall project development.  

'templates' directory consist all HTML files used for web application creation. ‘Data’ folder contains the list of stopwords and all the intermediate files utilized in manipulating and transforming the data. 
‘config.json’ -> File containing key-value pairs required to fetch tweets securely through Twitter API
‘newfile.txt’ -> This file demonstrates an example of feature vectors developed after revamping the unstructured text data from the tweets several natural language processing techniques.
‘app.py’ -> Main entry point to our application. Consists entire code and steps required to build an end to end machine learning pipeline. 
Steps to run the application locally: Open Command Prompt -> Change the path to a location that contains all these files -> Type 'python Main.py' -> Hit the URL on the browser.

