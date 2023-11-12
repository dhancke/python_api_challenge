# python_api_challenge
Week 6
# WeatherPy_DH
Overview of Requirements:

Part 1: WeatherPy
This task involved creating a Python script to visualise the weather of over 500 cities of varying distances from the equator. This required using the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site. using problem-solving to create a representative model of weather across cities.

For this part, you'll use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. The starter code will guide you through the process of using your Python coding skills to develop a solution to address the required functionalities.

Requirement 1: 
Showcasing the relationship between Weather Variables and Latitude the requirement was to use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code and then create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship
TThe requirement was to compute the linear regression for each relationship, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 

NThe scatter plots needed to include the linear regression line, the model's formula, and the r values. The following plots should be included:
- Northern Hemisphere: Temperature (C) vs. Latitude
- Southern Hemisphere: Temperature (C) vs. Latitude
- Northern Hemisphere: Humidity (%) vs. Latitude
- Southern Hemisphere: Humidity (%) vs. Latitude
- Northern Hemisphere: Cloudiness (%) vs. Latitude
- Southern Hemisphere: Cloudiness (%) vs. Latitude
- Northern Hemisphere: Wind Speed (m/s) vs. Latitude
- Southern Hemisphere: Wind Speed (m/s) vs. Latitude

There was a requirement to explain the linear regression and describe any relationships that are visable.

Part 2: VacationPy
This task involved using weather data skills to plan future vacations using Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The main task was to use the Geoapify API and the geoViews Python library and employ Python skills to create map visualisations. Here a map that displayed a point for every city in the city_data_df DataFrame. The size of the point needed to be the humidity in each city.

The Humidity map:
- The city_data_df DataFrame needed to be found to determine ideal weather conditions, For example:
- A max temperature lower than 27 degrees but higher than 21
- Wind speed less than 4.5 m/s
- Zero cloudiness

The Hotel map:
A new DataFrame called hotel_df to store the city, country, coordinates, and humidity was required.
- For each city, using the Geoapify API was required to find the first hotel located within 10,000 metres of the coordinates.
- The hotel name and the country as additional information in the hover message for each city in the map was required.

Hotel map questions to be answered:
- What is citipy used for? 
- Why would you use it in conjunction with the OpenWeatherMap API? 
- How would you do so?



