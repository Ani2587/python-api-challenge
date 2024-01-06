# python-api-challenge

## Overview
The assignment involves analyzing weather patterns in cities relative to their proximity to the equator. WeatherPy utilizes the OpenWeatherMap API and Python scripting to collect and visualize weather data through scatter plots and linear regression. VacationPy then uses this data to plan vacations, creating map visualizations based on humidity levels to narrow down ideal destinations with specific weather conditions.

## Purpose
The assignment aims to showcase Python coding skills in accessing and visualizing weather data, uncovering patterns between latitude and weather variables. Additionally, it demonstrates practical applications by using the gathered data in VacationPy to plan vacations, helping users find optimal destinations based on desired weather conditions. The integrated approach provides both insights into weather patterns and real-world utility for travel planning.

![image](https://github.com/Ani2587/python-api-challenge/assets/17106097/330e3ab4-0b9b-4fb5-a88f-96dcf7d10292)


![image](https://github.com/Ani2587/python-api-challenge/assets/17106097/958100a0-b06c-479c-a3db-4724f99f9c4b)

![image](https://github.com/Ani2587/python-api-challenge/assets/17106097/1a8ec600-3c73-45df-9282-709590b7d5a8)

![image](https://github.com/Ani2587/python-api-challenge/assets/17106097/a62cb1e7-485e-488f-95bb-2c8bf7722088)

![image](https://github.com/Ani2587/python-api-challenge/assets/17106097/6112983b-69aa-4dff-8db9-b24c0fc27cbb)

![image](https://github.com/Ani2587/python-api-challenge/assets/17106097/ce4ee66f-741a-4978-9762-64a9e24594e5)



## Instructions

For this challenge, we have two code files committed to this repo:
•	WeatherPy.ipynb
•	VacationPy.ipynb
And api_keys.py file(not commited to the code) is updated in gitignore file. 
after running the code succefully, output folder should have following files:
  - cities.csv
  - Fig1.png
  - Fig2.png
  - Fig3.png
  - Fig4.png

1.	For weather challenge, we are analyzing the weather data for a list of cities and for each city, fetching following weather details:
  •	Latitude
  •	Longitude
  •	Max Temp
  •	Humidity
  •	Cloudiness
  •	Wind Speed
  •	Country
  •	Date
2.	Exporting  the City Data into a cities.csv file in output folder.
3.	Plotting scatter plots and linear regression charts between weather variables(temperature,humidity ,cloudiness,speed plot) and latitude to analyze the relationship between them. Detail analysis is mentioned in the code. 
4.	Generated scatter plots and linear regression plots are saved as .png image in output folder. 

-For VacationPy,
.  getting the data from cities.csv file created in Part 1 ,converting that into a Pandas DataFrame and analyzing it.
•	 Generating a map showcasing individual points representing each city within the city_data_df DataFrame. 
. For each city, using the Geoapify API to find the first hotel located within 10,000 meters of the city coordinates.


