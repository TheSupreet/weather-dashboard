````markdown
# Weather Dashboard

This project is a weather dashboard application built with React, Material-UI, and Recharts. It fetches real-time weather data from RapiApi and displays the current weather and a 7-day forecast for various cities. The application also features a responsive design to ensure usability on different devices.

## Features

- **Fetch and display real-time weather data**: Users can search for cities and view current weather conditions.
- **7-day weather forecast**: Displays daily temperature trends and weather conditions.
- **Data visualization**: Graphical representation of temperature trends using Recharts.
- **Responsive design**: Ensures the application is mobile-friendly.
- **Error handling**: Gracefully handles errors such as invalid city names.

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- Node.js (v12 or higher)
- npm (v6 or higher)

## Project Structure

```
WEATHER-APP
│
├── node_modules
├── public
├── src
│   ├── components
│   │   ├── forecastChart
│   │   │   └── index.jsx
│   │   ├── header
│   │   │   └── index.jsx
│   │   ├── mainCards
│   │   │   ├── CurrentWeatherCard.jsx
│   │   │   ├── ForecastCard.jsx
│   │   │   └── index.jsx
│   ├── Context
│   │   └── index.jsx
│   └── images
├── .env
├── App.css
├── App.jsx
├── App.test.js
├── index.css
├── index.js
├── logo.svg
├── reportWebVitals.js
├── setupTests.js
├── .gitignore
├── package-lock.json
├── package.json
└── README.md


### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/TheSupreet/weather-dashboard
   cd weather-dashboard
   ```
````

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Get an API key from RapidApi**

   Sign up at [Rapidapi](https://rapidapi.com/hub) to get your API key.

4. **Create a `.env` file in the root directory**

   Add your RapidApi API key:

   ```plaintext
   REACT_APP_RapidApi_API_KEY=your_api_key_here
   ```

### Running the Application

1. **Start the development server**

```bash
npm start
```

The application will be available at [http://localhost:3000](http://localhost:3000).

### Building for Production

To create a production build, run:

```bash
npm run build
```

This will output the production-ready files to the `build` directory.


## Usage

1. **Search for a city**: Use the search bar to enter the name of a city.
2. **View current weather**: The current weather details for the selected city will be displayed.
3. **View 7-day forecast**: The application will also show a 7-day weather forecast with temperature trends.

## Note

- API KEY will be expiring within a month.
- Get a New API KEY, if the current API KEY expires.

```
