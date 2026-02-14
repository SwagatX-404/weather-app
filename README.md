# React Native Weather App 🌤️

A modern, beautiful **Weather Application** built with **React Native**, **Expo**, **Clerk** for authentication, **NativeWind** (Tailwind CSS for React Native), and a **free weather API** (e.g., OpenWeatherMap, WeatherAPI.com, etc.).

This project follows a full tutorial approach — perfect for learning modern React Native development in 2025+.

[![Expo](https://img.shields.io/badge/Expo-000000?style=for-the-badge&logo=expo&logoColor=white)](https://expo.dev)
[![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactnative.dev)
[![NativeWind](https://img.shields.io/badge/NativeWind-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://www.nativewind.dev)
[![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white)](https://clerk.com)

## ✨ Features

- 🔐 **User Authentication** with Clerk (Sign in, Sign up, Google/Apple login support)
- 🌍 **Current Weather** + **Hourly & Daily Forecast**
- 📍 **Location-based weather** (using device location via Expo Location)
- 🎨 **Beautiful UI** styled with NativeWind (Tailwind CSS)
- 🌙 **Dark / Light mode** support
- 🔄 **Real-time refresh** & error handling
- 📱 **Cross-platform** — iOS, Android (and web preview via Expo)
- ⚡ **Fast development** with Expo & hot reloading

## 🛠️ Tech Stack

| Technology       | Purpose                              | Link                                      |
|------------------|--------------------------------------|-------------------------------------------|
| React Native     | Mobile framework                     | https://reactnative.dev                   |
| Expo             | Development toolchain & SDK          | https://expo.dev                          |
| Clerk            | Authentication & user management     | https://clerk.com                         |
| NativeWind       | Tailwind CSS for React Native        | https://www.nativewind.dev                |
| Expo Location    | Access device location               | https://docs.expo.dev/versions/latest/sdk/location/ |
| Axios / Fetch    | API requests                         | —                                         |
| Free Weather API | Weather data (e.g. OpenWeatherMap)   | https://openweathermap.org/api            |

## 📸 Screenshots

(Add 3–5 screenshots here later — you can upload them to the repo and link like this:)

![Home Screen Light](screenshots/home-light.png)  
![Forecast Screen Dark](screenshots/forecast-dark.png)  
![Login with Clerk](screenshots/clerk-login.png)

## 🚀 Quick Start

### Prerequisites

- Node.js ≥ 18
- Yarn or npm
- Expo CLI: `npm install -g expo-cli`
- Expo Go app on your phone (for quick testing)
- Accounts: Clerk.dev + Weather API key

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/weather-app-rn.git
cd weather-app-rn
