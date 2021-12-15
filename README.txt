# Project Name
> Outline a brief description of your project.
BoomBikes(bike-shareing) aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. 

The company wants to know:

1. Which variables are significant in predicting the demand for shared bikes.

2. How well those variables describe the bike demands

## Table of Contents
* This bike demand problem statement. Need to find the predication of bike demand fpor bbom bike company.

* python 3 and Git as CM(#technologies-used)

* Conclusion:
cnt(count of total rental bikes including both casual and registered)=0.395×temp+0.235×2019(Year)+0.052×Sep-0.151×windspeed -0.145×spring-0.072×July-0.274×Light_Snow-0.078×Mist

Top 3 features

Temperature in Celsius

year(2019)

month(september)

R-squared for test data set 0.787 and 0.824(#conclusions)


## General Information
Problem Statement: A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.

How well those variables describe the bike demands

Some data information

dteday : date
season : season (1:spring, 2:summer, 3:fall, 4:winter)
yr : year (0: 2018, 1:2019)
mnth : month ( 1 to 12)
holiday : weather day is a holiday or not
weekday : day of the week
workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
weathersit :
1: Clear, Few clouds, Partly cloudy, Partly cloudy
2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
temp : temperature in Celsius
atemp: feeling temperature in Celsius
hum: humidity
windspeed: wind speed
casual: count of casual users
registered: count of registered users
cnt: count of total rental bikes including both casual and registered
Steps:

Reading and Understanding the Data

Preparing data set for modeling, rescaleing(Traing vs Test data set)

Training the model

Residual Analysis

Predition and evalution on Test data set



## Conclusions
Conclusion:
cnt(count of total rental bikes including both casual and registered)=0.395×temp+0.235×2019(Year)+0.052×Sep-0.151×windspeed -0.145×spring-0.072×July-0.274×Light_Snow-0.078×Mist

Top 3 features

Temperature in Celsius

year(2019)

month(september)

R-squared for test data set 0.787 and 0.824


## Technologies Used
python 3 and Git as CM(#technologies-used)

numpy as np
pandas as pd 
matplotlib.pyplot as plt
seaborn as sns
sklearn
statsmodels.api as sm


## Acknowledgements
Give credit here.
Thanks to Ahamed class instructor for explaining the project


## Contact
Created by sandipan.kr@gmail.com


