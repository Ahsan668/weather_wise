# Weather Wise

Weather Wise is a mobile application built with Flutter that provides real-time weather forecasts. It utilizes the OpenWeather API to fetch and display weather data for various locations.

## Features

- **Real-time Weather Updates**: Get the current weather for your location or any city you search for.
- **7-day Weather Forecast**: See the weather forecast for the upcoming week.
- **Detailed Weather Information**: Includes temperature, humidity, wind speed, and more.
- **User-friendly Interface**: Easy to navigate and visually appealing design.
- **Search Functionality**: Find weather information for any city worldwide.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Ahsan668/weather-wise.git
   cd weather-wise
Install dependencies:

bash
Copy code
flutter pub get
Run the app:

bash
Copy code
flutter run
Configuration

Obtain an API key from the OpenWeather API.

Add the API key to your Flutter app:

Open the lib/constants.dart file (or wherever you store your constants) and add your API key:

dart
Copy code
const String apiKey = 'YOUR_API_KEY';
Usage

Home Screen: Displays the current weather for your location.
Forecast Screen: Shows the weather forecast for the next 7 days.
Search: Use the search bar to find the weather for any city.
Dependencies

http: For making HTTP requests to the OpenWeather API.
provider: State management.

Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements

OpenWeather API for providing the weather data.
Flutter for the awesome framework.
