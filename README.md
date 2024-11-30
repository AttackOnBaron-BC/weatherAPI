# Weather Dashboard 🌦️

## Description

The Weather Dashboard is a web application that allows travelers to quickly view current and forecasted weather conditions for multiple cities. By leveraging the OpenWeather API, users can search for a city and instantly access detailed weather information, helping them plan trips more effectively.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [API Reference](#api-reference)
- [Contributing](#contributing)
- [License](#license)

## DEMO

The demo is [here](https://weatherapi-g770.onrender.com/)
![image](https://github.com/user-attachments/assets/6b48d4ca-7e62-41b3-b54f-095a2bd66d11)


## Features

- Search for current weather conditions in any city
- View a 5-day weather forecast
- Persistent search history
- Responsive design for mobile and desktop
- Real-time weather data from OpenWeather API

## User Story

```
AS A traveler
I WANT to see the weather outlook for multiple cities
SO THAT I can plan a trip accordingly
```

## Acceptance Criteria

- When a city is searched, current and future conditions are displayed
- Searched cities are added to search history
- Current weather conditions show:
  - City name
  - Date
  - Weather condition icon
  - Temperature
  - Humidity
  - Wind speed
- 5-day forecast displays:
  - Date
  - Weather condition icon
  - Temperature
  - Wind speed
  - Humidity
- Clicking a city in search history retrieves its weather information

## Installation

### Prerequisites

- Node.js (v14 or later)
- npm (v6 or later)
- OpenWeather API Key

### Steps

1. Clone the repository
```bash
git clone https://github.com/your-username/weather-dashboard.git
```

2. Navigate to the project directory
```bash
cd weather-dashboard
```

3. Install dependencies
```bash
npm install
```

4. Create a `.env` file in the root directory and add your OpenWeather API key
```
OPENWEATHER_API_KEY=your_api_key_here
```

## Usage

1. Start the development server
```bash
npm run start:dev
```

2. Open your browser and navigate to `http://localhost:3000`

3. Search for a city in the input field to view its weather conditions

## Technologies Used

- Frontend:
  - HTML5
  - CSS3
  - JavaScript (ES6+)
  - Bootstrap/Tailwind CSS

- Backend:
  - Node.js
  - Express.js

- API:
  - OpenWeather 5-Day Forecast API

## API Reference

### OpenWeather API Endpoint

```
https://api.openweathermap.org/data/2.5/forecast?lat={lat}&lon={lon}&appid={API_KEY}
```

### Parameters

- `lat`: Latitude of the city
- `lon`: Longitude of the city
- `appid`: Your OpenWeather API key

**Note**: API key may take up to 2 hours to activate after registration.


## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Your Name - your.email@example.com

Project Link: [https://github.com/your-username/weather-dashboard](https://github.com/your-username/weather-dashboard)
