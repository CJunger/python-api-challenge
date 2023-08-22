# python-api-challenge
Python API Challenge for Data Analytics Bootcamp .
Using Python requests, APIs, and JSON traversals to answer the question:
"What is the weather like as we approach the equator?"

##Instructions
The activity has two deliverables, 1.WeatherPy and 2.VacationPy.

In WeatherPy I used a Python script to visualize the weather of 500 cities with varying distances from the equator. I used citipy Python library (https://pypi.python.org/pypi/citipy) and OpenWeatherMap API (https://openweathermap.org/api) and provided starter code to general the random coordinates and nearest city to the provided latitude and longitude. 

I then created plots to show the relationship between the weather variables and Latitude by using OpenWeather API to retrieve weather data from the cities generated by the starter code.  

###Latitude vs. Temperature

![image](https://github.com/CJunger/python-api-challenge/assets/131617662/35e2b51b-6ed8-4990-9257-2caef81a93b2)

###Latitude vs. Humidity

![image](https://github.com/CJunger/python-api-challenge/assets/131617662/5ccdd468-8816-431b-9949-0a64216cc38e)

###Latitude vs. Cloudiness

![image](https://github.com/CJunger/python-api-challenge/assets/131617662/775b9d46-78f6-4d95-ae0f-dffd6b15a6ab)

###Latitude vs. Wind Speed

![image](https://github.com/CJunger/python-api-challenge/assets/131617662/9e31b1fb-ccf6-4d37-88e6-8a897821c97a)

Next I computed the linear regression for each relationship by creating a fuction and separated the plots into Norther Hemisphere vs. Southern Hemisphere. I then created a series of scatter plots that included the linear regression line, the model's formula, and the r values:

Northern Hemisphere: Temperature vs. Latitude
Southern Hemisphere: Temperature vs. Latitude
Northern Hemisphere: Humidity vs. Latitude
Southern Hemisphere: Humidity vs. Latitude
Northern Hemisphere: Cloudiness vs. Latitude
Southern Hemisphere: Cloudiness vs. Latitude
Northern Hemisphere: Wind Speed vs. Latitude
Southern Hemisphere: Wind Speed vs. Latitude

2: VacationPy
I used Jupyter notebooks, the geoViews Python library, and the Geoapify API to create map visualizations.

Using the VacationPy.ipynb starter code I:

Created a map that displays a point for every city in the city_data_df DataFrame with the size of the point correlating to the humidity in each city.

Humidity map
Narrowed down the data frame to ideal conditions and created a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
Using Geoapify API to find the first hotel located within 10,000 meters of your coordinates for each city.
Added the hotel name and the country as additional information in the hover message for each city on the map.







