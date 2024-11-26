# Weather-Forecasting-System

The “Weather Forecasting System” is an expert system aimed at providing real-time weather information for cities globally. By utilizing data fetched from the OpenWeather API, this system provides accurate weather forecasts including temperature, humidity, wind speed, weather conditions (such as clear skies, rain etc.) and pressure. Additionally, the system generates recommendations based on the weather conditions. This system combines real-time weather data with AI-powered decision-making by offering personalized guidance to the user based on the weather conditions.

### Source of Data

The weather data used in this project is sourced from the OpenWeather API. OpenWeather provides free API services to fetch weather information worldwide. It includes various types of weather data such as current weather, historical weather, forecasts and even air pollution levels. For this project, I have used the Current Weather Data API endpoint to fetch real-time weather data for selected cities which includes the following weather parameters:
•	Temperature (in Celsius)
•	Humidity (percentage)
•	Weather description (such as clear sky, rain, etc.)
•	Wind speed
•	Pressure
The weather data is returned in JSON format and the system extracts and displays key data points for the user.
