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

API data in JSON format was filtered and converted into dataframes which was exported into csv format.
The dataframes were used to generate heatmaps and in conjunction with google maps, identified various cities and their weather conditions. 
Based on the analysis, an ideal vacation itinerary can be generated.
