# CabBookingSystemPrediction

BACKGROUND:

Cab booking system is the process where renting a cab is automated through an app throughout a city. Using this app,people can book a cab from one location to another location.  Being a cab booking app company, exploiting theunderstanding ofcab supply and demand could increase the efficiency of their service and enhance user experience by minimizing waiting time. Objective of this project is to combine historical usage pattern along with the open data sources like weather data to forecast cab booking demand in a city.

PROCESS FLOW:

You will be provided with hourly renting data span of two years. Data is randomly divided into trainand testset. You must predict the total count of cabs bookedin each hour covered by the testset, using the information available prior to the booking period.You need to append the train_labeldataset to train.csv as ‘Total_booking’ column.

Please find the descriptions of the columns present in the datasetas below.

  datetime-hourly date +timestamp 
  
  season-spring, summer, autumn, winter
  
  holiday-whether the day is considered a holidayworkingday-whether the day is neither a weekend nor holiday
  
  weather-Clear , Cloudy,  Light Rain, Heavy 
  
  temp-temperature in Celsius
  
  atemp-"feels like" temperature in Celsius
  
  humidity-relative humidity
  
  windspeed-wind speed
  
  Total_booking-number of total booking

Task1:

  1.Visualize data using different visualizations to generate interesting insights.
  
  2.Outlier Analysis
  
  3.Missing value analysis
  
  4.Visualizing Total_booking Vs other features to generate insights
  
  5.Correlation Analysis

Task2:

  1.Feature Engineering
  
  2.Grid search
  
  3.Regression Analysis
  
  4.Ensemble Model
