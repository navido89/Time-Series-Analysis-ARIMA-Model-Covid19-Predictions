# Predicting number of Covid19 deaths using Time Series Analysis (ARIMA MODEL) 

+ A Time Series Analysis (ARIMA Model) was used to predict the number of deaths in the US starting from August 1st – August 21st and August 1st – November 1st. The goal of this project was to compare our results with the projections that have been made by CNN and to get a deeper understanding of Time Series Analysis.

+ Used the data set from "Our World in Data", which consisted of 34,033 rows and 34 columns. Feature engineered the date column and transformed the class from a factor to date. In regards to data cleaning, I selected the US data points. Implemented the differencing technique to make our data stationary in order to conduct a time series analysis. Applied the Augmented Dickey-Fuller Test to make sure our data is stationary. Used the ARIMA model and its auto.arima function to conduct our projection.

+ Final model projected 18,589 deaths and CNN projected 19,000 deaths between August 1st and August 21st.

+ Between August 1st and November 1st my model projected 235,967 deaths and CNN projected 231,000 deaths. Actual death number according to Worldometer was 236,072.

Built with R and the following libraries: ggplot2, tidyverse, zoo, aTSA, ggplot2tseries, forecast, lubridate
