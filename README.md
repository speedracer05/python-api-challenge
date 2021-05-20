# Introduction

This repository is an assignment from UC Davis's Data Analytics bootcamp, which consists of a two-part excercise. Part I, WeatherPy, visualizes the weather of 500+ cities, across the world of varying distances from the equator, retrieveing data from the OpenWehaterMap API. In Part II, VactionPy, builds upon data acquired from Part I to plan a future vacation. I will use jupyter-maps and Goolge Places API to display humidity information on a heat map, find ideal weather conditions and select a hotel for each city within 5000 meters of the selected coordinates. Lastly, hotels are plotted on top of the humidity heatmap, with a pin containing the hotel name, city and country.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

<b> Project Discription </b>: Generate all of the tables and figures needed to produce a technical report of the study. 

## General Information
 


## Technologies
```python
# Dependencies & Setup
import requests
import matplotlib.pyplot
import pandas as pd
import numpy as np
import time

from citipy import citipy
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
