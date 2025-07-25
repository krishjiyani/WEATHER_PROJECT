# ☁️ Weather Info API – Golang Project

A simple and lightweight HTTP server built in Go that fetches real-time weather data using the OpenWeatherMap API. This project demonstrates basic API integration, JSON decoding, and dynamic routing using Go's standard libraries.

---

## 🌦️ Project Overview

This project allows users to get the current weather details for a given city via a simple HTTP GET request. It integrates with the OpenWeatherMap API and returns structured weather data in JSON format.

---

## 🔧 Tech Stack

- **Language**: Go (Golang)
- **Standard Libraries**: `net/http`, `encoding/json`, `os`, `fmt`
- **API Integration**: OpenWeatherMap REST API
- **Config Management**: Custom `.json` config file for API key

---

## 🔁 Features

- `GET /hello` – Test route to verify server is running
- `GET /weather/{city}` – Returns weather data for the specified city
- API key securely loaded from `.apiconfig` JSON file
- Dynamic routing and response formatting using Go's core packages
- JSON response structure with city, temperature, weather condition, etc.

