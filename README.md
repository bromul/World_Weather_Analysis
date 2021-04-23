# World_Weather_Analysis

In this project, in order to help a travel site, we were tasked with finding random cities around the world, using APIs to find their local weather conditions and hotels, and create a short itinerary for a potential traveller in a country.

## Weather_Database

Within this folder, one will find code showing how we generated random latitudes and longitudes, converted those into the nearest cities, and then recorded local weather conditions. 

Additionally, one will find the CSV file we produced from our generated data.

## Vacation_Search

Within this folder, one will find code showing how we can ask a customer what their preferred maximum and minimum temperatures are and narrow the potential results for travel destinations. Then, we looked into each of the customer's preferred cities and found a hotel in the area. 

Further, there is a CSV we produced with all the customer's preferred cities, general information about the cities, and the names of hotels, as well as a screenshot of a map we generated from the preferred cities dataframe. 

## Vacation_Itinerary

Within this folder, one will find code showing how we used the customer's preferred cities to produce an itinerary - in this case a travel route within a single country, Sri Lanka.

Moreover, one will also find two maps generated during this process. The first is the travel route in question, with each city marked as stops on the trip. The second is a map without the travel route, but with markers that provide the name of a hotel in the city, the city name, the country code, and the current weather and temperature (in Fahrenheit).
