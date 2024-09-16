
---

# Weather App 🌦

A simple and elegant Weather App built with HTML, CSS, and JavaScript. It fetches real-time weather data using the OpenWeatherMap API and provides users with both current weather information and an hourly forecast for the next 24 hours.

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [How to Run Locally](#how-to-run-locally)
- [API Integration](#api-integration)
- [Improvements](#improvements)
- [License](#license)

## Features

- Search weather information by city name.
- Display current temperature, weather condition, and weather icon.
- Hourly forecast for the next 24 hours.
- Loading indicator to improve user experience.
- Fully responsive design.
- Elegant UI with animations and hover effects.

## Screenshots

### Home Page:
![Weather App Home](<img width="1678" alt="Home" src="https://github.com/user-attachments/assets/3095e205-cc9b-45ad-a38e-6bce411e8f2f">)

### Searching:
![Weather App Searching ](<img width="1680" alt="Searching" src="https://github.com/user-attachments/assets/aa9088c9-6913-4621-b00b-0ea5d3e6c9a2">
)

### Results+Hourly Forecast:
![Weather App Hourly Forecast](<img width="1677" alt="Hourly+search" src="https://github.com/user-attachments/assets/8729f6c1-7f76-4295-bcd5-b02cf9585212">)

## Demo

**Live Demo**: [Weather App Demo](#)

## Technologies Used

- **HTML**: Structuring the webpage and UI elements.
- **CSS**: Styling and animations for an elegant, modern UI.
- **JavaScript**: Fetching data from the OpenWeatherMap API and dynamically displaying content.
- **OpenWeatherMap API**: Fetching real-time weather data for current and forecast conditions.

## How to Run Locally

To run this project on your local machine, follow these simple steps:

### Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript.
- A text editor like VSCode or Sublime Text.
- A web browser like Chrome or Firefox.

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```
   
2. Navigate into the project directory:
   ```bash
   cd weather-app
   ```

3. Get your API key from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) and replace it in the `script.js` file where it says `const apiKey = 'YOUR_API_KEY'`.

4. Open `index.html` in a browser:
   ```bash
   open index.html
   ```

5. Search for any city to see the current weather and the hourly forecast!

## API Integration

This app integrates the OpenWeatherMap API to fetch weather data. Here’s how it works:

- **Current Weather Data**: The API provides temperature, weather condition (e.g., clear sky, rain), and a corresponding weather icon.
- **Forecast Data**: The API delivers a 5-day forecast, which is sliced to show the next 24 hours (in 3-hour intervals).

### API Endpoints Used

- **Current Weather API**:  
  `https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}`
  
- **5-Day / 3-Hour Forecast API**:  
  `https://api.openweathermap.org/data/2.5/forecast?q={city}&appid={API_KEY}`

## Improvements

Here are a few future improvements that could be made to the app:

- Add location-based weather detection using the browser's Geolocation API.
- Implement error handling for invalid city names or API request failures with custom error pages.
- Include more weather details like humidity, wind speed, and sunrise/sunset times.
- Add unit conversion between Celsius and Fahrenheit.
- Cache data for faster performance and reduced API calls.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to modify this README based on your specific project requirements!
