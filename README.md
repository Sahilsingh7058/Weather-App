# 🌦️ Weather App

A beautiful and beginner-friendly **Weather App** built using **HTML, CSS, and JavaScript**, that fetches real-time weather information of any city using the **OpenWeatherMap API**.

---

## 🚀 Features
- 🌍 **Real-time weather data** using the OpenWeatherMap API  
- 🔍 **Search any city** and instantly view results  
- ☁️ Displays:
  - Temperature (°C)
  - City name
  - Humidity (%)
  - Wind speed (km/h)
- 🖼️ **Dynamic weather icons** (clear, clouds, rain, drizzle, mist)  
- ⚠️ **Error handling** for invalid city names  
- 📱 **Responsive design** for all devices  
- 🎨 Smooth hover animations and a modern gradient UI  

---

## 🧰 Tech Stack

| Technology | Description |
|-------------|-------------|
| **HTML5** | App structure and content |
| **CSS3** | Styling, gradients, and responsiveness |
| **JavaScript (ES6)** | Logic, API fetching, and DOM manipulation |
| **OpenWeatherMap API** | Source of live weather data |

---

## 📂 Project Structure
weather-app/
│
├── index.html # Main HTML file
├── style.css # Styling for the app
├── app.js # JavaScript logic (API handling)
├── README.md # Project documentation
└── images/ # Weather and UI icons
├── search.png
├── rain.png
├── clouds.png
├── clear.png
├── drizzle.png
├── mist.png
├── humidity.png
└── wind.png

🧠 How It Works

You type a city name in the search bar

JavaScript fetches data from the OpenWeatherMap API

The app displays the city’s temperature, humidity, and wind speed

Depending on the weather condition, a matching icon appears (e.g., rain, clear sky)

If the city doesn’t exist, an error message is shown
🧠 How It Works

You type a city name in the search bar

JavaScript fetches data from the OpenWeatherMap API

The app displays the city’s temperature, humidity, and wind speed

Depending on the weather condition, a matching icon appears (e.g., rain, clear sky)

If the city doesn’t exist, an error message is shown

## 🔑 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/weather-app.git
cd weather-app
2. Get Your API Key
Go to OpenWeatherMap

Sign up (free)

Generate your API key

3. Add Your API Key
In app.js, replace the placeholder with your actual key:

javascript
Copy code
const apiKey = "YOUR_API_KEY_HERE";
4. Run the App
Just open index.html in your browser — and enjoy 🌤️
