# Weather App 🌤️

A modern weather application that provides real-time weather updates for any location. Users can search for weather details by city name or use their current location for instant updates. The app also features a 24-hour weather forecast and a clean, responsive design.

---

## Features 🛠️
- 🌍 **Search Weather by City**: Enter any city name to get detailed weather data.
- 📍 **Location-based Weather**: Automatically fetches weather based on the user's location.
- 🕒 **24-Hour Forecast**: Displays hourly weather updates for the next 24 hours.
- 🎨 **Responsive Design**: Optimized for desktops, tablets, and mobile devices.
- 🌐 **Dynamic Icons**: Weather-specific icons to enhance the visual experience.

---

## Tech Stack 🧰
- **Frontend**: HTML, CSS, JavaScript
- **API**: [WeatherAPI](https://www.weatherapi.com/)
- **Icons**: Custom weather icons mapped to WeatherAPI's condition codes

---

## Installation 🔧

1. Clone the repository:

   ```bash
   git clone https://github.com/HariPasapuleti/weather-app
   ```
3. Navigate to the project directory:

   ```bash
   cd weather-app
   ```
5. Open `index.html` in your browser to see the app in action. Alternatively, you can deploy it on a server of your choice.

7. **API Key Setup**:
  - Visit [WeatherAPI](https://www.weatherapi.com/) and sign up for a free account to get an API key.
  - Replace the `API_KEY` placeholder in the script with your actual API key in the `weather.js` file:
    
    ```javascript
    const API_KEY = 'YOUR_API_KEY';
    ```
5. Optionally, if you're looking to run the app locally using a server, you can use any local server setup (e.g., using Live Server extension in VS Code or using Python's built-in HTTP server).
