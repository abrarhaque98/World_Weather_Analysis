# World_Weather_Analysis


### Overview of Project

This project was to create a travel itinerary amongst four points using the Google Maps API. 

It began with creating random latitudes and longitudes then finding cities near them, then retrieving the resulting cities weather data from the OpenWeatherMap API. The data retrieved for the cities were, latitude, longitude, max temp, humidity, cloudiness, wind speed, country, and current weather description.  Once that data was pulled it was formatted into a dataframe and converted into a csv file. 
![image](https://user-images.githubusercontent.com/85713568/137208571-e3cf3172-d354-49ae-abfe-a73d9b9f9b0d.png)

With that the next step was creating a little user input in which the user would input preferred max and min temperatures and the data would be sorted into another dataframe there after. 
![image](https://user-images.githubusercontent.com/85713568/137208718-a06df712-d36f-4983-b2f4-1ea3ad1e2117.png)

After that hotels within a 5000 meter radius to the filtered cities were searched for and any city not having a hotel in that radius was dropped. 

![image](https://user-images.githubusercontent.com/85713568/137209002-2cb3e3ee-7797-4bb4-bbfe-4996ee009900.png)

Moving forward the google maps API was used to visualize the locations around the globe. 

![image](https://user-images.githubusercontent.com/85713568/137209153-e406d94d-4661-4670-bc2f-df27e5d1f882.png)

Finally four locations were selected by choice and an itinerary for directions was visualized using the google maps API.

![image](https://user-images.githubusercontent.com/85713568/137209366-be5800dc-c429-4708-bab2-f65658a1eada.png)

![image](https://user-images.githubusercontent.com/85713568/137209412-5ca9f5c8-540f-46f1-a97a-10341204a058.png)




