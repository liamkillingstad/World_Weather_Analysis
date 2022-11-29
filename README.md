# World_Weather_Analysis

## Module 6: Planning my Trip with Python

This assignment required work for the PlanMyTrip App. The app is built by a top travel company specialized which specializes in the hotel industry. The app is desifned to allow for travelers to choose their highest desired destinations, anywhere in the world, based specifically on their weather preferences.

We were sourced to build the app specifically using API calls from: 
- Google Maps
- Open Weather

### This project consists of three modules.

1. Weather Database
In this specific module we were required to retrieve 2000 random geographic coordinates and use the CityPy module to define the closest city names based on those specific coordinates. Once city names were stored in a list, the Open Weather API was used to request JSON weather data from a website. After cleaning the data, final results were transformed into Pandas data frame and stored in CSV file.

2. Vacation Search
In this module I used input function to take and store potential customer preferred minimum and maximum temperatures. Based on this input I used Pandas loc method on Weather Database file to filter the data. Next, I used Google Maps APIs to retrieve hotel names. After cleaning the data, the data frame was exported to CSV file and then used to generate a graphic demonstrating the city locations. 

3. Vacation Itinerary
In this module 4 hotel destinations were selected that customers would most likely be interested in visting based on their weather preferences. Based on selection criteria that were extracted using coordinates with the to_numpy() function and used Google Directions API to connect and plot those points via selected traveling mode.

## Documentation

Software: Python 3.10.5, Jupyter Notebook 6.4.8
