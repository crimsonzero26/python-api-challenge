# Python API Challenge

### WeatherPy

In this section, you'll create a Python script to visualize the weather of 500+ cities of varying distance from the equator. To do so, you'll use a simple Python library, the OpenWeatherMap API, and your problem-solving skills to create a representative model of weather across cities.

The first requirement is to create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After each plot, add a sentence or two explaining what the code is analyzing.

The second requirement is to compute the linear regression for each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots, explain what the linear regression is modeling. For example, describe any relationships that you notice and any other findings you may have.

### VacationPy

Now, let's use your skills working with weather data to plan future vacations. Use Jupyter-gmaps and the Google Places API for this part of the assignment. Narrowed down the DataFrame to find your ideal weather condition, including:

* A max temperature lower than 80 degrees but higher than 70.
* Wind speed less than 10 mph.
* Zero cloudiness.
* Drop any rows that don't satisfy all three conditions. You want to be sure the weather is ideal.
* Use Google Places API to find the first hotel for each city located within 5,000 meters of your coordinates.

### Heatmap Result

![Heatmap](/Images/Heatmap.JPG)
