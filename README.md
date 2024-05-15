# python-api-challenge
# Instructions
This activity is broken down into two deliverables, WeatherPy and VacationPy.

# Part 1: WeatherPy
In this deliverable, a Python script is created to visualise the weather of over 500 cities of varying distances from the equator. Using the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site.

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
Using the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. 

Plots to showcase the following relationships:
  Latitude vs. Temperature
  Latitude vs. Humidity
  Latitude vs. Cloudiness
  Latitude vs. Wind Speed

# Then
Compute Linear Regression for Each Relationship
Create a series of scatter plots. 
Sample scatter plot with the linear regression line.

Included plots:
Northern Hemisphere: Temperature (C) vs. Latitude
Southern Hemisphere: Temperature (C) vs. Latitude
Northern Hemisphere: Humidity (%) vs. Latitude
Southern Hemisphere: Humidity (%) vs. Latitude
Northern Hemisphere: Cloudiness (%) vs. Latitude
Southern Hemisphere: Cloudiness (%) vs. Latitude
Northern Hemisphere: Wind Speed (m/s) vs. Latitude
Southern Hemisphere: Wind Speed (m/s) vs. Latitude

# Part 2: VacationPy
Using the weather data skills to plan future vacations with the geoViews Python library, and the Geoapify API.

Create a map that displays a point for every city in the city_data_df DataFrame.
  Humidity map
    Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:
    A max temperature lower than 27 degrees but higher than 21
    Wind speed less than 4.5 m/s
    Zero cloudiness

# Then
Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
Using the Geoapify API to find the first hotel located within 10,000 metres of your coordinates.
Adding the hotel name and the country as additional information in the hover message for each city in the map.

