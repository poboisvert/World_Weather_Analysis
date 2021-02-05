# PyBer Project Overview

The goal of this project was to give insights on a dataset generated with random latitute and longitude from NumPy and to provide real-time suggestions for our client's ideal hotels by using (1) within a given range of latitude and longitude and that (2) provided the right kind of weather for the client.

## Resources

- Datasets (Weather_Database folder): WeatherPy_Database.csv
- Software: Python 3.8.5, Jupyter 6.1.4

## Summary

### Weather Analysis

The Jupyter notebook "WeatherPy" provide a stastical analysis in order to confirm if there was a relation between the latitude and longitude with the Humidity, Cloudiness and Wind Speed.

The Jupyter notebook "VacationPy" give the user the ability to find hotel from a selected range hotels that he could stay for a potentiel trip.

### High level Analysis

The Jupyter notebook "Weather_Database" is a dataset of 2,000 latitude and longitude a citie that was found using the API OpenWeatherMap.

The Jupyter notebook "Weather_Database" use the previous dataset and generate a DataFrame of hotels with the local weather condition that are open and possible to book.

The Jupyter notebook "Vacation_Itinerary" is the final document to book a trip by car across a specific region.
