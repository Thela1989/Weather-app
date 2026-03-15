# Weather App

A simple and responsive weather application built with HTML, CSS, and JavaScript.

The app includes:

- a current weather view
- a 5-day forecast view
- city search using the OpenWeather API

## Features

- Search weather by city name
- Display current temperature, feels-like temperature, humidity, and wind speed
- Show weather condition icons (clear, clouds, rain, snow, thunderstorm, etc.)
- Navigate to a separate 5-day forecast page
- Mobile-friendly layout

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- OpenWeather API

## Project Structure

- `start.html`: current weather page
- `page2.html`: 5-day forecast page
- `styles.css`: shared styling for both pages
- `images/`: icons used in the current weather page
- `images.5days/`: icons for forecast cards

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm

### Installation

1. Install dependencies:

```bash
npm install
```

2. Start the local server:

```bash
npm run dev
```

3. Open your browser:

```text
http://localhost:3000/start.html
```

## API Notes

This project uses OpenWeather endpoints for:

- current weather
- forecast data

API keys are currently written directly in the HTML files. For production use, move keys to a secure backend or environment-based setup.

## Future Improvements

- Add better error handling for invalid API responses
- Add unit conversion (Celsius/Fahrenheit)
- Add day/night themes based on local time
- Refactor JavaScript into separate files for maintainability
