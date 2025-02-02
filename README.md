Aviation Weather Forecast Web App 🌤️✈️

A weather forecasting web application designed for the aviation industry, optimized for iPad. The app fetches real-time weather data using the OpenWeatherMap API and provides 15-hour & 5-day forecasts based on current location, city names, or ICAO airport codes.


✨ Features:

Live Weather Updates: Displays temperature, wind speed, humidity, pressure, and cloud coverage.

15-Hour & 5-Day Forecasts: Helps aviation professionals plan operations.

Flight Safety Alerts: Identifies hazardous weather conditions & predicts the next safe flight time.

Geolocation & ICAO Support: Retrieve weather data via GPS or airport codes.

iPad-Optimized UI: Lightweight and efficient performance with Preact (React.js).



🚀 Technologies Used:

Frontend: Preact (React.js), JavaScript, CSS

APIs: OpenWeatherMap API, Fetch API, Geolocation API

State Management: React Component Lifecycle

Error Handling: Validates incorrect city names & ICAO codes


# Set-Up Guide
- [Installation](#installation)
- [Development Workflow](#development-workflow)

**0. Before doing any of this, if you're using your own laptop/desktop, make sure you've got the latest versions of node and npm installed :**

```sh
node -v
npm -v
```

## Installation

**1. Clone this repository :**

```sh
git clone --depth 1 https://github.com/kazeohada/weatherapp.git weather-app
cd weather-app
```

**2. Make it your own :**

```sh
rm -rf .git && git init && npm init
```

> :information_source: Command above re-initializes the repo and sets up your NPM project.

**2a. Make it your own (Windows):**

If you are using Windowsyou can run the three necessary comand using Powershell. You mught need elevated privileges.

```sh
rm -r -fo .git
git init 
npm init
```

**3. Install the dependencies :**

```sh
npm install
```

## Development Workflow


**4. Start a live-reload development server :**

```sh
npm run dev
```

> This is a full web server for your project. Any time you make changes within the `src` directory, it will rebuild and even refresh your browser.


**5. Generate a production build in `./build` :**

```sh
npm run build
```

**6. Start local production server with [serve](https://github.com/zeit/serve):**

```sh
npm start
```
