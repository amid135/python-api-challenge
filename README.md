# python-api-challenge
This repository contains two projects, WeatherPy and VacationPy, that explore the use of Python, APIs, and data analysis techniques to answer questions about weather and plan vacations based on weather conditions.

WeatherPy
In WeatherPy, we use Python to visualize the weather of over 500 cities across the world. We leverage the citipy library to randomly select cities based on latitude and longitude coordinates. Using the OpenWeatherMap API, we retrieve current weather data for each city, including temperature, humidity, cloudiness, and wind speed.

Requirements
- Create Plots to Showcase the Relationship Between Weather Variables and Latitude:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

Compute Linear Regression for Each Relationship:
- Separate the plots into Northern Hemisphere and Southern Hemisphere.
- Create scatter plots with linear regression lines, displaying the regression equation and correlation coefficient (r^2).

Files
- WeatherPy.ipynb: Jupyter notebook containing the Python script for WeatherPy.
- api_keys.py: File where your API key for OpenWeatherMap API is stored. Ensure this file is included in .gitignore to protect your API key.
- .gitignore: File to ensure sensitive information like api_keys.py is not uploaded to GitHub.
- README.md: This file, providing an overview of the project, instructions, and requirements.

VacationPy
- In VacationPy, we continue using our weather data skills to plan future vacations. We use the geoViews Python library and the Geoapify API to create map visualizations.

Tasks
Create a Map Showing Cities:
- Display a map with points for each city, where the size of the point corresponds to humidity.
- Narrow Down Cities Based on Weather Conditions:

Filter cities based on desired weather conditions (e.g., max temperature, wind speed, cloudiness).
Find Nearby Hotels:
- Use the Geoapify API to find the nearest hotel to each city's coordinates (within 10,000 meters).
Create a Map Showing Hotels:
- Display a map with hotels added to the city points, providing hotel names and countries in hover messages.

Files
- VacationPy.ipynb: Jupyter notebook containing the Python script for VacationPy.
- README.md: This file, providing an overview of the project, instructions, and requirements.
- Getting Started
- Clone the Repository:

Setup:
- Obtain an API key from OpenWeatherMap API and Geoapify API.
- Create api_keys.py in the root directory and store your API keys:

Run WeatherPy:
- Open and execute WeatherPy.ipynb in Jupyter Notebook.
- Follow the instructions within the notebook to generate weather visualizations.

Run VacationPy:
- Open and execute VacationPy.ipynb in Jupyter Notebook.
- Follow the instructions within the notebook to plan vacation spots based on weather conditions.

Notes
- Ensure api_keys.py is included in .gitignore to protect your API keys.
- Regularly commit your changes to track your progress.

Refer to the respective Jupyter notebooks for detailed coding instructions and data visualization outputs.
This project provides an opportunity to deepen your understanding of Python, APIs, data analysis, and visualization techniques. Enjoy exploring and analyzing weather data to draw meaningful insights and plan your ideal vacation destinations!
