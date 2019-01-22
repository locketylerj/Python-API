# What's the Weather Like at the Equator?

## Python, APIs and JSON traversals
Use  Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

We know what you may be thinking: _"Duh. It gets hotter..."_

But, if pressed, how would you **prove** it?

![Equator](Images/equatorsign.png)

## WeatherPy

This Python script visualizes the weather of 500+ cities across the world of varying distance from the equator. This is accomplished using a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

The script builds series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

The script also:

* Randomly selects **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Performs a weather check on each of the cities using a series of successive API calls.
* Includes a print log of each city as it's being processed with the city number and city name.
* Saves both a CSV of all data retrieved and png images for each scatter plot.

As final considerations:

* Also included is a written description of three observable trends based on the data.

## Additional Notes

* Requires an API key to run the script. 

## Copyright

Data Boot Camp © 2018. All Rights Reserved.
