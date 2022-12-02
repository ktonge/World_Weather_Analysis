# World_Weather_Analysis

## Purpose
We were tasked with working for fictional a fictional travel ap.  This project uses a combination of OpenWeatherMap and Geoapify API keys to pull weather information as well as distance and travel information for a series of chosen cities.

## Method
The basic structure of this code created a list of randomized latitudes and longitudes.  From those coordinates we used citipy to get the city names, from there we used APIs from OpenWeatherMap to pull the weather information for this list of cities.  We removed any latitudes and longitudes that did not correspond with a city.  We created a data frame containing the city name, country, latitude, longitude, maximum temperature, and weather description. 

A user input field prompts the user to input the maximum and minimum prefered temperature, in this case we used cities with a maximum temperature between 70 and 90 degrees farenheit. After filtering the locations based on maximum temp,we used Geoapify to add in a column with hotel information for each of those cities.  We removed any cities in which no hotel was present. We presented that information on a map below.

![map1](https://github.com/ktonge/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

(There is an additional saved photo named WeatherPy_vacation_map_drop_down, which shows that the map provides the hotel and weather information for the city when hovering above it.)  

## Practicing with Plots
From our final list of cities I picked some random locations in Peru to practice plotting maps.  The map below shows a trip between four cities: beginnging and ending in Pementel, visiting Paita, Hualmay, and Pisco along the way.  

![map2](https://github.com/ktonge/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_Travel_map.png.png)

To create this image I created a map both showing the individual cities on the map, as well as a map showing the route between them, and then combined them.  
