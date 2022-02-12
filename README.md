# world_weather_analysis

## Overview of World Weather Analysis

The purpose of this analysis is to create a create a weather database in order to visualize the data and give travelers the tools to narrow down vacation searches based on weather. Travelers will be able to view hotels in cities that fall within the requested temperatuire ranges and the ability to plan their itinerary.

## Weather Database

In order to create the weather database, Numpy is used to create a set of 2,000 longitude and latitude values. Citipy and the open weather map API are used to narrow down the longitute and latitude values that bring in a city. This data is then exported into a CSV file which is used for the Vacation Search and Itinerary.

![image](https://user-images.githubusercontent.com/91445591/153723451-8d988c0c-8475-4c8b-9dcc-5ace9df9321c.png)

## Vacation Search

Travelers are able to enter the temperatue range for their vacation search in order to bring in citites that fall within the specified range. Once the temperature range is entered, gmaps is used to display the city options. 

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/91445591/153723467-55e9b0b1-6006-489c-ae1b-e343c365b673.png)

## Vacation Itinerary

Travelers can create a vacation itinerary route to travel between the multiple cities. 

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/91445591/153723476-1d553e70-8233-4f75-afd5-419ed8a76c83.png)

![WeatherPy_travel_map](https://user-images.githubusercontent.com/91445591/153723474-ac04ae1e-694a-40bf-b4f0-edce7747aabc.png)
