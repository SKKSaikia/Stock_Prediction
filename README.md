# Stock_Prediction

 Project started : 21:50 , 28/10/2017 | PwC challenge #9, Hack2Innovate Hackathon (2 Day), IIT-G

 Sentiment Analysis of Tweets & predicting Stock prices based on user sentiments about # Amazon
 
 Dataset : We have created 2 data sets on our own.
 
 (1) data.json - is a dictionary holding a key-value pair of sentiment ( 1 for positive & 0 for negative )
     , where "key" is the sentiment ( either 0 or 1 ) & "value" is the sample tweet (" Actual Tweet by users").
     
 (2) data.txt - sample data file holding 2 columns & 100 rows (rows denote no of cases).
 
     The two columns:
     column ( tweet_sent ) - holds data if the tweet was positive ( 1 ) or negative ( 0 ).
     column ( stock_sent ) - holds data if stock price rose ( 1 ) or fell ( 0 ).
     0 for fall/-ve sentiment & 1 for rise/+ve sentiment.
     
 We lack proper cleaned datasets for both Stock data & tweets of same timeframe in the meantime.
 
 Note : Since, the stock fluctuations are made up & the tweets too.We are unable to predict and match with real case scenarios.For instance, during festive season, people generally shops more & feel happy about it.This trend during festive season generally tends to increase stock prices, because of more demand of the products.Since, here we dont have a time to time mapped dataset of people's sentiments & stock fluctuation, We are unable to predict/verify if really that happened.
 
Future case scenario : With proper datastes, we can better train the model & hence get better accuracy.We will be able to extend & predict the same outcome of another e-commerce site during similar historic events.

Meanwhile :


INPUT TEST CASES:

![Input Image](https://github.com/SKKSaikia/Stock_Prediction/blob/master/input.PNG)

OUTPUT TEST CASES:

![Output Image](https://github.com/SKKSaikia/Stock_Prediction/blob/master/output.PNG)


We can see our model performs well for the self generated test cases.In future, we can maybe get real time tweets with the help of an API & predict the stock fluctuations for the coming days.
