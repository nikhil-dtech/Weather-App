# 🌤️ Weather Forecast Web App

A sleek and responsive weather forecast web application that provides real-time weather updates based on your current location or a searched city. Built using vanilla JavaScript and powered by the OpenWeatherMap API.

## 🔗 Live Demo

> https://weatherapp9910.netlify.app/

---

## 🌟 Features

- 📍 Auto-detects your current location using Geolocation API
- 🌆 Search weather by city name
- 📅 Displays current temperature, humidity, wind speed, and weather condition
- 🌈 Dynamic weather icons and background based on weather
- 🕓 Shows date and time for the location
- 📱 Fully responsive UI

---

## 🌐 Tech Stack

| Layer       | Technology             |
|------------|-------------------------|
| Frontend   | HTML, CSS, JavaScript   |
| API        | OpenWeatherMap API      |
| Geolocation | Browser Geolocation API |

---

## 🧠 How It Works

1. Uses `navigator.geolocation` to get user's current location.
2. Fetches city name using reverse geocoding from OpenWeatherMap API.
3. Fetches real-time weather data using OpenWeatherMap's Weather API.
4. Displays weather data dynamically using DOM manipulation.

---

## ⚙️ Setup Instructions

###  Clone the Repository

```bash
git clone https://github.com/nikhil-dtech/Weather-App.git
cd Weather-App
```

## Open in Browser
You can directly open index.html in your browser.

⚠️ Geolocation will only work in secure contexts (https:// or localhost).
