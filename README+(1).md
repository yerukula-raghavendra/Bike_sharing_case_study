# Bike Sharing Demand Analysis - Linear Regression

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

**Goals :**
*  Develop a model to find the variables which are significant the demand for shared bikes with the available independent variables.
*  It will be used by the management to understand and manipulate the business strategy to meet the demand levels and meet the customer's expectations.
*  Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Table of Contents
* [Attribute Information](#attribute-information)
* [Libraries Used](#libraries-used)
* [Algorithms](#algorithms)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## Attribute Information
day.csv have the following fields:
*  instant: record index
*  dteday : date
*  season : season (1:spring, 2:summer, 3:fall, 4:winter)
*  yr : year (0: 2018, 1:2019)
*  mnth : month ( 1 to 12)
*  holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
*  weekday : day of the week
*  workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
	*  1: Clear, Few clouds, Partly cloudy, Partly cloudy
	*  2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
	*  3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
	*  4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
*  temp : temperature in Celsius
*  atemp: feeling temperature in Celsius
*  hum: humidity
*  windspeed: wind speed
*  casual: count of casual users
*  registered: count of registered users
*  cnt: count of total rental bikes including both casual and registered


## Libraries Used
- pandas
- matplotlib
- seaborn
- scikit-learn
- numpy
- warnings
- statsmodels


## Algorithms
- Linear Regression

## Conclusions

Based on the final model The Top 3 features contributing significantly towards the demands of share bikes are:

*  yr_2019 **(Positive correlation).**
*  atemp **(Positive correlation).**
*  mnth_3 **(Positive correlation).**




## Contact
Created by [@yerukula-raghavendra] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
