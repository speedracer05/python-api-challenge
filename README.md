# Introduction

This repository is an assignment from UC Davis's Data Analytics bootcamp. Part I, WeatherPy, visualizes the weather of 800+ cities, across the world of varying distances from the equator, retrieveing data using the OpenWeatherMap API. In Part II, VactionPy, builds upon data acquired from Part I to plan a future vacation, using jupyter-maps and Goolge Places API to display humidity information on a heat map, find ideal weather conditions and select a hotel for each city within 5000 meters of the selected coordinates. Lastly, hotels are plotted on top of the humidity heatmap, with a pin containing the hotel name, city and country.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

<b> Project Discription </b>: Generate all of the tables and figures needed to produce a technical report of the study. 

## General Information
The code analyzes the relationship between the city latitude and various weather attributes, e.g. temperature and humidity. Data is taken from city_data_df, using 'o' as a marker to plot the City_Lat and Temperature as x,y coordinates. What makes this assignment unique is that I employed Matpltlib's colormap to map values to a color gradient, with the lowest temperature in blue, and the highest in red. A colorbar was also added to aid in identifying color to numerical range. Regression analysis was conducted using R-squared to identify how close the data fit to the regression line that was plotted.


## Technologies
```python
# Dependencies & Setup
import matplotlib.pyplot as plt
import pandas as pd
import numpy as np
import requests, json
import gmaps
import os
from config import api_key
```


## Setup
Load and open the Jupyter Notebook file in your computer.
```
git clone https://github.com/speedracer05/Matplotlib-Challenge.git
pip install citipy: https://pypi.org/project/citipy/
get Weather maps api: https://home.openweathermap.org/
get started with Google Maps Platform: https://developers.google.com/maps/gmp-get-started
```

## Built With
* Jupyter notebook Code Version: 6.0.3
Chrome: 87.0.4280.141
Node.js: 12.18.3
OS: Windows_NT x64 10.0.19042
* conda 4.10.0
* Python 3.6.10 Anaconda, Inc.
* Kite Pro Version: 1.2021.310.0

## Author
John Chan
