# Exploring Torino's Municipalities and Venues

![](https://github.com/RachaelKilonzo/Exploring-Torino-Municipalities/blob/main/images/royal%20library%20of%20turin.png)

## Introduction

This project aims to present an analysis of the municipalities within the Metropolitan City of Turin, Italy, focusing on the categorization of nearby venues using geolocation data and clustering techniques. The data was sourced from
[Wikipedia](https://en.wikipedia.org/wiki/List_of_municipalities_of_the_Metropolitan_City_of_Turin) and [Foursquare API](https://location.foursquare.com/developer/), with the primary goal of exploring the diversity and distribution of venues across different municipalities.

## Data Collection

### Municipalities Data
- **Source**: Wikipedia's list of municipalities in the Metropolitan City of Turin.
- **Method**: Data was scraped using `BeautifulSoup` and included municipality names, population, and area.
- **Enhancement**: Geolocation data (latitude and longitude) was added using the `geopy` library.

### Venue Data
- **Source**: Foursquare API.
- **Method**: For each municipality, venues within a 1 km radius were collected.
- **Details**: Venue name, category, and location were extracted for analysis.
![](https://github.com/RachaelKilonzo/Exploring-Torino-Municipalities/blob/main/images/venues.PNG)

## Analysis

### Venue Categorization
- **Objective**: Identify and categorize the top 10 venue types across all municipalities.
- **Visualization**: A pie chart was created to display the proportion of each category.

### Clustering
- **Technique**: K-Means clustering was applied to group municipalities based on venue categories.
- **Evaluation**: The silhouette score was used to determine the optimal number of clusters.
- **Result**: Municipalities were grouped into clusters that reflected similar venue distributions.

## Results

### Venue Distribution
- **Top Venue Types**: The most common venues included Eating joints, Plazas and Fuelling Stations 
- **Municipality Insights**: Larger municipalities tended to have a higher diversity of venues, while smaller ones were more specialized.


### Clustering Outcomes
- **Cluster Characteristics**: Each cluster represented a different mix of venue types, with some clusters dominated by dining options and others by recreational spaces.
- **Visualization**: A Folium map was generated to visualize the clusters, with each municipality color-coded by its cluster.
![](https://github.com/RachaelKilonzo/Exploring-Torino-Municipalities/blob/main/images/torino_clusters_map.PNG)

## Conclusion

The analysis revealed distinct patterns in venue distribution across Torino's municipalities. These insights could inform decisions related to urban planning, tourism, and business development within the metropolitan area.

## Future Work

- **Time-Based Analysis**: Extend the study to consider temporal changes in venue popularity.
- **Demographic Integration**: Incorporate demographic data for a more comprehensive analysis.
- **Alternative Clustering Methods**: Experiment with other clustering algorithms to explore different patterns.


