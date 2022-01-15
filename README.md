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
Foursquare data is commonly used to power location data for Apple, UberFor this business problem I have used, as a part of the assignment, the Foursquare API to retrieve information about the popular spots around these 5 Major Districts of Tokyo. The popular spots returned depends on the highest foot traffic and thus it depends on the time when the call is made. So we may get different popular venues depending upon different time of the day. The call returns a JSON file and we need to turn that into a data-frame. Here I’ve chosen 100 popular spots for each major districts within a radius of 1 km. Below is the data-frame obtained from the JSON file that was returned by Foursquare —
