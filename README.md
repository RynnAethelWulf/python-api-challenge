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

<p align="center">  A report that breaks down the weather data retrived from api and finding relationships between weather,humidity,wind-speed and displaying the hotels on google maps for cities satisfying the perfect weather conditions.
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


## ✍️ Observable Trends <a name = "trends"></a>
<b>Part-1</b>
From the data of 249 mice identified these were the trends observeved -
- Ramicane regimen performes as good as Capomulin regimen.
- Ketapril and Naftisol regimen increased the  tumor volume significantly.
- Capomulin regimen has been more effective for female mice.

What can be clearly seen in the  mices for Capomulin regimen between tumor volume and weight has positive slope - indicating as weight increase in mouse , the tumor volume increase linearly. There is higher correlation between tumor volume and timepoint for Capomulin regimen.

<b>Part-2</b></br>
![alt text](https://github.com/bimalkprabha/python-api-challenge/blob/main/output_data/heatmap.png?raw=true)</br>
![alt text](https://github.com/bimalkprabha/python-api-challenge/blob/main/output_data/hotel_locations_at_perfect_weather.png?raw=true)</br>


## 🎉 Acknowledgements <a name = "acknowledgement"></a>
- UWA Data Science</br>
- Citypy python library by wingchen</br>
