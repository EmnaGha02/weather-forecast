# Weather App

## Overview
This Weather App allows users to search for real-time weather conditions and hourly forecasts of any city using the OpenWeatherMap API. The application provides temperature, weather descriptions, and icons representing the current and predicted weather conditions.

## Features
- Search weather information by city name
- Display current temperature and weather description
- Show weather icons based on conditions
- Provide an hourly weather forecast for the next 24 hours
- Responsive design with a clean UI

## Technologies Used
- **HTML** (index.html): Structuring the app layout
- **CSS** (styles.css): Styling the UI with a modern look
- **JavaScript** (script.js): Fetching and displaying weather data using OpenWeatherMap API

## Installation & Usage
1. Clone this repository or download the files.
2. Open `index.html` in your web browser.
3. Enter a city name and click the search button to get weather details.

## Files Overview
- **index.html**: Contains the structure of the app including an input field, button, and display areas for weather data.
- **styles.css**: Styles the weather container with a gradient background, styled buttons, and formatted text.
- **script.js**: Handles API requests, processes data, and updates the UI dynamically.

## API Used
The app uses the **OpenWeatherMap API** to fetch real-time weather data.

- **Current Weather Data**:  
  `https://api.openweathermap.org/data/2.5/weather?q={city}&appid={apiKey}`
- **Hourly Forecast Data**:  
  `https://api.openweathermap.org/data/2.5/forecast?q={city}&appid={apiKey}`

> **Note:** Replace `apiKey` with your valid OpenWeatherMap API key.

## Future Improvements
- Add geolocation support to fetch weather based on user's location.
- Implement a 7-day weather forecast.
- Improve UI with animations and better visual representations.
- Convert temperatures to Fahrenheit based on user preference.

