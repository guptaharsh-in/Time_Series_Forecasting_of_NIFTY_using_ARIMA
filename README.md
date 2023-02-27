# Time_Series_Forecasting_of_NIFTY_using_ARIMA

Time Series Forecasting of NIFTY using ARIMA model and comparing it with the Baseline Model

Install YahooFinance Library

Import Libraries

Load Data

Data Cleaning

Calculate Baseline Error 

Check for Stationarity (AdFuller Test)

Differncing

Check for Seasonality (Seasonal Decompose)

Identification of AR and MA Models (plot_acf, plot_pacf)

Calculate p,d,q

Here :  
p = AR Model Lags = PACF Plot = 1,  
d = Differecing = 1,  
q = MA Model Lags = ACF Plot = 1  

Train Test Split

Model Training using ARIMA

# Result & Conclusion

![Arima](https://user-images.githubusercontent.com/121168657/221621803-9376fb62-689c-42a1-bc84-078b63c111a3.JPG)

ARIMA Error > Baseline Error,   
Therefore, ARIMA was not Ideal to Forecast this particular Nifty Data.



