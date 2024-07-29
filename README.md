# PYTHON - API Project

## Overview
This project consists of two main parts: WeatherPy and VacactionPy. The objective is to analyze weather data from over 500 cities worldwide and use this data to plan potential vacaion destinations. We will utilize various Python libraries such as citypy, OpenWeatherMap API, Geoapify API, and geoViews to gather, visualize, and analyze the data. 

### PART 1 :  WeatherPy

In  this deliverable, Python script is created to visualize the weather of over 500 cities of varying distances from the equator. This part involves  retrieving weather data using the OpenWeatherMap API and visualizing the relationships between different weather variables and latitude.

### PART 2 : VacationPy

In VacationPy, the weather data from WeatherPy is used to plan vacations based on ideal weather conditions. Interactive map visualizations is created to identify suitable vacation destinations and find nearby hotels using the Geopify API.

## Key Components:
### WeatherPy
1. **Retrieved Weather Data**: Used the OpenWeatherMap API to get weather data for over 500 cities.
2. **Visualized Data**: Created scatter plots to show the relationships between:
    - Latitude and Temperature
    - Latitude and Humidity
    - Latitude and Cloudiness
    - Latitude and Wind Speed
3. **Linear Regression Analysis**: Computed linear regressions for the above relationships, separating data into the Northern and Southern Hemispheres.

### VacationPy
1. Created City Map: Displayed a map with points representing each city, with the size of each point indicating the city's humidity.
2. Filtered Ideal Conditions: Narrowed down the cities to those with ideal weather conditions based on specified criteria.
3. Found Nearby Hotels: Used the Geopify API to locate the nearest hotel within 10,000 meters of each city's coordinates.
4. Interactive Map: Created an interactive map displaying the cities with hover messages showing the hotel name and country.
