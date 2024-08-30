# python-api-challenge

## Overview

### This assignment explores certain global weather trends using Python in Jupyter Notebook, and APIs from OpenWeatherMap and Geoapify. There are two main analyses in this assignment:

### 1. WeatherPy: Analysis of weather data including temperature, humidity, cloudiness, and wind speed, for over 600 cities worldwide to analyze their relationships to latitude.
### 2. VacationPy: Finds the ideal vacation areas through filtering cities on weather conditions and nearness to local hotels. This analysis shows results on interactive maps using hvplot.

## Project Structure

### - WeatherPy.ipynb: A Jupyter Notebook for obtaining, processing, and analyzing data on weather.
### - VacationPy.ipynb: A Jupyter Notebook for finding vacation locations that have ideal weather conditions and close accommodations.
### - cities.csv: A dataset containing city names, countries, and coordinates obtained for API calls.
### - Output Figure Folder: Contains plots depicting different analyses:
###     - Scatter plots and linear regression model plots: visuals for how temperature, humidity, cloudiness, and wind speed vary based on latitude.
###     - Interactive maps: map_plot.png & map_plot_with_hotels.png--both show cities with weather data on a hover menu on a map, one includes nearby hotels.

## Key Takeaways

### 1. Temp vs. Lat: Depicts a clear pattern of temperatures increases closer to the equator
### 2. Humidity, Cloudiness, Wind Speed vs. Lat: Displays more differentiation and weaker to no relationship with latitude
### 3. Vacation Analysis: Gives a list of potential vacation locations based on ideal weather conditions and nearby hotels, all visualized on an interactive hvplot map.

## Requirements to Run Analysis:

## Python version 3.0 and above
## Jupyter Notebook (for best results)
## Libraries to import: pandas, numpy, matplotlib, requests, scipy, hvplot, and geoviews

## How to Use: 

### - Weather Analysis: Use "WeatherPy.ipynb" for data analysis on weather, it will produce scatter plots and regression lines to depict relationship between weather params and latitude.
### - Vacation Analysis: Use "VactionPy.ipynb" to filter cities by ideal weather conditions and find nearby hotels, it will produce results on an interactive map.

