# World Weather Analysis


## Project overview
The goal of the project is to collect weather data on worldwide cities through API request and together with google map, analyze the data to help recommend the ideal cities, hotels and time of the year to take a vacation.


## Method used.

The data collection process includes:
•	Generating random latitudes and longitudes
•	Used OpenWeatherMap API to request weather information.
•	API request resulted in JSON data. 
•	Google maps API request data


![Capture](https://user-images.githubusercontent.com/75961117/112777839-2a182000-9011-11eb-97c7-cdfd07fba051.PNG)

## Results


![WeatherPy_travel_map](https://user-images.githubusercontent.com/75961117/112777965-6cd9f800-9011-11eb-8051-049fe1a64fde.png)


![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/75961117/112778037-a3177780-9011-11eb-8f62-370d3c6ccc77.png)



API data in JSON format was filtered and converted into dataframes which was exported into csv format.
The dataframes were used to generate heatmaps and in conjunction with google maps, identified various cities and their weather conditions. 
Based on the analysis, an ideal vacation itinerary can be generated.
