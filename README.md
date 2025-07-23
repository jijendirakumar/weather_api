🌦️ Weather App
A simple weather application that allows users to check real-time weather information for any city using the WeatherAPI.com.

📸 Demo
<img width="1279" height="832" alt="image" src="https://github.com/user-attachments/assets/7f96b087-230a-43d6-bb14-5c51c4d0740e" />


🚀 Features
Get current weather data by city name

Display temperature, weather condition, humidity, wind speed

Weather icon display

Responsive and clean UI

🛠️ Tech Stack
HTML – for structure

CSS – for styling

JavaScript – for dynamic functionality

WeatherAPI.com – for weather data

🔑 API Key Setup
Go to 👉 https://www.weatherapi.com

Sign up and log in

Generate a free API key

Replace the placeholder key in your script.js file:

js
Copy
Edit
const apiKey = "YOUR_API_KEY";
📁 Project Structure
graphql
Copy
Edit
weather-app/
│
├── index.html        # Main UI
├── style.css         # Styling file
└── script.js         # JavaScript logic with API call
🔍 Example API Call
url
Copy
Edit
https://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=London
Returns a JSON object with current weather details.

📦 How to Run
Clone/download the repo

Open index.html in any modern browser

Type any city (e.g., London) and click “Get Weather”

💡 Future Enhancements
Add 7-day forecast

Dark mode support

Geolocation-based weather

Search history with localStorage

📜 License
This project is open-source and free to use.
