# ArcWeather

![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/DanDevProjects/arcweather/total)

ArcWeather is a professional-grade, lightweight meteorological web application built with modern web standards and Material 3 design principles. It provides real-time weather tracking, extended 14-day forecasts, air quality composition analysis, and an interactive storm radar map without requiring heavy backend infrastructure.

---

## Key Features

* **Real-Time Meteorological Tracking**: Live updates for temperature, apparent temperature, humidity, dew point, cloud cover, wind speed, wind gusts, and visibility.
* **Extended Forecasts**: 12-hour short-range progression charts and comprehensive 14-day outlook views with visual temperature range indicators.
* **Interactive Radar Map**: Integrated Leaflet mapping supporting Esri base layers and live RainViewer storm/precipitation radar overlays.
* **Environmental Metrics**: Advanced atmospheric readings including European AQI, PM2.5, PM10, ozone levels, barometric pressure, UV index, and pollen allergen indexes.
* **Multi-Language Support**: Fully localized interface supporting English, Traditional Chinese, and Spanish.
* **Dynamic Theming**: Seamless switching between Light, Dark, and System appearance themes with precise contrast adjustments.
* **Saved Places**: Local storage persistence for managing favorite locations and quick switching.
* **Background Auto-Refresh**: Automatically checks and updates meteorological data at 1-minute intervals.

---

## Tech Stack

* **Markup & Style**: HTML5, Tailwind CSS (Custom configured with Material 3 color palettes).
* **Scripting**: Vanilla JavaScript (ES6+), asynchronous API handling.
* **Mapping**: Leaflet.js, Esri World Canvas, RainViewer API.
* **Weather & Air Quality Data**: Open-Meteo Open-Source Weather APIs.

---

## Getting Started

Because ArcWeather is built as a client-side single-page application, no complex build steps, package managers, or backend servers are required to run it locally.

### Prerequisites

* Any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).
* An active internet connection (required for fetching live API data and map tiles).

### Running Locally

1. Clone or download the repository to your local machine:
   ```bash
   git clone https://github.com/DanDevProjects/arcweather.git
   
2. Navigate to the project directory:
   ```bash
   cd arcweather

3. Open the index.html file directly in your browser by clicking the index.html file.

## APIs and Data Sources
Arcweather uses free and Open-source API providers.

- Weather Forecasts: Open-Meteo
- Air Quality index: Open-Meteo Air Quality API
- Precipitation Radar: RainViewer
- Geocoding and Reverse Geocoding: Open-Meteo Geocoding & BigDataCloud
- Map: Esri World Canvas (Light/Dark)

## Installing
You can Download from GitHub or [Install / Update with Obtainium](https://apps.obtainium.imranr.dev/?url=https://github.com/DanDevProjects/arcweather)

## Contributing
Contributions, Bug reports and features requests are welcome. Feel free to Contribute in the project or submit a pull request if you like to improve the codebase.

## License
This project is Open-Source and available under the MIT License.
