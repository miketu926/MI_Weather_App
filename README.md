# A simple weather app that displays 3-day forecast

## Installation
  * Clone this repo
  * Open .html file in browser
  * NOTE: the path takes a query string of two fields
    * zip_code= {zip_code}
    * date= {MM/DD/YYYY}
    * example: index.html?zip_code=10011&date=05/15/2019

## Comments
  * API returns a type opaque response
    * fetch API functions are created however not utilized because of the opaque response
  * Objects are created under `locationApi` and `forecastApi` to mock API responses in JSON
  * Data is gathered and presented by traversing through `locationApi` and `forecastApi`
  * Weather images are gathered statically from `https://developer.accuweather.com/weather-icons` using their image links

## Features
  * API requests for location and forecast
  * Dynamically populates 3-day forecast starting from current date
    * Day of the week changes dynamically
    * Forecast updates
  * Weather icons sourced from `https://developer.accuweather.com/weather-icons`