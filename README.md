# Weather Website

## Overview
This Weather Website is a simple web application that provides real-time weather updates using the OpenWeatherMap API. Users can search for weather details of any location, view current temperature, humidity, wind speed, pressure, and other weather conditions. The website also displays hourly and daily forecasts, along with sunrise and sunset times.

## Features
- **Real-Time Weather Data**: Fetches and displays weather conditions for any searched location.
- **Hourly Forecast**: Provides weather updates for the next few hours.
- **Daily Forecast**: Shows temperature trends for the upcoming days.
- **Sunrise & Sunset Times**: Displays sunrise, sunset, solar noon, and twilight times.
- **Live Clock & Date**: Shows the current time and date dynamically.

## Technologies Used
- **HTML**: Structure of the webpage
- **CSS**: Styling and layout design
- **JavaScript**: Fetching API data and dynamic updates
- **OpenWeatherMap API**: Retrieves real-time weather data

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/weather-website.git
   ```
2. Open `index.html` in a web browser.
3. Ensure you have an API key from OpenWeatherMap and replace the existing key in `script.js`:
   ```js
   const apiKey = "YOUR_API_KEY";
   ```
4. Start using the website by entering a location in the search bar.

## API Usage
- **Current Weather Data**:
  ```sh
  https://api.openweathermap.org/data/2.5/weather?q={location}&appid={API_KEY}&units=metric
  ```
- **Hourly & Daily Forecast**:
  ```sh
  https://api.openweathermap.org/data/2.5/forecast?q={location}&appid={API_KEY}&units=metric
  ```
- **Sunrise & Sunset Times**:
  ```sh
  https://api.sunrise-sunset.org/json?lat={latitude}&lng={longitude}
  ```
## Deployment Link
https://teal-dasik-94e5e0.netlify.app/
![image](https://github.com/user-attachments/assets/4d76b257-c499-4ba1-992d-38937256d6d4)
![image](https://github.com/user-attachments/assets/df260209-4076-4c70-ac75-abe3ee640580)
![image](https://github.com/user-attachments/assets/50719359-0a7f-4ab8-b24d-658cef1086bf)


