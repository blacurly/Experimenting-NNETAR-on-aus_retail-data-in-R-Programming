# Experimenting-NNETAR-on-aus_retail-data-in-R-Programming

On this case, we want to experiment with using NNETAR() on aus_retail data and then compare its model performance against the traditional time series models.

The NNETAR() function is part of the forecast package in R and is used for Neural Network Time Series Forecasting. 
It offers several advantages for time series forecasting:

1. It can capture complex **nonlinear relationships** in the data, which traditional linear models might miss.
2. Can handle both seasonal and non-seasonal data
3. By fitting multiple networks with different random starting weights and averaging the results, it reduces the risk of overfitting and improves forecast accuracy2.
4. The function can scale inputs, which helps in handling data with different magnitudes and improves the stability of the model
