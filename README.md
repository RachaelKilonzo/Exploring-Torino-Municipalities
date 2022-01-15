# Exploring-Nairobi Restaurants
![Nairobi](https://user-images.githubusercontent.com/93233240/149614540-09bb5737-e3b2-4d92-b49b-b37c4588527c.jpg)
## Problem: Discovering Restaurants in Nairobi Residential Areas.
Nairobi is an perhaps the biggest economic hub in East and Central Africa. Here we will try to analyze  the restaurant scene in Kenya's capital.
## Clients that this may be of interest to.
- Business personnel who wants to invest or open a restaurant. 
- Freelancer who loves to have their own restaurant as a side business. 
- Data Scientists, who may want to implement similar projects.

## Data Preparation
### Scraping and getting coordinates
Scrapped the data from "https://hassconsult.co.ke/real-estate/images/HassLandIndexQ12021.pdf" with the help of Tabula and requests to create a data frame and found the longitude and latitude of Suburbs and Satelite towns of Nairobi using geocoder

## Using Foursquare Location Data:
Foursquare data is commonly used to power location data for Airbnb, Apple Maps, Samsung, TripAdvisor, Spotify, AccuWeather, and Uber. For this problem I have used the Foursquare API to retrieve information about 100 restaurants in a 1000 meter radius of suburban and satelite towns in Nairobi for analysis.

## Indian cuisine vs fast food restaurants
![satelites](https://user-images.githubusercontent.com/93233240/149623236-f787c993-95d9-49c1-9d9d-1898fc3a7556.png) vs ![suburbs](https://user-images.githubusercontent.com/93233240/149623238-b953646e-9f37-4ef9-9c2e-1fb01d118d02.png)

![indian food](https://user-images.githubusercontent.com/93233240/149623243-3ff16a83-2373-4d3c-bfb8-9b7b68bfdeb1.jpg)
![fastfood](https://user-images.githubusercontent.com/93233240/149623246-99f7c562-aea0-4ed3-8b2f-a09668e130ff.jpg)
