# Simple Weather App Using ReactJS and OpenWeatherMap API

![weather_app](https://github.com/user-attachments/assets/53f54568-a437-42f1-b17f-7527cdda19b8)

## Description

The **Weather App** is a modern, responsive web application that allows users to search for the current weather conditions of any city across the globe. The app fetches real-time data from the OpenWeatherMap API and displays key weather metrics like temperature, humidity, and wind speed, along with appropriate weather icons. The UI is designed to be clean and intuitive, utilizing a "Cool and Calm" color scheme for a soothing user experience.

## Features

### 1. **City Search**
   - Users can search for any city by typing the city name in the search bar and clicking the search icon.
   - If the city is not found or the input is empty, an alert will notify the user.

### 2. **Real-Time Weather Data**
   - The app displays the current temperature, location, and weather icon based on the selected city.
   - Data includes:
     - **Temperature** in Celsius.
     - **Humidity** percentage.
     - **Wind Speed** in kilometers per hour.

### 3. **Weather Icons**
   - The app dynamically changes the weather icon according to the current weather conditions, using data from OpenWeatherMap.
   - Weather icons include clear skies, cloudy, rainy, snowy, and more.

### 4. **Responsive Design**
   - The layout is responsive and adjusts seamlessly to different screen sizes, providing a consistent experience across devices.

### 5. **Cool and Calm UI**
   - The app uses a color scheme of Cool Blue and Mint Green, with a clean white accent, creating a modern and visually appealing interface.
   - The background features a smooth linear gradient, enhancing the overall aesthetic.

## Technologies Used

- **React.js**: A JavaScript library for building the user interface.
- **OpenWeatherMap API**: Provides real-time weather data.
- **CSS3**: For styling, including the custom color scheme and responsive layout.
- **JavaScript (ES6)**: For logic and dynamic functionality.

## Installation

To run the Weather App locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/deepshika-babu/Simple-Weather-App-Using-React-and-OpenWeatherMap-API.git

2. **Navigate to the project directory:**
   ```bash
   cd weather-app

3. **Install dependencies:**
   ```bash
   npm install

4. **Create a .env file in the root directory and add your OpenWeatherMap API key:**
   ```bash
   VITE_APP_ID=your_openweathermap_api_key

5. **Start the development server:**
   ```bash
   npm run dev

6. ***Open your browser and visit:**
   ```bash
   http://localhost:3000

## How It Works

1. **Search Functionality:** Users can enter a city name in the search bar. On clicking the search icon, the app fetches weather data using the OpenWeatherMap API and displays it on the screen.
2. **Weather Data Display:** If the data is successfully fetched, it shows the current temperature, city name, humidity, and wind speed along with a relevant weather icon.
3. **Default City:** On initial load, the app displays weather data for a default city (e.g., Chennai).
4. **Error Handling:** If the city is not found or there is an issue with the API call, the user is alerted accordingly.

## Future Improvements

1. **5-day Weather Forecast:** Display a 5-day weather forecast with daily high and low temperatures.
2. **Geolocation Support:** Automatically fetch and display weather data based on the user's current location.
3. **Unit Conversion:** Allow users to switch between Celsius and Fahrenheit.

## Acknowledgments

- Special thanks to [OpenWeatherMap](https://openweathermap.org/) for their excellent API.
- The project is inspired by the need for a simple, easy-to-use weather app with a clean interface.

## AUTHOR:
**ROKHIT ROY**
