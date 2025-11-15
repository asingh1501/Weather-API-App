# Weather-API-App
# 🌤️ Weather App — Real-Time Weather Lookup

This project is a simple and responsive Weather Application that allows users to search for any city and instantly retrieve its real-time weather data. The app uses the **OpenWeatherMap API** to display the current temperature, humidity, description, and a weather emoji based on conditions.

This project demonstrates API integration, DOM manipulation, async JavaScript, and clean UI styling using HTML/CSS/JS.

---

## 📌 Features

- 🌍 **Search any city worldwide**
- 🌡️ **Real-time temperature** (converted from Kelvin → Fahrenheit)
- 💧 **Humidity display**
- 📝 **Weather description**
- 🌈 **Weather emoji** based on conditions (sun, clouds, rain, snow, etc.)
- ⚠️ **Error handling** for invalid city names or network issues
- 🎨 **Styled UI card** that updates dynamically

---

## 🧰 Tech Stack

- **HTML** – structure
- **CSS** – layout & styling
- **JavaScript** – logic & API handling
- **OpenWeatherMap API**

---

## 🚀 How It Works

### 1. User Input  
The user enters a city name into the input field and clicks **Get Weather**.

### 2. API Request  
The app fetches weather data from:https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}


### 3. Data Extraction  
The script extracts:
- City name  
- Temperature  
- Humidity  
- Weather description  
- Weather condition ID  

### 4. UI Display  
A styled card appears showing:
- City  
- Temperature (°F)  
- Humidity  
- Weather description  
- Matching emoji  

### 5. Error Handling  
If the city is invalid, the app shows a clean error message in the card.

---

## 📁 File Structure

Weather-App/
│
├── index.html # Main UI
├── weather.css # Styling
└── weather.js # JavaScript logic + API calls

---

## 📊 Example Output

When a user searches “New York”, they may see:

- City: **New York**
- Temperature: **75°F**
- Humidity: **60%**
- Conditions: **clear sky**
- Emoji: ☀️

---

## 📂 Future Improvements

- Add a **5-day forecast**
- Add **temperature unit toggle** (°F / °C)
- Add **background changes** based on weather
- Add **geolocation support** (weather for current location)
- Improve animations & UI transitions

---

## ▶️ How to Run

1. Download or clone the repository:
   ```bash
   git clone https://github.com/asingh1501/Weather-API-App.git

   const apiKey = "YOUR_API_KEY_HERE";





