# Weather App

A small weather web app: type a city name and get the current temperature, humidity and wind speed, with an icon that matches the weather.

Written in plain HTML, CSS and JavaScript (no frameworks, no build step).

## Features

- Search any city by name
- Current temperature (°C), humidity (%) and wind speed
- Weather icon that changes according to the conditions (clear, clouds, rain, drizzle, mist)
- Data from the [OpenWeatherMap](https://openweathermap.org/api) "Current weather" API, fetched with `fetch` / `async-await`

## Run it

1. Get a free API key from OpenWeatherMap.
2. Put it in the `apikey` constant inside `weater.html`.
3. Open `weater.html` in a browser (or serve the folder with any static server).

## Files

| File | Purpose |
| --- | --- |
| `weater.html` | Page structure and the JavaScript that calls the API |
| `weater.css` | Styling |

## What I practised

Calling a REST API from the browser, handling JSON responses, updating the DOM from the data, and basic CSS layout.
