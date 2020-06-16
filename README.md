# Weather-App-using-Java-in-Android

<img  src='https://blog.frsarker.com/wp-content/uploads/2020/06/Weather-App-Design.jpg' >

<br>
<p>This project is on Creating an Android Weather App using Java.
To get the weather information I used <a href="https://openweathermap.org" target="_blank">OpenWeatherMap</a> API. 
Informations like Temperature, Pressure, Humidity, Weather status, Time of Sunrise and Sunset etc. are passed from the API.</p>
<p>Visit the blog post on <a href="https://blog.frsarker.com/java/create-a-weather-app-using-java-in-android.html" target="_blank">
<b>Create a Weather App using Java in Android</b>
</a>
</p>


<br><h2>Get an API key from OpenWeatherMap</h2>
<p>For retrieving data we will use <strong>OpenWeatherAPI</strong>, and we will be needing an API key for it. Before proceeding please get an API key by registering. You can either follow the attached video above or steps below.</p>
<ol>
<li>Create a New Account from <a title="Create new account" href="https://home.openweathermap.org/users/sign_up" target="_blank" rel="noopener">here</a>.</li>
<li>After login go to <a title="Get the API key" href="https://home.openweathermap.org/api_keys" target="_blank" rel="noopener">here</a> to get the API Key.</li>
</ol>

<br><h2>Getting weather information using Latitude & Longitude</h2>
<p>Suppose you want to request weather information using a <strong>Latitude</strong> &amp; <strong>Longitude</strong> of a place, then you should use:</p>
<pre>String response = HttpRequest.excuteGet("https://api.openweathermap.org/data/2.5/weather?lat=" + LAT + "&lon=" + LON + "&units=metric&appid=" + API);</pre>
<p>where LAT and LON will be the Latitude &amp; Longitude respectively. If you want to implement this project to display weather
information of user's current location you'll just need detect the current latitude &amp; longitude. I've already posted an article on 
<a href="https://blog.frsarker.com/java/detect-current-latitude-and-longitude-using-java-in-android.html" target="_blank">
Detect Current Latitude & Longitude using Java in Android
</a>
</p>

