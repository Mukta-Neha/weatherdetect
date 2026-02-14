🌤️ Weather App (HTML, CSS & JavaScript)

A simple and user-friendly Weather Application built using HTML, CSS, and JavaScript.
This app fetches real-time weather data using the OpenWeatherMap API and displays temperature, weather condition, humidity, and wind speed for any city entered by the user.

🚀 Features

🔍 Search weather by city name

🌡️ Displays temperature in Celsius

☁️ Shows weather condition (Clear, Cloudy, Rain, Mist, Snow)

💧 Humidity information

🌬️ Wind speed details

❌ Error message for invalid city names

📱 Responsive and modern UI

🛠️ Technologies Used

HTML5 – Structure

CSS3 – Styling & Layout

JavaScript (ES6) – Logic & API handling

OpenWeatherMap API – Real-time weather data

📂 Project Structure
Weather-App/
│
├── index.html        # Main HTML file
├── style.css         # CSS styling file
├── script.js         # JavaScript logic
├── cloud.png         # Weather icons
├── clear.png
├── rain.png
├── mist.png
├── snow.png
└── 404.png           # Error image

⚙️ How It Works

User enters a city name

App sends a request to OpenWeatherMap API

Weather data is fetched in JSON format

Data is displayed dynamically on the UI

If city is not found → error message is shown

🔑 API Configuration

This project uses the OpenWeatherMap API.

In script.js:

const api_key = "YOUR_API_KEY_HERE";
