# python-api-challenge

## WeatherPy
The script first uses citipy to determine the cities based on latitude and longitude, and utilises the OpenWeatherMap API key to retrieve weather data from the cities list generated from the citipy library.

### Code Operation
Operating the code involves running the file 'WeatherPy.ipynb'.


### Dependencies
This program requires the matplotlib, pandas, numpy, citipy as well as scipy.stats libraries.

### Analysis
The code will generate plots to showcase the relationship between weather variables and latitude, and compute the linear regression for each relationship.
        

## VacationPy
The script first loads cities.csv (WeatherPy/output_data/cities.csv) into a Pandas DataFrame, and utilises both the OpenWeatherMap and Geoapify API Keys

### Code Operation
Operating the code involves running the file 'VacationPy.ipynb', and inputting weather parameters to narrow down the cities based on ideal weather conditions.

### Dependencies
This program requires the matplotlib, hvplot as well as geoviews libraries.

### Analysis
The code will generate a map displaying a point for every city in the `city_data_df` DataFrame, with the size of each point representing the humidity in each of these cities. The code also generates a second map displaying a smaller subset of cities narrowed down by ideal weather conditions, and displays the first hotel located within 10,000 metres of each coordinate, the humidity as well as country when hovered over.
           
