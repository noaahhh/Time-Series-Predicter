# Time-Series-Predicter

 <div align="center">
  <h3>Forecasting time series data with machine and deep learning techniques</h3>
  
  <img src="assets/images/dxy-tahmin.png" >
  <a href="https://github.com/noaahhh/Time-Series-Predicter/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/noaahhh/Time-Series-Predicter/issues"></a>
  <a href="https://github.com/noaahhh/Time-Series-Predicter/issues/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/noaahhh/Time-Series-Predicter"></a>
  <a href="https://github.com/noaahhh/Time-Series-Predicter/issues/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/noaahhh/Time-Series-Predicter"></a>
</div>

# About
This project aims to how to forecast a financial time series data using machine and deep learning techniques. Using this knowledge, I want to create an project which can predict next values of financial datas.  Tecnical analysis notebook contains different indicator for BTC-TRY prices.

LSTM univariate models can forecast DXY and Gold ounce price using own old data. 

LSTM multivariate models forecast DXY ann Gold ounce price with many financial time series, multi input and one output is used. 

C-LSTM models is the version of multivariate models that added convolitional and pooling layer. 

# Installation
you can download latest version of imported library at the beginning of notebook for all or just install requirements.txt.

``` sh 
keras-latest
tensorflow-latest
matplotlib-latest
pandas_datareader

#or
pip install -r requirements.txt

```

for installation you can use:
``` sh
pip3 install keras  matplotlib tensorflow pandas_datareader --upgrade 

```
# Usage

All notebooks can runnable end to end. Just click `run All` in jupyter notebook.

# Prediction Period
  <img src="assets/images/dxy-splits.png" >

Train, validation test splits is like the plot above. The last 365 trading days is test dataset. Rest of the datasets splits as 70:30. %70 is train and %30 validation dataset