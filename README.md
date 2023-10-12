# python-api-challenge

For this challenge, we have two code files committed to this repo:
•	WeatherPy.ipynb
•	VacationPy.ipynb
And api_keys.py file(not commited to the code) is updated in gitignore file. 
after running the code succefully, output folder should have folooing filrs:
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
.  •	For each city, using the Geoapify API to find the first hotel located within 10,000 meters of the city coordinates.

![image](https://github.com/Ani2587/python-api-challenge/assets/17106097/6023fcbe-15d2-454d-bfbd-653104f76e1c)

![image](https://github.com/Ani2587/python-api-challenge/assets/17106097/41a22713-0519-4835-9aed-372192133f60)
