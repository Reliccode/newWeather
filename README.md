# newWeather

newWeather is a simple and user-friendly desktop application developed in Python using the PyQt5 framework. It provides real-time weather information for any city, allows users to manage their favorite cities, and offers customization options for various weather parameters.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [System Tray](#system-tray)
- [Authors](#authors)
- [Notes](#notes)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Current Weather Display:** View real-time weather information for a specified city, including temperature, humidity, pressure, wind speed, and more.
- **Favorites:** Save your favorite cities for quick access to their weather information.
- **Settings:** Customize the app by selecting preferred weather parameters and units (metric or imperial).
- **System Tray Integration:** Minimize the app to the system tray for easy access.

## Requirements

- Python 3.x
- PyQt5
- qt-material
- OpenWeatherMap API key

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Reliccode/newWeather.git
    cd newWeather
    ```

2. Install dependencies:

    ```bash
    pip install PyQt5 qt-material
    ```

3. Obtain an API key from [OpenWeatherMap](https://openweathermap.org/) and replace the placeholder in `config.py` with your key.

4. Run the application:

    ```bash
    python main.py
    ```

## Usage

1. Enter the desired city in the search bar.
2. Click the "Search" button to display the current weather information.
3. Add the city to your favorites by clicking the "Add to Favorites" button.
4. Customize app settings by clicking the "Settings" button.
5. Access your favorite cities and switch between them using the "Favorites" button.

## Keyboard Shortcuts

- **Enter:** Search for weather data.
- **Shift + F2:** Open settings or go back from settings.
- **Ctrl + Shift + F1:** Open favorites or go back from favorites.
- **Ctrl + S:** Add the current city to favorites.

## System Tray

- The app can be minimized to the system tray.
- To exit the application, right-click the system tray icon and select "Exit."

## Authors

- [Glen Maritim](https://github.com/ExitMirth)
- [Naniwet M.](https://github.com/Reliccode)

## Notes

- The app uses SQLite to store favorite cities and settings.
- Make sure to respect the OpenWeatherMap API usage guidelines.

## Contributing

Contributions are welcome! Please follow the [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).