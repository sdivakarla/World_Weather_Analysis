# Travel Planning with Weather Data

Using publicly available weather data, travelers can find locations based on weather preferences. Then, using Google Maps Directions, an itinerary with the travel route can be displayed. 

# Overview

Developing a presentation of travel data for required multiple steps: 

1. Accessing weather data from openeweather.org and randomly selected 2000 locations based on computer generated latitude and longitudes. 
2. Getting the nearest unique city using the citypy module in Jupyter Notebook. 
3. The weather database includes information, such as maximum temperature, percent humidity, percent cloudiness, wind speed and weather description. 
4. Using the Google API nearby search, located hotels in each of the cities. 
5. Using user input of preferred minimum and maximum temperatures, then maps can be generated of locations within the preferred temperature zones. 
6. Selecting locations, then a travel route can be calculated. 

# Results


A map of the cities locations generated between a minimum temperature of 75 degrees Fahrenheit and a maximum of 90 degrees Fahrenheit is shown below. The markers are clickable to get the hotel name, city name, country code, maximum temperature and weather description at the time of the analysis. 
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/98054953/162783170-b02f675b-dae1-481a-a718-1d87c32c926f.png)

A personal travel itinerary was also made for a trip in Mexico with the travel route as well as hotel names and weather information. 
![WeatherPy_Travel_map](https://user-images.githubusercontent.com/98054953/162784765-240eec7f-97dd-433c-aa7f-9256750ba812.png) ![WeatherPy_Travel_map_Markers](https://user-images.githubusercontent.com/98054953/162784789-86357142-884c-44d0-8aba-6133b3e58cbd.png)



# Summary 

Using data from publicly available sources, it is possible to generate personalize weather and travel maps.  The process can be further modified to search for any of the criteria available in the database.  
