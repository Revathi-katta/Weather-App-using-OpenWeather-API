# Weather App 🌤️

A simple and interactive weather application built with **React (Vite)** that fetches real-time weather data using the **OpenWeather API**.  
This project demonstrates API integration, error handling, and modern React development practices.

---

## [App Link](https://weather-app-using-open-weather-paamw7cn8.vercel.app/)


## 🚀 Features
- 🌍 Search weather by city name
- 📍 Displays temperature, humidity, and weather conditions
- ⚡ Built with Vite for fast development and hot reloads
- ❌ Handles invalid city names with proper error messages

---

## 🛠️ Tech Stack
- **Frontend:** React, Vite, CSS
- **API:** OpenWeather API
- **Build Tool:** Vite
- **Deployment:** Vercel/Netlify

---

## 📸 Screenshots
<div align="center">
  <img src="screenshots\Screenshot 2025-08-20 032800.png" alt="Contributor"/>
</div>    
<div align="center">
  <img src="screenshots\Screenshot 2025-08-20 032847.png" alt="Contributor"/>
</div>    

---

## 📂 Project Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Revathi-katta/Weather-App-using-OpenWeather-API.git
cd weather-app
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Create `.env` file in root
```bash
VITE_WEATHER_API_KEY=your_openweather_api_key
```

### 4️⃣ Start the development server
```bash
npm run dev
```

---

## 📦 Build for production
```bash
npm run build
```

---

## 🧩 Folder Structure
```
weather-app/
│── public/
│── screenshots/
│── src/
│   │── components/
│   │   └── WeatherCard.jsx
│   │── App.jsx
│   │── main.jsx
│── .env
│── package.json
│── vite.config.js
│── README.md
```

##  Developed By

**Revathi Katta**  
B.Tech @ IIT Gandhinagar
[GitHub](https://github.com/Revathi-katta)
[Skillected Certificate](<div align="center">
  <img src="Certificate.png" alt="Contributor"/>
</div>)


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
