In this analysis, I am going to implement time-series analysis with the Prophet model in Python. The purpose is to predict the number of tourists to Japan based on past historical data.

**Time Series Analysis**

The Facebook prophet model performs a time series analysis to predict future visitors. Prophet was developed by Facebook researchers in order to create high-quality business forecasting. An additive regression model was utilized in this model, and it consists of four main components as follows:
y(t)=g(t)+s(t)+h(t)+ε(t)
Where,
* g(t) is the trend function which models non-periodic changes in the value of the time series
* s(t) represents periodic changes which occur due to seasonal effects period
* h(t) represents the effects of holidays which occur on potentially irregular schedules over one or more days
* ε(t) intends to any unusual changes which are not recognized by the model.

  
**Data**


The dataset I used for this analysis can be downloaded from [JTB Tourism Research & Consulting Co](https://www.tourism.jp/en/tourism-database/stats/inbound/).
The data provided the monthly number of visitors to Japan from 2014 to 2018.

**Used Tools for Analysis**

* Google Colab
* Python
  
**Required libraries**
* Pandas
* NumPy
* Matplotlib
* Prophet


