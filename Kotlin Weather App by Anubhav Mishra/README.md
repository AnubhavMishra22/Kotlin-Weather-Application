# Kotlin-Weather-App
<br>
<p>This project is on Creating an Android Weather App using Kotlin.
To get the weather information I used <a href="https://openweathermap.org" target="_blank">OpenWeatherMap</a> API. 
Informations like Temperature, Pressure, Humidity, Weather status, Time of Sunrise and Sunset etc. are passed from the API.</p>
<p>
<b>Creating an Android Weather App using Kotlin</b>
</a>
</p>
<br><h2>Get an API key from OpenWeatherMap</h2>
<p>For retrieving data we will use <strong>OpenWeatherAPI</strong>, and we will be needing an API key for it. Before proceeding please get an API key by registering on Open Weather API.</p>
<br><h2>Getting weather information using Latitude & Longitude</h2>
<p>Suppose you want to request weather information using a <strong>Latitude</strong> &amp; <strong>Longitude</strong> of a place, then you should use:</p>
<pre>response = URL("https://api.openweathermap.org/data/2.5/weather?lat=$LAT&amp;lon=$LON&amp;units=metric&amp;appid=$API").readText(
                    Charsets.UTF_8
                )</pre>
<p>where LAT and LON will be the Latitude &amp; Longitude respectively.In this project to display weather
information of user's current location we just need detected the current latitude &amp; longitude.
</a>
</p>

