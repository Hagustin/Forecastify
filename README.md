# Forecastify

Forecastify is a dynamic weather dashboard application that allows users to search for current weather conditions and view a 5-day forecast for multiple cities. Built with TypeScript, Vite, and Express, this project leverages the OpenWeather API to provide real-time weather data. It also features a search history function for convenient access to previously searched cities.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Current Weather Data**: Displays current temperature, wind speed, and humidity for any searched city.
- **5-Day Forecast**: Provides a detailed weather forecast for the upcoming days.
- **Search History**: Keeps track of previously searched cities for quick access.
- **Responsive Design**: Fully responsive layout to enhance user experience on all devices.

## Technologies Used

- **Frontend**: 
  - TypeScript
  - Vite
  - HTML/CSS
  - Day.js (for date handling)

- **Backend**: 
  - Node.js
  - Express
  - JSON file storage for search history

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Hagustin/Forecastify.git
cd forecastify
```
2. Navigate to the client directory and install dependencies:
```bash
cd client
npm install
```
3. Navigate to the server directory and install dependencies:

```bash 
cd server
npm install
```

4. Create a .env file in the server directory and add your OpenWeather API key:
``` bash
OPENWEATHER_API_KEY=your_api_key_here
```

5. Start the server:
``` bash
cd server
npm run start
```

6. In a new terminal window, start the client:
```bash
cd client
npm run dev
```

7. Open your browser and navigate to http://localhost:3000 to access Forecastify.

## Usage
Enter a city name in the search bar and click "Search" to retrieve the current weather and forecast.
View past searches in the search history for quick access.

## Contributing
Contributions are welcome! If you have suggestions for improvements or want to report issues, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.