# CU-06-python-api-challenge
## Description
Using APIs and JSON traversals to answer the question: How does the weather change as we approach the equator?
#### WeatherPy
We are tasked to create a py script to visualize the weather of 500 cities of varying distances from the equator using citipy and OpenWeatherMap API to create a representative model of weathers across different cities. 
#### VacationPy

## Approaches and Resources
#### WeatherPy
* Use OpenWeatherMap to plot the northern and southern hemispheres with linear regression lines:
  * Latitude vs Temperature
  * Latitude vs Humidity
  * Latitude vs Cloudiness
  * Latitude vs Windspeed

#### VacationPy
* Use weather data to plan future vacations using the geoViews and Geoapify API and create a map visualization.
  * Create a map for every city with humidity
  * Narrow down the df to find the ideal weather condition
  * Create a new df to store city, country coordinates and humidity.
  * Use Geoapify API to find the first hotel within 10,000m
  * Add hotel name
## Conclusions
* **There is a strong relationship between maxiumum temperature and latitude**
![alt-text](https://github.com/anderoos/CU-6-python-api-challenge/blob/main/output_data/Fig1.png)

## Limitations and recommendations

## Licensing 
This code has no license restrictions. Challenge materials are provided by the Columbia School of Engineering.
