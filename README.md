# Weather Forecast App

The Weather Forecast App is a user-friendly application that provides real-time weather updates and a 5-day forecast for any city worldwide.

Users can easily search for weather information by entering the name of a city.

The app displays detailed weather conditions, including **temperature, humidity, wind speed, and a brief description of the weather**.

Additionally, the app features a theme toggle button, allowing users to switch between light and dark modes for a personalized experience.

![image](https://github.com/user-attachments/assets/ce100ae9-ab03-48b6-9f33-5a34e8591b03)

## Features

- **Search Weather**: Get current weather and 5-day forecast by city.
- **Weather Details**: Display temperature, humidity, wind speed, and weather conditions.
- **Theme Toggle**: Switch between light and dark themes.

## Technologies Used

- **HTML**
- **CSS**
- **JavaScript**
- **Axios** for API requests
- **SheCodes Weather API**

## Getting Started

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/CynthiaWahome/js-weather-forecast-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd js-weather-forecast-app
    ```

3. Open [index.html](http://_vscodecontentref_/0) in your web browser:

    ```bash
    open index.html
    ```

## Usage

1. Enter the name of a city in the search bar and click the "Search" button.
2. The current weather and 5-day forecast for the entered city will be displayed.
3. Click the "Toggle Theme" button to switch between light and dark modes.

## Project Structure
.
├── index.html
├── src
│   ├── style.css
│   └── index.js
└── README.md

## API

This project uses the SheCodes Weather API to fetch weather data. You will need an API key to use this service.

### Example API Call

Get the current weather for a city:

```
https://api.shecodes.io/weather/v1/current?query={query}&key={key}
```

### Example API Response for Kinshasa

```json
{
  "city": "Kinshasa",
  "country": "Democratic Republic of the Congo",
  "coordinates": {
    "longitude": 15.3222,
    "latitude": -4.325
  },
  "condition": {
    "description": "clear sky",
    "icon_url": "http://shecodes-assets.s3.amazonaws.com/api/weather/icons/clear-sky-day.png",
    "icon": "clear-sky-day"
  },
  "temperature": {
    "current": 30.12,
    "humidity": 60,
    "feels_like": 32.00,
    "pressure": 1012
  },
  "wind": {
    "speed": 3.5,
    "degree": 90
  },
  "time": 1734436974
}
```

## Acknowledgements

- [SheCodes](https://www.shecodes.io/) for providing the weather API
- [Axios](https://axios-http.com/) for making HTTP requests easy
- [Roboto](https://fonts.google.com/specimen/Roboto) font from Google Fonts
