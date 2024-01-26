# Assignment 2 - API 
## Zhumabai Adilet

Weather Information:
I use the OpenWeatherAPI to show real-time weather data, including temperature, description, icon,
coordinates, feels-like temperature, humidity, pressure, wind speed, country code, and rain volume
for the last 3 hours.

Geolocation and Mapping:
I use maps to visually showcase the location of cities based on latitude and longitude.


## Installation

To install the project, follow these steps:

1. Install from Moodle:
    ```bash
   Open Moodle to install zip file.
    ```
    ```bash
    git clone https://github.com/AdiletZumabai/Assign-2-Adilet
    ```
    


2. Navigate to the project directory:
    ```bash
    cd Ass 2 Web
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

## Usage

To use the project, follow these instructions:

1. Configure the settings in `config.js`.
2. Run the project:
    ```bash
    node server/server.js
    ```

## API Usage

The project provides the following APIs:

- `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${apiKey}`: Weather API.
- `https://api.openweathermap.org/data/2.5/forecast?q=${city}&appid=${apiKey}`: Forecast API.
- `https://api.openweathermap.org/geo/1.0/direct?q=${city}&limit=1&appid=${geocodingApiKey}`: Geocode API.
- `https://api.opencagedata.com/geocode/v1/json?q=${lat}+${lon}&key=${opencageApiKey}`: Location API.





## Credits

- Adilet: [@AdiletZumabai](https://github.com/AdiletZumabai)


## Support

For support, please [open an issue](https://github.com/yourusername/yourproject/issues) on GitHub.

