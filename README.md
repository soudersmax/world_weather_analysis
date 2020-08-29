# World Wide Weather Project

## Task # 1 

Collect and analyze weather data across cities worldwide by creating a Pandas DataFrame with 500 + of the world's unique cities and their weather data in real time. 



### Purpose

Client will use the data to recommend ideal hotels based on clients' weather preferences



### Method

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
   * Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences (vacationpy.ipynb and weatherPy.ipynb)

## Task #2

Create a vacation itinerary based on input commands for maximum and minimum temperature preferences. 

### Purpose

Client will use the app to input temperature preferences, locate cities that fit those criteria, and locate hotels in those cities. 

### Method

1. Collect the weather data 
   * Use NumPy module to generate 2000 random latitudes and longitudes
   * Use the CityPy module to retrieve the nearest city
   * Perform API call with OpenWeatherMap
   * Parse JSON data from API request and add to new DataFrame
   * Stored in weather_database
2. Collect Customer preferences and use them to identify potential travel destinations
   * Use input statements for minimum and maximum temperature preferences
   * Filter DataFrame to provide potential hotels and locate nearby hotels
   * Display destinations on a marker layer map with pop-up markers
   * Stored in vacation_search
3. Create a travel Itinerary Map
   * Use Google Directions API to create a  travel itinerary to show the route between 4 cities from the potential destinations
   * Create a marker layer map with a popup marker for each city on the itinerary
   * Stored as vacation_itinerary