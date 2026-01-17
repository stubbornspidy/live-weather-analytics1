# Live Weather Analytics Web Application

A responsive web application that provides real-time weather insights, short-term forecasts, and safety-based recommendations using public weather APIs.

This project focuses on **logic-driven insights** rather than just displaying raw weather data.

---

## Features

- City-based weather search with input validation
- Automatic location detection using browser geolocation
- Current weather conditions with live date and time
- 5-day weather forecast with daily summaries
- Hourly weather overview for the current day
- “Best time to go out” recommendation based on weather conditions
- Overall weather confidence score indicating safety level
- Rule-based alerts for risky conditions (rain, heat, cold, wind, low visibility)
- Context-aware weather suggestions (safe / caution / avoid)
- Air Quality Index (AQI) display with major pollutant values
- Client-side rate limiting to control excessive API requests
- Fully responsive UI for desktop and mobile devices

---

## Tech Stack

HTML5, CSS3, JavaScript (ES6), Bootstrap 5, OpenWeatherMap API

---

## How It Works (High-Level Flow)

1. On page load, the app attempts to fetch the user’s location using browser geolocation.
2. Weather data is fetched using latitude/longitude or city name input.
3. Current conditions, forecasts, AQI, and sunrise/sunset data are processed.
4. Rule-based logic determines alerts, best time recommendations, and confidence score.
5. The UI updates dynamically without page reloads.

---

## Why This Project

Rather than building a basic weather display, this project emphasizes:
- Decision-making logic
- User safety indicators
- Efficient API usage
- Clear separation between data processing and UI updates

---

## Future Enhancements

- Server-side rate limiting
- Persistent user preferences
- Weather trend comparisons
- Notification support
- Backend integration for analytics

---

## Note

This project uses public APIs and client-side logic for learning and demonstration purposes.
