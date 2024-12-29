# WeatherHUB

A modern weather dashboard that retrieves weather data from multiple reliable weather APIs, calculates averages for enhanced accuracy, and displays precise weather information. This project blends an appealing graphical interface with a robust backend to improve weather forecasting reliability.

## Features

- **Multiple Weather APIs:** Supports OpenWeatherMap, WeatherAPI.com, and MetaWeather.
- **Average Calculation:** Aggregates and averages temperature and humidity from multiple APIs for enhanced accuracy.
- **Modern User Interface:** Designed to resemble popular weather apps like Apple Weather or Samsung Weather.
- **Responsive Design:** Optimized for various devices and screen sizes.
- **Animation Support:** Smooth transitions and animations for an improved user experience.

## Technologies Used

- **Backend:**
  - Node.js
  - Express.js
  - Axios
  - dotenv
  - CORS
- **Frontend:**
  - HTML5
  - CSS3 (including Flexbox and animations)
  - JavaScript (ES6)

## Installation Guide

### Prerequisites

- Installed **Node.js** and **npm**.
- API keys from [OpenWeatherMap](https://openweathermap.org/api) and [WeatherAPI.com](https://www.weatherapi.com/).

### Steps to Install

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/trayx1/weatherhub.git
    cd weather-dashboard
    ```

2. **Setup the Backend:**

    Navigate to the `backend` folder:

    ```bash
    cd backend
    ```

    Install dependencies:

    ```bash
    npm install
    ```

    Create a `.env` file and add your API keys:

    ```env
    PORT=5000
    OPENWEATHER_API_KEY=your_openweathermap_api_key
    WEATHERAPI_API_KEY=your_weatherapi_com_api_key
    ```

    Start the backend server:

    ```bash
    npm start
    ```

    The server will run at `http://localhost:5000`.

3. **Setup the Frontend:**

    Open a new terminal and navigate to the `frontend` folder:

    ```bash
    cd ../frontend
    ```

    Start a simple HTTP server. You can use `http-server`. Install it globally if you don’t have it:

    ```bash
    npm install -g http-server
    ```

    Start the server:

    ```bash
    http-server -c-1
    ```

    **Alternatively:** Open the `index.html` file directly in your browser.

    **Note:** Ensure the backend server is running as the frontend fetches data from `http://localhost:5000`.

## Usage

1. **Start the Backend Server:**

    ```bash
    cd backend
    npm start
    ```

2. **Launch the Frontend:**

    Open the `frontend/index.html` file in your browser or start a local HTTP server.

3. **Fetch Weather Data:**

    - Enter the name of a city in the search field.
    - Click "Search" or press the Enter key.
    - The application will display the average temperature, humidity, and a weather description.

## Contributing

Contributions are welcome! Follow these steps:

1. **Fork** the repository.
2. **Create** a new branch (`git checkout -b feature/NewFeature`).
3. **Commit** your changes (`git commit -m 'Add new feature'`).
4. **Push** the branch (`git push origin feature/NewFeature`).
5. **Submit** a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
