---
published: true
---
# Introduction

Welcome to my blog, where I explore the exciting intersection of quantitative finance and cryptocurrency. My name is Danijel Jevtic, and as a finance and data science enthusiast, I've always been fascinated by the potential of cryptocurrencies like Bitcoin to disrupt traditional financial systems. In this blog, I will share my insights, research, and experiments with various data science techniques and trading strategies in the context of Bitcoin. Specifically, in this post, I will explore the use of Random Forest, a popular machine learning algorithm, in the development of an effective Bitcoin trading model. Whether you're a finance professional, a data science enthusiast, or simply someone curious about the world of cryptocurrency, I hope you'll find something of value in my blog. So, let's dive into the world of Bitcoin trading with Random Forest!

## Background on Bitcoin and its trading market

Bitcoin is a decentralized digital currency that was created in 2009 by an unknown person or group using the pseudonym Satoshi Nakamoto. Unlike traditional currencies, which are controlled by central authorities such as governments or banks, Bitcoin operates on a decentralized network of computers that use cryptography to secure and verify transactions. This makes Bitcoin a "peer-to-peer" currency that allows users to send and receive payments without the need for intermediaries.

The trading market for Bitcoin has grown significantly over the past few years, with more and more investors and traders entering the market. Bitcoin is now traded on a number of exchanges, with the largest and most popular being Binance, Coinbase, and Kraken. The market price of Bitcoin is determined by supply and demand, and can be highly volatile due to a number of factors, including changes in regulatory environments, news events, and the actions of large investors.[1]


### Why use random forest for Bitcoin trading?

Random forest is a powerful machine learning algorithm that has been widely used in various fields, including finance and economics. When it comes to Bitcoin trading, random forest can be particularly useful because of its ability to handle large and complex datasets, as well as its ability to capture non-linear relationships between variables.

One of the key advantages of random forest is its ability to handle a large number of input variables, which is often the case with Bitcoin trading data. In addition to traditional market indicators such as price and volume, there are many other variables that can potentially impact the price of Bitcoin, such as social media sentiment, news events, and regulatory changes. Random forest can handle this kind of high-dimensional data and effectively identify the most relevant input variables for the trading model.

Another advantage of random forest is its ability to capture non-linear relationships between variables. In the case of Bitcoin trading, the relationships between different variables can be complex and dynamic, and traditional linear models may not be able to capture these relationships effectively. Random forest can identify and model these non-linear relationships, allowing for more accurate predictions of future prices and better decision making.

Furthermore, random forest is known for its robustness to outliers and noise in the data. In the context of Bitcoin trading, this is particularly important as the market can be highly volatile and subject to sudden and unexpected price movements. By using random forest, the model can be more resilient to these unexpected events, leading to more consistent and reliable trading decisions.

Overall, random forest can be an effective tool for Bitcoin trading because of its ability to handle large and complex datasets, model non-linear relationships between variables, and robustness to noise and outliers in the data. By using this machine learning algorithm, traders can potentially improve their trading performance and increase their profits. [1-4]

## Data collection and preparation

In order to build an effective Bitcoin trading model using Random Forest, it's crucial to have access to reliable and accurate data. For this purpose, I have decided to use Glassnode as my data provider and their API as the primary tool for data collection. Glassnode is a leading on-chain market intelligence provider, delivering transparent and actionable insights into Bitcoin and other blockchain networks. Utilizing the Glassnode API, I was able to collect a wide range of relevant data, including historical Bitcoin price data, on-chain transaction data, and network statistics. In this section, I will discuss the steps I took to collect and prepare the data necessary for the development of my Random Forest model, utilizing the Glassnode API as my primary data source.

### Sources of Bitcoin market and on-chain data



### Data cleaning and preprocessing

### Feature engineering


## Random forest model building

### Overview of random forest algorithm

### Selecting input variables for the model

### Training the model on historical data

### Model evaluation and validation

## Backtesting and performance analysis

### Using the model to make trading decisions

### Backtesting the model on historical data

### Performance metrics and analysis

## Conclusion and next steps

## Summary of the project and results

## Limitations and potential improvements

## Future work and research directions


## References
[1] https://bitcoin.org/bitcoin.pdf
[2] Breiman, L. (2001). Random forests. Machine Learning, 45(1), 5-32.
[3] Dey, D. K., & Rajarshi, M. B. (2019). Forecasting stock price using a hybrid model of random forest and     artificial neural network. Journal of Big Data, 6(1), 14.
[4] Guresen, E., Kayakutlu, G., & Daim, T. U. (2011). Using artificial neural network models in stock market     index prediction. Expert Systems with Applications, 38(8), 10389-10397.
