Name :- Mishra Ritik Sarojkumar 
Company Name :- CODETECH IT SOLUTIONS PVT LTD 
Intern ID :- CT04DG3359
Domain :- Java Programming 
Duration :- 30 June 2025 to 30 July 2025

# 🌤️ Java Weather App

A simple command-line Java application that fetches and displays real-time weather data for any city using the OpenWeatherMap API.

---

## 🔧 Features

- Fetches real-time weather data (temperature, humidity, and condition).
- Accepts city name input from the user.
- Displays weather in a clean, readable format.
- Uses the `org.json` library to parse API responses.

---

## 🚀 Getting Started

### 📁 Prerequisites

- Java JDK 8 or higher installed.
- Internet connection.
- OpenWeatherMap API key (free).

---

### 📥 Installation & Setup

#### 1. Clone or Download the Project
Place the files in a working directory, 


> 💡 Download JSON library from:  
> [https://repo1.maven.org/maven2/org/json/json/20230227/json-20230227.jar](https://repo1.maven.org/maven2/org/json/json/20230227/json-20230227.jar)

#### 2. Get Your Free API Key
- Sign up at [https://openweathermap.org/api](https://openweathermap.org/api)
- Replace the `API_KEY` value in `WeatherApp.java` with your key:

```java
static final String API_KEY = "your_actual_api_key_here";

#### Example Output :

Enter city name: Mumbai
Weather Report for Mumbai:
Temperature: 31.2°C
Humidity: 68%
Condition: scattered clouds


