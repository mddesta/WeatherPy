
# WeatherPy

### Background

Created a Python script to analyze and visualize the weather of 500+ cities and investigate the relationship between latitude and weather attributes. Below are the graphs created based on the data obtained from the OpenWeatherMap API. 

### Technologies

* Jupyter Notebook 
* Pandas
* Visualization 
* numpy 
* requests
* json
* time

### Visualization

1. Latitude vs. Temperature Plot:

![Temperature Plot](https://github.com/mddesta/WeatherPy/blob/master/Output/Temperature.png)

2. Latitude vs. Humidity Plot:

![Humidity Plot](https://github.com/mddesta/WeatherPy/blob/master/Output/Humidity.png)

3. Latitude vs. Cloudiness Plot:

![Cloudiness Plot](https://github.com/mddesta/WeatherPy/blob/master/Output/Cloudiness.png)

4. Latitude vs. Wind Speed Plot:

![Wind Speed Plot](https://github.com/mddesta/WeatherPy/blob/master/Output/Wind%20Speed.png)

# Conclusions

1. Temperature increases as we get closer to the equator. However, the highest temperature is recorded near the 20  degree mark. Further analysis and data is needed to establish the cause of this. 

2. Cloudiness and humidity do not show strong correlation to latitude. These findings suggest that there are other factors impacting these variables. Example of such potential factors are altitude and time of the day. 

3. As one moves away from the equator, there are clusters of cities that experience 0% cloudiness. Other cluster points are 40% and 80% cloudiness. On the other hand, the analysis shows that, for the cities tested, wind speeds greater than 20mph are rare. 
