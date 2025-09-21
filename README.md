🌦️ Custom Rainmeter Weather Skin
This repository contains a custom Rainmeter skin for displaying weather information in a clean and dynamic way.

✨ Features
🌡️ Displays temperature in °C

🌤️ Shows a dynamic weather icon that updates based on current conditions

☁️ Displays weather status (e.g., Rainy, Cloudy, Sunny, etc.)

🔄 Auto-refreshes with updated weather data





📥 Installation Guide
Install Rainmeter Download and install Rainmeter.

Install a Base Skin Install any Rainmeter skin of your choice (e.g., Mond, Enigma, Inside Dream, etc.).

Replace Weather Skin

Navigate to the skin’s weather folder.

Replace its weather.ini file with the weather.ini file from this repository.

Add Resources Copy the @Resources folder from this repository into the same directory where weather.ini is located.

Refresh the Skin Right-click the Rainmeter tray icon → Refresh all (or refresh the specific skin).






🌍 Configure Location & API Key
To make the weather skin work for your location, follow these steps:

Open OpenWeatherMap in your browser.

Create a free account and log in.

Copy your API key from your account dashboard.

Open the weather.ini file and update the Base URL with your API key:

https://api.openweathermap.org/data/2.5/weather?lat=<latitude>&lon=<longitude>&appid=<api key>&units=metric
Find the latitude and longitude of your area (you can use Google Maps or any online tool).

Replace <latitude> and <longitude> in the URL with your location’s coordinates.

Example:
https://api.openweathermap.org/data/2.5/weather?lat=28.7041&lon=77.1025

📸 Preview

<img width="194" height="51" alt="image" src="https://github.com/user-attachments/assets/961e708f-f5a4-47e3-aacd-264bc67cb961" />







⚡ Notes

Make sure your internet connection is active for live weather updates.

You can customize fonts, colors, and layout by editing the .ini file.
