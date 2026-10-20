# 🌤️ Weather Dashboard

A real-time weather dashboard built with HTML, CSS and asynchronous JavaScript. Search any city to see its current temperature, humidity and wind speed.

## 🔗 Live Demo
https://yasaswisrigudivaka.github.io/weather-dashboard/

## ✨ Features
- Fetches live data using the Fetch API with async/await
- Search weather by city name
- Parses nested JSON and renders it dynamically as cards
- Error handling for invalid cities and network failures
- Responsive design that works on mobile

## 🛠️ Tech Stack
- HTML5, CSS3
- JavaScript (ES6+)
- [Open-Meteo API](https://open-meteo.com/) (Geocoding and Forecast), no API key needed

## ⚙️ How It Works
1. The city name is sent to the Geocoding API to get latitude and longitude.
2. Those coordinates are sent to the Forecast API to get current weather.
3. The JSON response is parsed and displayed on the page.

## 👤 Author
Yasaswi Sri Gudivaka
Web Development Intern, Thiranex
