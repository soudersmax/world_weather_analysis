# World Wide Weather Project

## Task

Collect and analyze weather data across cities worldwide by creating a Pandas DataFrame with 500 + of the world's unique cities and their weather data in real time. 



## Purpose

Client will use the data to recommend ideal hotels based on clients' weather preferences



## Method

1. Collect the data
   * Use NumPy module to generate more than 1500 random latitudes and longitudes
   * Use the citipy module to list the nearest city to the latitudes and longitudes
   * Use the OpenWeatherMap API to request the current weather data from each unique city in your list
   * Parse the JSON data from the API request
   * Collect specific data from the JSON file and add it to a DataFrame
2. Exploratory Analysis with Visualization
   * Create exploratory scatter plots 
   * Determine correlations for specific weather features
   * Create a series of heatmaps using the Google Maps and Places API that showcases said relationship
3. Visualize Travel Data
   * Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences





