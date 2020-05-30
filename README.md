# COVID19 Forecast Using 1-D Convolution and LSTM.

This project utilizes machine learning for time series prediction to forecast the number of confirmed COVID19 cases in each country around the world. 
Types of neural networks used are 1-D Convolution and LSTM. All details and descriptions are in the notebook. 

## Data
Number of confirmed COVID19 cases in various locations across the world provided by [Kaggle](https://www.kaggle.com/c/covid19-global-forecasting-week-5/overview)

## Result
```Validation Loss = 0.3111```

```Validation MAE = 0.5689```

This was the result of training for 150 epochs without any thorough tuning. The forecast graphs are shown in the notebook.

![thailand](https://github.com/KongpolC/covid_19_forecast/tree/master/images/thailand.png)

![us](https://github.com/KongpolC/covid_19_forecast/tree/master/images/us.png)

![russia](https://github.com/KongpolC/covid_19_forecast/tree/master/images/russia.png)

![uk](https://github.com/KongpolC/covid_19_forecast/tree/master/images/uk.png)

![india](https://github.com/KongpolC/covid_19_forecast/tree/master/images/india.png)
