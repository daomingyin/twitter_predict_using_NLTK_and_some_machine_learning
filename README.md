# twitter_predict_using_NLTK_and_some_machine_learning

In our project, we built up a prediction model that bags eight machine learning algorithms to perform technical analysis on the stock price on Zoom. 

In our model, we used seven technical analysis indicators, as well as two sentimental indicators, as our explainable variables. 

For each day, each of the eight machine learning algorithms will produce a trading signal (1 for buy and -1 for sell) to vote for the decision.

We performed back test on Zoom’s stock price from Jan 1 st to Apr 24th , 2020 and compared the prediction capability of our model with pure momentum. We found higher cumulative return achieved in our model against pure momentum.

This code mainly use NLTK and some machine learning skills to make a forecast,
and mainly use for my own assignment.


There are two codes file, one is use word2vector and LDA to create the dictionary of coronavirous 
and do the sentiment analysis based on that.


Another one is mainly using the machine learning tools to figure out the relationships 
between the sentiment & technical indicator with stock price


The twitter code is scraped and only uploaded the clean version.

The extratreeClassifier is not accurate so i just delete from plot.

If you have some questions, feel free to contact[email:brayntyin@163.com],[wechat:Dick9233]

金融研究生 assignment，

主要研究最近推特上对单只股票的情绪以及市场的情绪，

一个代码是用词袋创立关于 coronavirous 的词库， 在 twitter 上使用词库提取含有关键词的上下文，并对其情感分析

另一个是用机器学习方法拟合走势

整合部分技术指标 

用算法去预测 accumulate return. 

比较各种算法的优缺点

![image](1588201923050.jpg)
