# Applied-Data-Science-Capstone

## Peer-graded Assignment: Capstone Project - The Battle of Neighborhoods

_Lackeshwar Bachan_  
_IBM Coursera _
 

Now that you have been equipped with the skills and the tools to use location data to explore a geographical location, 
over the course of two weeks, you will have the opportunity to be as creative as you want and come up with an idea to 
leverage the Foursquare location data to explore or compare neighborhoods or cities of your choice or to come up with a 
problem that you can use the Foursquare location data to solve.


## 1) Introduction/Business Problem

Clearly define a problem or an idea of your choice, where you would need to leverage the Foursquare location data to 
solve or execute. Remember that data science problems always target an audience and are meant to help a group of 
stakeholders solve a problem, so make sure that you explicitly describe your audience and why they would care about 
your problem.

**_The purpose of this project to assist persons looking to open a new Indian restaurant in New York City to choose the right location.
This would be done by providing data about the income and population of each neighbourhood as well as the competitors already present in 
the same regions._**

**_Questions that can be asked using the above mentioned datasets_**
&ndashWhat is best location in New York City for Indian Cuisine ?
&ndashWhich areas have potential Indian Resturant Market ?
&ndashWhich all areas lack Indian Resturants ?

## 2) Data

Describe the data that you will be using to solve the problem or execute your idea. Remember that you will need to use 
the Foursquare location data to solve the problem or execute your idea. You can absolutely use other datasets in 
combination with the Foursquare location data. So make sure that you provide adequate explanation and discussion, 
with examples, of the data that you will be using, even if it is only Foursquare location data.

**_For this project we need the following data : _**

**_New York City data that contains list Boroughs, Neighborhoods along with their latitude and longitude._**
Data source : https://cocl.us/new_york_dataset
Description : This data set contains the required information. And we will use this data set to explore various neighborhoods of new york city.
**_Indian resturants in each neighborhood of new york city._**
Data source : Fousquare API
Description : By using this api we will get all the venues in each neighborhood. We can filter these venues to get only indian resturants.
**_GeoSpace data_**
Data source : https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm
Description : By using this geo space data we will get the New york Borough boundaries that will help us visualize choropleth map.