![Google Maps and Open Weather API](https://user-images.githubusercontent.com/93561950/163034582-f035085a-0b6b-4177-8731-24e9b0074ea1.png)
# Python-API-Challenge

### Methods Used
Scatterplots, Linear Regression

### Technologies
Python, Matplotlib, gmaps

### Featured Notebooks and files
VacationPy - Using GoogleMap API calls, ideal weather conditions pulled from randomly selected cities around the world. These cities are plotted with a heatmap and labeled with a hotel within 5000km of the city location.
![Heat Map with Hotels Screen Shot](https://user-images.githubusercontent.com/93561950/163036071-b6a28157-9fff-408e-9e5d-3d9bbe4a4384.png)


WeatherPy - Using OpenWeather API calls, current weather data from randomly selected cities around the world is analyized. 

weather.csv - CSV file with all weather data from randomly selected cities.

#### Analysis and Obseved Trends
The strongest correlation observed was between latitude & maximum temperature of a city in the Northern Hemisphere, suggesting the higher the latitude, or the more north you travel, the colder it gets.

![MaxTempRegressionNorthHemi](https://user-images.githubusercontent.com/93561950/163036299-8d3d7f81-16a6-41fe-af81-0a9092d4f372.png)


This is not neccesarily the case in the Southern Hemisphere. No correlation observed between city location and maximum temperature in the Southern Hemisphere cities.

![MaxTempRegressionSouthHemi](https://user-images.githubusercontent.com/93561950/163036319-186de5bd-d1e8-4a8a-ad7a-0aafc0a7f996.png)


Cloudiness, humidity, and wind speed were also not dependent on city location. 

![CloudRegressionNorthHemi](https://user-images.githubusercontent.com/93561950/163036359-709426be-67e4-48ad-a8ab-9fa7d734e640.png)


#### Suggestions for further analysis
Compare current weather data with weather data from the 40 year archive to examine potential effects of global warming.
