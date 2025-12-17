🌦️ Advanced Weather Widget (Glassmorphism UI)
A modern, responsive weather application built using pure HTML, CSS, and Vanilla JavaScript.
This project provides real-time weather data, dynamic animated backgrounds, and a glassmorphism interface, all packed into a single, deployable HTML file

✨ Features
🔍 Search weather by city, region, or postcode
📍 Automatic location detection (GPS → IP fallback)
🌡️ Displays temperature (°C / °F) and feels-like temperature
💧 Shows humidity, wind speed, and air quality (PM2.5)
🎨 Dynamic animated background that changes with weather & temperature
🧊 Glassmorphism UI with smooth gradients and blur effects
📱 Fully responsive (desktop, tablet, mobile)
♿ Accessible with ARIA roles and screen-reader support
⚡ No frameworks — pure vanilla HTML, CSS & JavaScript

🛠️ Technologies Used
HTML5 – semantic structure & accessibility
CSS3 – glassmorphism, gradients, animations & responsive design
JavaScript (ES6+) – API handling, DOM updates, async/await
WeatherAPI – real-time weather data

📸 Preview
The UI automatically adapts its background based on:
Sunny / Clear
Cloudy / Overcast
Rain / Snow / Storm
Hot / Cold temperature

🚀 How It Works
User enters a location (city, region, or postcode)
App fetches live data from WeatherAPI
Weather data is parsed and displayed instantly
Background animation updates dynamically based on:
Weather condition
Temperature range
If no city is entered:
App attempts GPS location
Falls back to IP-based location
