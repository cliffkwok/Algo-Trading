# Applications of LSTM to the Prediction of Stock Market
## Introduction
准确预测一只股票的涨跌趋势对我们在股市的成功起着重要作用。LSTM(Long short-term memory)是一种特殊的RNN，是一种用于处理序列数据的神经网络，主要可以解决长序列训练过程中的梯度消失和梯度爆炸问题。简单来说，就是相比普通的RNN，LSTM能够在更长的序列中有更好的表现。在本文中，我们研究了 LSTM（使用Keras Python包）在股票每日价格预测中的应用。同时，我们将采用 CNN 来完成这一任务，并将其与 LSTM 进行比较。最后我们发现，LSTM 在完成时间序列类型任务的时候有着很不错的表现。

## Dataset
我们将从 Yahoo Finance 获取股票数据。Yahoo Finance 是一个丰富的金融市场数据和工具资源，我们可以使用 yfinance 库来从该网站下载股票数据。

## Installation
You can run the jupyter notebook via Colab.

## Neural Network Model
- LSTM(Long short-term memory)
- CNN(Convolution Neural Network)
