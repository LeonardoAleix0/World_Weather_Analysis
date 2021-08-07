# **World Weather Analysis**

## Overview of Project

This project’s objective is to apply analysis, visualizations, statistical skills and retrieve specific information from websites using application programing interface (API) from 2000 cities around the world.  The expected deliverables for this project are:
*	Retrieve Weather Data
*	Create a Customer Travel Destination Map
*	Create a Travel Itinerary Map

## Data Source Information
The data source used in this project was retrieved from Open Weather website, Google gmaps and the statistical analysis was performed with Citipy Library. 

## Software
Python 3.7.6, Pandas Library, Matplotlib, Jupyter Notebook, APIs and JSON Traversals.

## Results 

### Retrieve Weather Data 

The Weather Data was retrieved based on a set of 2,000 random latitudes and longitudes. Using the Open Weather map and retrieving the information with API, the cities weather data was collected with the current weather description and saved in a new DataFrame. 

![image](https://user-images.githubusercontent.com/86136535/128609492-06a86969-d119-4901-839f-f341d2d8fb6a.png)


 
### Create a Customer Travel Destination Map 

Using customer weather preferences, potential travel destinations were identified along with nearby hotels. The destinations are identified with a marker layer map with pop-up markers. 


![image](https://user-images.githubusercontent.com/86136535/128609548-fd442b70-d6a2-4828-a5f6-518193f91831.png)



### Create a Travel Itinerary Map

Using Google Directions API a travel route was created to display positional coordinate between four cities chosen by the customer. 


![image](https://user-images.githubusercontent.com/86136535/128609660-54ef1d93-dceb-4472-a3fc-82bfa38961b2.png)


A marker layer map with pop-up was added to provide customized information to the user describing the name of the city, country, hotel and current weather description. 

![image](https://user-images.githubusercontent.com/86136535/128609728-32bb1b07-e043-4f8b-a19a-2f3dc207504f.png)


  










