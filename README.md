# 🛸 ISS Live Tracker - AstroHack 2025

A real-time International Space Station (ISS) tracking dashboard that integrates multiple space-related APIs to provide comprehensive space monitoring capabilities.

## 🌟 Features

- **Real-time ISS Tracking**: Live position updates every 5 seconds with latitude, longitude, altitude, and velocity
- **Interactive Map**: Visual tracking with ISS path history and auto-centering
- **Astronaut Information**: Current crew aboard the ISS with live updates
- **NASA Image of the Day**: Daily space imagery from NASA's APOD API
- **Space Weather Monitoring**: Solar wind speed and geomagnetic activity alerts
- **ISS Pass Predictions**: Find when the ISS will be visible from your location
- **Beautiful UI/UX**: Dark theme with smooth animations and responsive design

## 🚀 APIs Used

1. **Where The ISS At API** - Real-time ISS position data
   - Endpoint: `https://api.wheretheiss.at/v1/satellites/25544`
   - Updates: Every 5 seconds

2. **Open Notify API** - Astronaut information and ISS pass times
   - Astronauts: `http://api.open-notify.org/astros.json`
   - Pass Times: `http://api.open-notify.org/iss-pass.json`

3. **NASA APOD API** - Astronomy Picture of the Day
   - Endpoint: `https://api.nasa.gov/planetary/apod`
   - Using DEMO_KEY for hackathon

4. **OpenStreetMap** - Map tiles and geocoding
   - Leaflet.js integration for interactive mapping

5. **Space Weather (Simulated)** - Real NOAA API requires authentication
   - Demonstrates integration capabilities

## 💻 Technology Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Map Library**: Leaflet.js
- **Styling**: Custom CSS with CSS Variables
- **No Build Process Required**: Works directly in browser

## 🎯 Installation & Usage

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/astrohack-iss-tracker.git
cd astrohack-iss-tracker
