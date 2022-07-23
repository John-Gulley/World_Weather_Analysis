# World_Weather_Analysis

# Project Overview
  In this project, we will practice your analysis, visualization, and statistical skills by retrieving and analyzing weather data for a hypothetical travel company, PlanMyTrip.
  
#Summary
  For this project, using API's we generated a large amount of random Latitude and Longitude coordinate pairs across the world, to learn large data usage. We then found the closest city to each of those coordinate pairs. We then retrieved, collected, and cleaned weather data from each city coordinate pair. The weather data was then used to help prospective vacationers find a city and hotel that meet their weather preferences. We then added weather description to the weather data. Weather presences were added to identify ideal travel destinations and hotels nearby. Four cities were chosen to create a travel itinerary. Using Google Maps Directions API, a travel route was created between those four cities and a marker layer was added to the map.
  
#Retrieving Weather Data
  The random Latitude and Longitude coordinates were used to create a list of cities as well as the nearest city to each pair, adding a marker on the map. An empty list was then created to hold weather data and a loop was added to iterate through all the cities said list. After that, an API request was run to obtain City, Country, and multiple weather conditions. This information was then saved into a new DataFrame.

#Creating a Travel Itinerary Map
  Using all the information gathered above, 4 cities were selected to create an Travel Itinerary route. The loc method was utilized to create DataFrames for each of the four cities. The latitude and longitude pairs from each city were found using the "to_numpy" function. These latitude-longitude pairs were used to create a direction layer map. 
  
![Vacation_Itinerary_image](https://user-images.githubusercontent.com/102339838/180623037-caffdbc5-9b8d-44c4-9029-4d01b1247502.png)

Info box was created to display hotel, city, country, weather description and maximum temperature. And a marker layer was created to display this information. 

![Vacation_Itinerary_image2](https://user-images.githubusercontent.com/102339838/180623083-fc3bf9a5-ed33-41ea-82aa-5080b50b8c40.png)

#Findings
  This project can now be used to filter down specific weather preferences and create itineraries for traveling based on those preferences.
