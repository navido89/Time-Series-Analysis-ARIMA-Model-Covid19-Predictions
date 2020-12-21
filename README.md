<img src="images/coronavirus-covid.png">

# Predicting number of Covid19 deaths using Time Series Analysis (ARIMA MODEL) 
**Project Status: Completed**

The purpose of this project is to predict the number of deaths in the US starting from August 1st – August 21st and August 1st – November 1st. We also compare our results with the projections that have been made by CNN.

## Methods Used
+ Time Series Analysis 
+ Arima Model
+ Data Visualization
+ Data Cleaning 

## Technologies:
+ R
+ ggplot2
+ tidyverse
+ zoo
+ aTSA
+ ggplot2tseries
+ forecast
+ lubridate

## Project Description:
+ Used the data set from "Our World in Data", which consisted of 34033 rows and 34 columns. 
+ Feature engineered the date column and transformed the class from a factor to date. 
+ In regards to data cleaning, I selected the US data points. 
+ Implemented the differencing technique to make our data stationary in order to conduct a time series analysis. 
+ Applied the Augmented Dickey-Fuller Test to make sure our data is stationary. 
+ Used the ARIMA model and its auto.arima function to conduct our projection.

## Project Results:
+ Final model projected 18589 deaths and CNN projected 19000 deaths between August 1st and August 21st.
+ Between August 1st and November 1st my model projected 235967 deaths and CNN projected 231000 deaths. Actual death number according to Worldometer was 236072.

## Project View:
<a href="https://nbviewer.jupyter.org/github/navido89/Time-Series-Analysis-ARIMA-Model-Covid19-Predictions/blob/master/Predicting%20number%20of%20Covid19%20deaths%20using%20Time%20Series%20Analysis%20%28ARIMA%20MODEL%29%C2%B6.ipynb" target="_blank">Go</a>


