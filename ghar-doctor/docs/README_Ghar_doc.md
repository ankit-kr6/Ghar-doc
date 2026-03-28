# 🏥 Ghar Doctor — Smart Home Health Monitoring System

![Ghar Doctor Banner](web/assets/logo.png)

> **"Healthcare at your doorstep — monitored from anywhere, anytime."**

---

## 📌 Project Overview

**Ghar Doctor** is an IoT-powered real-time health monitoring system built for home use. It uses wearable body sensors connected to an ESP32 microcontroller to continuously track **heart rate** and **body temperature**, transmitting the data via WiFi to a live web dashboard accessible by patients and doctors.

This project was built as part of a **Hackathon** to solve the problem of remote patient monitoring in rural and semi-urban India — where frequent hospital visits are not always possible.

---

## 🎯 Problem Statement

Millions of patients in India, especially the elderly, cannot visit hospitals regularly. There is no affordable, easy-to-use system that:
- Monitors vitals continuously at home
- Alerts doctors when readings go abnormal
- Provides a live, readable dashboard remotely

**Ghar Doctor solves this.**

---

## 🚀 Features

- ❤️ **Real-time Heart Rate Monitoring** — continuous BPM tracking via pulse sensor
- 🌡️ **Body Temperature Tracking** — medical-grade precision sensor
- 📡 **WiFi Data Transmission** — ESP32 sends encrypted data over local WiFi
- ☁️ **Cloud Storage** — secure data logging for historical analysis
- 📊 **Live Web Dashboard** — responsive dashboard with live graph, stats & alerts
- 🔔 **Abnormal Alert System** — flags readings outside the normal range
- 🔐 **Login & Signup System** — secure user authentication pages
- 📱 **Fully Responsive UI** — works on mobile, tablet, and desktop

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Hardware | ESP32, MAX30100 Pulse Sensor, DS18B20 Temp Sensor |
| Firmware | Arduino C++ (ESP32 framework) |
| Frontend | HTML5, CSS3, JavaScript (Vanilla) |
| UI Design | Custom CSS with medical green/blue theme |
| Icons | Font Awesome 6 |
| Communication | WiFi (HTTP / WebSocket) |
| Data Storage | Cloud (Firebase / ThingSpeak) |

---

## 🖥️ Web Pages

| Page | Description |
|---|---|
| `index.html` | Landing page with hero section and product intro |
| `features.html` | All features listed with icons |
| `how-it-works.html` | Step-by-step data flow explanation |
| `dashboard.html` | Live health dashboard with charts and readings |
| `login.html` | Secure login page |
| `signup.html` | New user registration |
| `contact.html` | Contact form with info cards |

---

## 📸 Screenshots

### 🔬 Device
![Ghar Doctor Device](web/assets/ghar-doctor-device.png)

### 📊 Dashboard
> Live heart rate and temperature readings update every 2 seconds via sensor data.

---

## ⚙️ How It Works

```
Wearable Sensors
     ↓
ESP32 Microcontroller (processes raw data)
     ↓
WiFi Transmission (encrypted)
     ↓
Cloud Server (data stored securely)
     ↓
Live Web Dashboard (doctors & patients view data)
```

---

## 📂 Repository Structure

```
ghar-doctor/
├── README.md               ← You are here
├── web/
│   ├── index.html          ← Home / Landing page
│   ├── dashboard.html      ← Live monitoring dashboard
│   ├── features.html       ← Feature showcase
│   ├── how-it-works.html   ← System explanation
│   ├── login.html          ← User login
│   ├── signup.html         ← User registration
│   ├── contact.html        ← Contact page
│   ├── style.css           ← Global stylesheet
│   ├── script.js           ← JS for sensors & transitions
│   └── assets/
│       ├── logo.png
│       └── ghar-doctor-device.png
└── docs/
    └── project-report.pdf  ← Full project documentation
```

---

## 🧠 Team / Author

| Name | Role |
|---|---|
| Ankit Kumar Mandal | Developer & Designer |

> 📍 VIT Bhopal University | CSE (AI & ML) | Batch 2025–2029

---

## 🌐 Live Demo

> 🔗 Coming soon — will be hosted on GitHub Pages

To enable GitHub Pages:
1. Go to repo **Settings** → **Pages**
2. Select branch `main`, folder `/web`
3. Save — your site will be live at `https://YOUR_USERNAME.github.io/ghar-doctor`

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- VIT Bhopal University for the platform
- ESP32 & Arduino open-source community
- Font Awesome for icons
- All hackathon mentors and judges

---

<p align="center">Made with ❤️ for smarter healthcare in India</p>
