# World_Weather_Analysis

## Overview
Collect and present data to a travel tech company to help their customers find their ideal hotel based on their preferred travel criteria. Perform requests on the open weather map API and retrieve weather data by using the citipy module on more than 500 random longitudes and latitudes. Use MatPlotlib to create a series of scatter plots to show the relationship between the latitudes and variety of weather parameters for over 500 cities around the US. Also perform statistical analysis by using linear regression which will help predict the best time of the year to plan for vacations. Map out these places by using Google Maps and Places API. 

## Project Plan
- Task: Collect and analyze weather data across cities worldwide.
- Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
- Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.
1. Collect the Data
  - Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
  - Use the citipy module to list the nearest city to the latitudes and longitudes.
  - Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
  - Parse the JSON data from the API request.
  - Collect the following data from the JSON file and add it to a DataFrame:
    - City, country, and date
    - Latitude and longitude
    - Maximum temperature
    - Humidity
    - Cloudiness
    - Wind speed
2. Exploratory Analysis with Visualization
- Create scatter plots of the weather data for the following comparisons:
    - Latitude versus temperature
    - Latitude versus humidity
    - Latitude versus cloudiness
    - Latitude versus wind speed
- Determine the correlations for the following weather data:
    - Latitude and temperature
    - Latitude and humidity
    - Latitude and cloudiness
    - Latitude and wind speed
- Create a series of heatmaps using the Google Maps and Places API that showcases the following:
    - Latitude and temperature
    - Latitude and humidity
    - Latitude and cloudiness
    - Latitude and wind speed
3. Visualize Travel Data
- Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences:
  - Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
  - Create a heatmap for the new DataFrame.
  - Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
  - Store the name of the first hotel in the DataFrame.
  - Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.

## Additional Recommendations and Updates 
Specifically, recommend adding the weather description to the weather data that's already retrieved. Then, use input statements to filter the data for weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, a travel route between the four cities as well as a marker layer map is created.
