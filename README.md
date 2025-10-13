Project Title: Live Weather Dashboard


The aim of the Live Weather Dashboard is to provide users with real-time weather updates for any city or location. It helps users view current temperature, humidity, wind speed, and weather conditions through an interactive and user-friendly interface.

Features

  Real-Time Weather Data: Displays live temperature, humidity, wind speed, and weather description.

  Location Search: Allows users to search weather details of any city or region.

  Dynamic Interface: Automatically updates data when a new location is searched.

  Weather Icons: Shows visual icons representing the current weather condition (sunny, cloudy, rainy, etc.).

  Responsive Design: Works smoothly on desktop and mobile screens.

  Error Handling: Shows messages for invalid city names or network issues.

Technologies Used

Frontend: HTML, CSS, JavaScript

API: OpenWeatherMap API (for fetching live weather data)

Tools: VS Code (for development), GitHub Pages / Vercel (for deployment)

How It Works

The user enters a city name in the search bar.

The dashboard sends a request to the OpenWeatherMap API using JavaScript fetch() method.

The API returns live weather data in JSON format.

The JavaScript script extracts key details like temperature, humidity, and wind speed.

The dashboard updates the webpage dynamically to display the latest weather information with icons and styles.

If the city is not found, an error message is displayed to the user.
