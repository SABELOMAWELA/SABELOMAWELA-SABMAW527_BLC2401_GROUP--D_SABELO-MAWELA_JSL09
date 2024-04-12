# SABELOMAWELA-SABMAW527_BLC2401_GROUP--D_SABELO-MAWELA_JSL09
Live Webpage with Random Background, Crypto Price, Weather & Time
This is a webpage that fetches various data from APIs and displays it dynamically:

Background Image: A random landscape nature image is fetched from Unsplash and set as the background.
Crypto Price: Fetches Litecoin data (name, image, current price, high/low) from CoinGecko and displays it.
Weather: Uses geolocation to get your location and then fetches weather data (temperature, icon) from OpenWeatherMap.
Time: Updates the current time every second.
Live Demo: You can't include a link to the live demo here, but users can view it on GitHub Pages by hosting the project: let users know they can view the live demo on GitHub Pages

## Getting Started:

Clone or download this repository.
You'll need an API key for OpenWeatherMap (https://openweathermap.org/api). Create an account and note down your key.
Create an HTML file and copy-paste the code provided.
Replace the placeholder value for APPID in the OpenWeatherMap API call with your actual API key.
Save the HTML file (e.g., index.html).
Open the HTML file in your web browser to see it work!
Explanation of the Code:

The code uses a combination of JavaScript functions and the Fetch API to retrieve data from various APIs. Here's a breakdown of the key parts:

Unsplash API: Fetches a random background image.
CoinGecko API: Fetches data for Litecoin cryptocurrency.
OpenWeatherMap API: Uses geolocation to get your location and then fetches weather data.
Fetch API: Used to make asynchronous HTTP requests to the APIs.
setInterval: Updates the time on the webpage every second.
Further Customization:

You can explore the respective APIs for additional data options to display.
Feel free to modify the HTML structure and CSS styling to customize the layout and appearance.
Note: This is a basic example. Consider error handling and user interface improvements for a more robust application.
