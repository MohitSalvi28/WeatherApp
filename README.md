# 🌦️ React Weather Dashboard

A clean, responsive weather dashboard built with React and Vite that displays real-time weather information using the OpenWeatherMap API. Developed as part of a technical assignment for Qodex.ai.

---

## 🚀 Features

- 🔍 City-based weather search
- 🌡️ Displays current temperature, humidity, wind speed, and condition
- 🖼️ Dynamic weather icon based on real-time conditions
- 🔁 Auto-refreshes weather data every 30 seconds (polling)
- 💾 Saves last searched city using localStorage
- ⚠️ Handles invalid city names and API/network errors gracefully
- 📱 Responsive design with a clean layout
- ⚛️ React Context API for global state management

---

## 📸 Preview
![Screenshot 2025-05-27 233901](https://github.com/user-attachments/assets/bd325dbd-a728-416d-9efd-5981b57c939a)



---

## 🧑‍💻 Tech Stack

- React (Vite)
- JavaScript (ES6+)
- OpenWeatherMap API
- CSS (Flexbox)
- React Context API
- LocalStorage

---

## 📁 Project Structure
src/
├── App.jsx # Main application component
├── App.css # Application styles
├── main.jsx # Entry point
└── assets/ # (Optional) icons/images




## Short Description of My Approach
 
1. Project Setup: Initialized the project using Vite and React for faster build and hot-reload support.

2. Component Structure: Broke the UI into reusable components:

SearchBar for user input

WeatherDisplay to show weather info

ErrorMessage for displaying errors

3 API Integration: Used OpenWeatherMap API to fetch real-time weather data based on user input.

4 API Polling: Implemented automatic data refresh every 30 seconds using setInterval inside useEffect.

5 State Management: Used React Context API to manage global state (city and weather data).

6 Persistence: Used localStorage to store and reload the last searched city when the app is reopened.

⚠7 Error Handling: Managed errors gracefully (e.g., invalid city names, network issues) with user-friendly messages.

8 Styling: Applied CSS and Flexbox to ensure a clean, centered, and responsive UI.

9 Best Practices: Focused on clean code, modular design, and proper use of React hooks (useState, useEffect, useContext).
