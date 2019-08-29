# PythonAPI_Homework
Unit 6 Assignment - What's the Weather Like? 

![Equator](world.gif)

## WeatherPy

This project required creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. The data will be sourcesd from the [OpenWeatherMap API](https://openweathermap.org/api). Using Python to create API calls and read the JSON information into dataframes. 

The objective was to build a series of scatter plots to showcase the relationship of a city's weather data and geographical location.

## WeathPy_Complete notebook contains:

* Randomly select 500+ unique (non-repeat) cities based on latitude and longitude using a series of successive API calls.
* Print log of each city as it's being processed with the city number and city name.
* Queries for explore the weather data on each of the cities that explore:
    * Temperature (F) vs. Latitude (saved as Figure1)
    * Humidity (%) vs. Latitude (saved as Figure2)
    * Cloudiness (%) vs. Latitude (saved as Figure3)
    * Wind Speed (mph) vs. Latitude (saved as Figure4)

## Additional Files:
* CSV of all city weather data retrieved from API calls 
* PNG images for each scatter plot

## Analysis
Using the WeatherMap API to pull weather data from 500+ random cities around the world to determine correlation between a city's location and weather. A city that is closer to the equator is more likely to have higher tempatures than cities further from the equator. 
* Specifically, out of the random cities pulled, those sitting with 20 lat seem to have a higher tempature than cities on the equator at this time.
* Based on the data, there are more cities with humidity in the Northern Hemisphere at this time of year.
* Wind Speed seems to be mild for the majority cities pulled for this time of year.

