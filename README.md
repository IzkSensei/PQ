
<p align="center">
  <img src="https://github.com/IzkSensei/TimeSeries/blob/master/Images/title.JPG">
</p>
<h1 align="center">Comparing prediction methods</h1>
<p>Time series forecasting is the process of predicting the future value of a sequence based on historical data. Research in the area of machine learning has recently been focused on this task to address the limitations of traditional forecasting methods, which are time-consuming and complex. A powerful forecasting technique that is able to infer stochastic dependencies between past and future values is highly needed with the increase of historical data and the need for accurate production forecasting.
</p>

## Introduction

<p> In this project we studied various methods for predicting time series datas like stock market and comparing th results of these models </a>
<ul>  
<li>Moving Average</li>
<li>Prophet</li>
<li>Long Short Term Memory (LSTM)</li>  
</ul>
</p>


## Problem details
Main Data:
  <p align="center">
  <img src="https://github.com/IzkSensei/TimeSeries/blob/master/Images/Main.JPG">
</p> 



## Results
<ul>
<li>Moving Avg:  
<p align="center">
  <img src="https://github.com/IzkSensei/TimeSeries/blob/master/Images/MV.JPG">
</p> 
<li>LSTM:
<p align="center">
  <img src="https://github.com/IzkSensei/TimeSeries/blob/master/Images/lstm.JPG" >
  <img src="https://github.com/IzkSensei/TimeSeries/blob/master/Images/lstm_corr.JPG" >
</p>

<li>Prophet:
<p align="center">
  <img src="https://github.com/IzkSensei/TimeSeries/blob/master/Images/Prophet.JPG" width="400">
  <img src="https://github.com/IzkSensei/TimeSeries/blob/master/Images/Prophet2.JPG" width="400">
</p>
</ul>


## Performance comparison
Comparing RMSE results of these models:
|**Method**|RMSE|
|-|-|
|MV|8129.87|
|LSTM|809.013|
|Prophet|9292.317|


## Refrences:

[1] Müller, K-R., et al. "Predicting time series with support vector machines." _International Conference on Artificial Neural Networks_. Springer, Berlin, Heidelberg, 1997.

[2] Gers, Felix A., Jürgen Schmidhuber, and Fred Cummins. "Learning to forget: Continual prediction with LSTM." _Neural computation_ 12.10 (2000): 2451-2471.

[3] Ariyo, Adebiyi A., Adewumi O. Adewumi, and Charles K. Ayo. "Stock price prediction using the ARIMA model." _2014 UKSim-AMSS 16th International Conference on Computer Modelling and Simulation_. IEEE, 2014.

[4] Taylor, Sean J., and Benjamin Letham. "Forecasting at scale." _The American Statistician_ 72.1 (2018): 37-45.

## Note
This implementation is based on [Tensorflow 2.0](https://www.tensorflow.org/guide/effective_tf2) package and made possible by [Google Colabratory](https://colab.research.google.com) GPU.
