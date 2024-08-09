# weatherapi-challenge
Overview

I’ve completed a project that dives into analyzing global weather data and planning vacations based on ideal weather conditions. This project is split into two parts: WeatherPy and VacationPy.

Project Structure

WeatherPy.ipynb: This notebook explores the relationship between weather parameters and latitude for over 500 cities using the OpenWeatherMap API.
VacationPy.ipynb: Here, I’ve planned vacations by narrowing down cities with ideal weather conditions and finding nearby hotels using the Geoapify API.
api_keys.py: Contains API keys (securely excluded from the repository using .gitignore).
.gitignore: Configured to keep sensitive information like api_keys.py out of GitHub.
How I Did It

I cloned the repository and set up a local environment.
I added my API keys to the api_keys.py file (not included in the repo).
I ran the analyses in the following order:
WeatherPy.ipynb: I analyzed and visualized how weather changes with latitude.
VacationPy.ipynb: I filtered cities to find ideal vacation spots based on specific weather criteria, then mapped them along with nearby hotels.
What’s Inside

WeatherPy:
I generated random geographic coordinates and matched them to the nearest city.
Pulled weather data using the OpenWeatherMap API.
Created scatter plots to examine how latitude affects temperature, humidity, cloudiness, and wind speed.
Performed linear regression to analyze trends separately for the Northern and Southern Hemispheres.
VacationPy:
I narrowed down cities to those with perfect vacation weather.
Used the Geoapify API to find hotels within 10,000 meters of the selected cities.
Mapped these cities, highlighting weather conditions and hotel options.
Tools and Libraries

Python
Jupyter Notebook
Pandas
Matplotlib
Holoviews/GeoViews
OpenWeatherMap API
Geoapify API
Important Notes

I made sure to include api_keys.py in the .gitignore file to keep my API keys secure. All relevant data, analysis, and visualizations are in the notebooks.

## I USED CHATGPT & XPERT LEARNING TO HELP ME WRITE THE CODE
