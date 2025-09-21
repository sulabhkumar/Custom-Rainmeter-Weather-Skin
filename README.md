🌦️ Custom Rainmeter Weather Skin
This repository contains a custom Rainmeter skin for displaying weather information in a clean and dynamic way.

✨ Features
🌡️ Displays temperature in °C

🌤️ Shows a dynamic weather icon that updates based on current conditions

☁️ Displays weather status (e.g., Rainy, Cloudy, Sunny, etc.)

🔄 Auto-refreshes with updated weather data





📥 Installation Guide
1. Install Rainmeter Download and install Rainmeter.

2. Install a Base Skin Install any Rainmeter skin of your choice (e.g., Mond, Enigma, Inside Dream, etc.).

3. Replace Weather Skin

4. Navigate to the skin’s weather folder.

5. Replace its weather.ini file with the weather.ini file from this repository.

6. Add Resources Copy the @Resources folder from this repository into the same directory where weather.ini is located.

7. Refresh the Skin Right-click the Rainmeter tray icon → Refresh all (or refresh the specific skin).






🌍 Configure Location & API Key
To make the weather skin work for your location, follow these steps:

1. Open OpenWeatherMap in your browser.

2. Create a free account and log in.

3. Copy your API key from your account dashboard.

4. Open the weather.ini file and update the Base URL with your API key:

[https://api.openweathermap.org/data/2.5/weather?lat={latitude}&lon={longitude}&appid={api_key}&units=metric]

5. Find the latitude and longitude of your area (you can use Google Maps or any online tool).

6. Replace <latitude> and <longitude> in the URL with your location’s coordinates.

Example:
[https://api.openweathermap.org/data/2.5/weather?lat=55&lon=55&appid=aa4564dfgvb66h3421cfa7ad6c45dffsghdffg&units=metric]


🖼️ Configure Weather Icons
To ensure the correct weather icons display:

1. Open the weather.ini file.

2. Locate the [MeterIcon] block.

3. Update the ImageName property to include the full path of your Icons folder before the [MeasureIconCode]@2x.png.

Example:

[MeterIcon]

ImageName = "C:\Users\administrator\Desktop\Rainmeter\Skins\Mond\Weather\@Resources\Icons\\[MeasureIconCode]@2x.png"

📸 Preview

<img width="194" height="51" alt="image" src="https://github.com/user-attachments/assets/961e708f-f5a4-47e3-aacd-264bc67cb961" />







⚡ Notes

Make sure your internet connection is active for live weather updates.

You can customize fonts, colors, and layout by editing the .ini file.
