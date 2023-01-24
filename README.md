# python-api-challenge

In part one of this project, I have studied the effects of lattitude change on temperature, cloudiness, wind and humidity in different cities around the world.

To get the cities data, I have used OpenWeatherMap API.

After fetching the data, I exported the data on a new csv file to use it for the second part of this project.

I have generated scatter plots and calculated linear regression and r-squared values to study the relationships between above mentioned variables.

In the second part of this project, I used the CSV file created in the first part to import the data.

I plotted all the cities on a map using hvplot.

Then I choose ideal cities for my holiday liking by filtering them according to temperature, wind speed, cloudiness and humidity.

After doing that, I used geoapifi API to find the nearest hotel from the city center.

As last step, I displayed my shortlisted cities on the map with more details (nearest hotel etc.) in hover popup.
