Tamara Hundich

  10/30/2023

  Michigan State University edX Data Analytics Bootcamp 

 API Challenge 6: WeatherPy and VacationPy 

## Requirements
Part 1: WeatherPy
  - Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
    - To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code.   
      - Next, you'll create a series of scatter plots to showcase the following relationships:
            - Latitude vs. Temperature
            - Latitude vs. Humidity
            - Latitude vs. Cloudiness
            - Latitude vs. Wind Speed
  - Requirement 2: Compute Linear Regression for Each Relationship
    - To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.
      - You should create the following plots:
            - Northern Hemisphere: Temperature vs. Latitude
            - Southern Hemisphere: Temperature vs. Latitude
            - Northern Hemisphere: Humidity vs. Latitude
            - Southern Hemisphere: Humidity vs. Latitude
            - Northern Hemisphere: Cloudiness vs. Latitude
            - Southern Hemisphere: Cloudiness vs. Latitude
            - Northern Hemisphere: Wind Speed vs. Latitude
            - Southern Hemisphere: Wind Speed vs. Latitude
      After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

Part 2: VacationPy 
      - Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
      - Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:
            - A max temperature lower than 27 degrees but higher than 21
            - Wind speed less than 4.5 m/s
            - Zero cloudiness
      - Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
            - For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
            - Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:
    
## Installation and Configuration 
	- Python, geoViews, geoPandas, Geoapify API, OpenWeatherMap API, and Jupiter Notebook. 
	
	- Files included with repository include the CSV file codes, README, figures from generated data, and output data. HTML links also included to show the maps incase Visual Studio Code cannot generate the maps. 
