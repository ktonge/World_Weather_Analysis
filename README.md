# World_Weather_Analysis
This assignment for bootcamp was a practice in APIs, I found this module to be the most exciting. 

##Purpose and Tools
We were tasked with working for fictional a fictional travel ap.  This project uses a combination of OpenWeatherMap and Geoapify API keys to pull weather information as well as distance and travel information for a series of chosen cities.

##Method
The basic structure of this code created a list of randomized latitudes and longitudes.  From those coordinates we used citipy to get the city names, from there we used APIs from OpenWeatherMap to pull the weather information for this list of cities.  We removed any latitudes and longitudes that did not correspond with a city.  We created a data frame containing the city name, country, latitude, longitude, maximum temperature, and weather description. 

A user input field prompts the user to input the maximum and minimum prefered temperature, in this case we used cities with a maximum temperature between 70 and 90 degrees farenheit. After filtering the locations based on maximum temp,we used Geoapify to add in a column with hotel information for each of those cities.  We removed any cities in which no hotel was present.  

##Practicing with Plots
From our final list of cities I picked some random locations in Peru to practice plotting maps.  For our first map we showed each of the 
