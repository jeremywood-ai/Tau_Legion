# Bike Sharing Demand Competition Lab
https://www.kaggle.com/c/bike-sharing-demand/data  

Lab Premise:
> You are provided hourly rental data spanning two years. For this competition, the training set is comprised of the first 19 days of each month, while the test set is the 20th to the end of the month. You must predict the total count of bikes rented during each hour covered by the test set, using only information available prior to the rental period.


For this lab, you would need to download train.csv and test.csv from kaggle.  
1. Go to the [URL](https://www.kaggle.com/c/bike-sharing-demand/data): https://www.kaggle.com/c/bike-sharing-demand/data
2. Sign-in / Register
3. Scroll down to Data Sources and download the *three* files

* train.csv
* test.csv
* sampleSubmission.csv

## Data Fields
**datetime** - hourly date + timestamp  
**season** -  1 = spring, 2 = summer, 3 = fall, 4 = winter 
**holiday** - whether the day is considered a holiday
**workingday** - whether the day is neither a weekend nor holiday
**weather**
1. Clear, Few clouds, Partly cloudy, Partly cloudy
1. Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
1. Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
1. Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog 
**temp** - temperature in Celsius
**atemp** - "feels like" temperature in Celsius
**humidity** - relative humidity
**windspeed** - wind speed
**casual** - number of non-registered user rentals initiated
**registered** - number of registered user rentals initiated
**count** - number of total rentals