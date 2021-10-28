# World-Weather-Analysis

## Overview of the analysis
The purpose of this module was to help the "PLANMYTRIP" company to collect and filter customer search data to present them with the best hotel that suits their tastes. The Pandas library was used to filter and save the cities in a Jupyter Notebook database to later graph and create trend lines for the climates of the cities, these cities were also mapped with all their characteristics using the google maps API to present them to customers.
For this challenge, a few changes were made to the application to improve it and take it to the next level. The first change was to add a description of the weather to the weather data that had already been retrieved. The second change was adding input statements to filter data based on customers' preferred climates, to identify nearby hotels. Finally, with the help of Google Maps Directions api, an itinerary was created with the route of 4 cities chosen by the client.

## Results
- For the **Deliverable 1**, a set of 2000 random latitudes and longitudes were generated, the closest city was retrieved, and an API call was made with OpenWeatherMap. With the meteorological data of the cities that were collected, the current meteorological description of each city was retrieved. Finally, a new DataFrame was created that contained the updated meteorological data and the file was exported into a "csv" type file.

![](https://github.com/Frankdiazw/World-Weather-Analysis/blob/main/Weather%20Database/Deliverable-1.png)

- Figure 1. Filtered DataFrame with meteorological data for each random city.

- For the **Deliverable 2**, input statements were used to retrieve the customer's climate preferences, then those preferences were used to identify potential travel destinations and nearby hotels. Finally, those destinations were displayed on a marker layer map with pop-up markers.

![](https://github.com/Frankdiazw/World-Weather-Analysis/blob/main/Vacation_Search/Deliverable-2.png)

- Figure 2. Marker layer map with pop-up markers of the filtered search from the client.

- For the **Deliverable 3**, the Google Directions API was used to create a travel itinerary showing the route between four cities chosen from the customer's possible travel destinations. Next, a marker layer map was created with a pop-up marker for each city in the itinerary.

![](https://github.com/Frankdiazw/World-Weather-Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

-Figure 3. Travel map for the 4 cities.

![](https://github.com/Frankdiazw/World-Weather-Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

-Figure 4. Travel map with markers for the 4 cities.
