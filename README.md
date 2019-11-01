# solar_energy_price_prediction
Final project for Time Series Analysis class. 

The goal here was to employ as many relevant time series models to the problem of predicting solar energy prices, in certain instances given covariates such as silicon, the price of oil, GDP, and weather patterns. 

To evaluate each model, where possible, we calculate MSE and MAE of a sliding window cross validation and then calculate MSE and MAE of the one-year forecast. 

Perhaps unsurprisingly, Facebook's Prophet model and the RNN both performed the best; that said, the far-less complex Auto Arima model isn't too bad!

The attached deck is definitely not for a business audience. 

In the R code: Some of the sliding windows for TBATS may have difficulty converging; also, need to fix some of the code with regard to the ARIMAX model. 
