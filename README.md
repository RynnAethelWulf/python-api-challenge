<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Project logo"></a>
</p>

<h3 align="center">Analysis of Weather Around the World & Finding Hotels at Perfect Weather Conditions</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/bimalkprabha/python-api-challenge//issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/bimalkprabha/python-api-challenge//pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center">  A report that breaks down the weather data retrived from api and finding relationships between weather,humidity,wind-speed and displaying the hotels on google maps for cities satisfying the perfect weather conditions using Regression Analysis.
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Observable Trends](#trends)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>
Creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, we'll be utilizing a  Python library, and the OpenWeatherMap API to create a representative model of weather across world cities.
Series of scatter plots are created to showcase the following relationships:
</br>

-Temperature (F) vs. Latitude</br>
-Humidity (%) vs. Latitude</br>
-Cloudiness (%) vs. Latitude</br>
-Wind Speed (mph) vs. Latitude</br>


Second part includes ,Running linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude)

## 🏁 Getting Started <a name = "getting_started"></a>

-Randomly selected at least 500 unique (non-repeat) cities based on latitude and longitude.
-Performed a weather check on each of the cities using a series of successive API calls.
-Included a print log of each city as it's being processed with the city number and city name.
-Saved a CSV of all retrieved data and a PNG image for each scatter plot.


## ✍️ Observable Trends <a name = "trends"></a></br>
<b>Part-1</b>
From the data of 574 city locations these were the trends observeved -
- Temperature increases toward higher latitudes,as earth is tiltled at an angle approx 23.5 degrees where higher latitude are closer to sun and lower latitudes are away from the sun based on the year.
![alt text](https://github.com/bimalkprabha/python-api-challenge/blob/main/output_data/fig6.png?raw=true)
![alt text](https://github.com/bimalkprabha/python-api-challenge/blob/main/output_data/fig5.png?raw=true)
 
- Areas near the Equator and towards northern latitiude  have much higher humidty than towards south poles. Again due to the tilt of the earth towards sun. 
![alt text](https://github.com/bimalkprabha/python-api-challenge/blob/main/output_data/fig7.png?raw=true)
 
- A strong linear temeprature drop from eqautor towards north pole.

<b>Part-2</b></br>
Heat map that displays the humidity for every city of the data on Oct/2020</br>

![alt text](https://github.com/bimalkprabha/python-api-challenge/blob/main/output_data/heatmap.png?raw=true)

</br>
 For perfect weather conditons here are the criteria considered
- A max temperature lower than 80 Fahernheit  but higher than 70 Fahernheit.</br>
- Wind speed less than 10 mph.</br>
- Zero cloudiness.</br>
- And finaly humidity between 30 and 60 cent.</br>
                                                       
                                                       
Hotels within the perfect weather conditons on Oct/2020</br>
</br>
![alt text](https://github.com/bimalkprabha/python-api-challenge/blob/main/output_data/hotel_locations_at_perfect_weather.png?raw=true)</br>

## 🎉 Acknowledgements <a name = "acknowledgement"></a>
- UWA Data Science</br>
- Citypy python library by wingchen</br>
