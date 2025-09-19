# WeatherApp-Android

A simple **Android weather forecast application** that allows users to check the current weather for any city.  
Built with **Java** and **Gradle**, using a public weather API.

---

## Table of Contents

- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Setup & Installation](#setup--installation)  

---

## Features

- 🌍 Search the weather by **city name**  
- ☀️ Displays **temperature**, **conditions** (Clear, Clouds, Rain, etc.), **humidity**, and more  
- ⚠️ Error handling for invalid city names or failed requests  
- 📱 Optimized for Android devices  

---

## Tech Stack

| Component | Technology |
|-----------|------------|
| Language | Java |
| Platform | Android |
| Build tool | Gradle |
| API | OpenWeatherMap |
| IDE | Android Studio |

---

## Setup & Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/Splendorius/WeatherApp-Android.git

2. Open the project in Android Studio

3. Insert your weather API key
weather_app/MainActivity.java
```java
private final String appid = "CHANGE_ME";
```


5. If using OpenWeatherMap, place your API key in res/values/strings.xml or wherever the app expects it

6. Build and run the app on an emulator or physical device
```text
Minimum SDK: 21 (Android 5.0 Lollipop), Target SDK: 33 (Android 13)
```
