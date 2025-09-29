# 🌦 Modern Weather Dashboard

A modern, responsive *Weather Dashboard* built with *HTML, Tailwind CSS, JavaScript, and Chart.js*.  
It detects the user’s location using the *IP Geolocation API* and fetches real-time weather and forecast data from the *OpenWeatherMap API*.

---

## 🚀 Features

- 🌍 *Automatic Location Detection* (via IP Geolocation API)
- ☀ *Current Weather Information* (temperature, humidity, wind, sunrise & sunset)
- 📊 *24-Hour Temperature Forecast* (interactive chart using Chart.js)
- 📅 *Detailed Forecast Cards* with weather icons and conditions
- 🎨 *Responsive UI* designed with Tailwind CSS
- ⚡ Fast and easy to run in any modern browser

---

## 🛠 Technologies Used

- *HTML5* – Structure of the app
- *Tailwind CSS* – Modern responsive styling
- *JavaScript (ES6)* – Core logic for fetching and displaying weather
- *Chart.js* – 24-hour temperature forecast chart
- *Font Awesome* – Weather-related icons
- *OpenWeatherMap API* – Weather and forecast data
- *IPGeolocation API* – Auto-detect user’s location

---

## 🔑 API Keys

You need two free API keys to run this project:

1. *OpenWeatherMap API* → [Get Key Here](https://home.openweathermap.org/users/sign_up)  
   Used for fetching weather and forecast data.  
   Example:
   ```js
   const WEATHER_API_KEY = "your_openweathermap_api_key";
IP Geolocation API → Get Key Here
Used for detecting user’s location automatically.
Example:

js
Copy code
const GEO_API_KEY = "your_ipgeolocation_api_key";
Replace these keys in index.html before running:

js
Copy code
const WEATHER_API_KEY = "your_openweathermap_api_key";
const GEO_API_KEY     = "your_ipgeolocation_api_key";
▶ How to Run
Clone this repository:

bash
Copy code
git clone https://github.com/yourusername/weather-dashboard.git
cd weather-dashboard
Open the project in VS Code.

Replace your API keys in index.html.

Run the project:

Option 1: Use the Live Server Extension in VS Code and click Go Live.

Option 2: Open index.html directly in your browser.

📸 Screenshots
http://127.0.0.1:5500/index.html

🌤 Current Weather
Shows temperature, weather condition, humidity, wind, sunrise, and sunset.

📊 Forecast Chart
Interactive 24-hour forecast chart built with Chart.js.

📅 Detailed Forecast
Hourly forecast cards with temperature, icons, and weather description.
