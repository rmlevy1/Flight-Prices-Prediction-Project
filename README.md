# Predicting Flight Prices From Beijing <-> Shanghai

## Goal: 
Create a prediction model to predict flight prices from Beijing to Shanghai and vice versa, in order to help prospective flyers take advantage of variables that lead to cheaper ticket prices. 

In our project we set out to predict flight prices from Beijing to Shanghai and vice versa. 
We explored the following data sets(https://www.kaggle.com/lpisallerl/air-tickets-between-shanghai-and-beijing#sha-pek.csv) from kaggle, which contained prices of tickets purchased for flights from January 2019 to August 2019. 

Data Cleaning/Feature Engineering 

Target Variable - Prices
Independent Variables 
  - Layover - 0 implying a direct flight, 1 implying a non-direct flight
  - cabinClass - class the seat was in; F-First class, C-Business class, Y-Economy 
  - dateDifference - days in advance ticket was purchased 
  - TODD - Time of day departure took place; M - 6am-Noon; A - Noon-6pm; N - 6pm-Midnight
  - Month - month that the departing flight happened
  - DOW - Day of week the flight departed
  - MOPD - Month the ticket was purchased
  - DOPD - Day of the week the ticket was purchased
  - TOPD_L - Time of day ticket was purchased; EM - Midnight-6am; M - 6am-Noon; A - Noon-6pm; N - 6pm-Midnight
  
  Models 
  We ran a Ridge, Lasso and OLS
  - OLS provided the best results with an RMSE of 132 and R^2 of 0.71 
  
  Actionable Insights
  - Provided in the pdf file attached; check pages 4 & 8.
  
  Further Exploration
  - Run the model on a data set containing ticket prices for a large time span (larger time span and full year). 
This project was completed by Jigme Sherpa and Raam Levy.
