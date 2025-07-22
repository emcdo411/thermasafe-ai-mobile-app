Absolutely! Here's your full `README.md` written out for the `thermasafe-ai-mobile-app` GitHub repository, tailored with clickable sections, shields.io badges, colorful banners, and beginner-friendly structure:

---

````markdown
# 📱 ThermaSafeAI Mobile Companion App

![React Native](https://img.shields.io/badge/React%20Native-0.73.4-blue?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-brightgreen?logo=typescript)
![Expo](https://img.shields.io/badge/Expo-49.x-orange?logo=expo)
![Styled Components](https://img.shields.io/badge/styled--components-v6-ff69b4?logo=styled-components)
![MIT License](https://img.shields.io/badge/license-DACR-lightgrey)

---

## 📚 Table of Contents

- [🚀 Overview](#-overview)
- [🧱 Folder Structure](#-folder-structure)
- [🛠️ Tech Stack](#️-tech-stack)
- [📦 Installed Packages](#-installed-packages)
- [📲 Features](#-features)
- [⚙️ Local Setup](#️-local-setup)
- [✅ Git Push & GitHub Actions](#-git-push--github-actions)
- [📸 Screenshots](#-screenshots)
- [💡 Why This Matters](#-why-this-matters)
- [🤝 Acknowledgements](#-acknowledgements)

---

## 🚀 Overview

The **ThermaSafeAI Mobile App** is the React Native-based companion to the [ThermaSafeAI](https://github.com/emcdo411/thermasafe-ai) project. This app lets users remotely monitor and control AI-powered stovetops to prevent Pyrex glassware from shattering due to thermal shock.

---

## 🧱 Folder Structure

```bash
thermasafe-ai-mobile-app/
├── assets/              # Icons, images
├── components/          # Reusable UI components
│   ├── ui/              # UI primitives (buttons, headers, etc.)
├── src/                 # App logic & screen routing
│   ├── hooks/           # Custom React hooks
│   ├── services/        # API and Bluetooth services
│   ├── screens/         # Main app screens (Home, Alerts, etc.)
│   ├── context/         # Global context/state providers
│   ├── utils/           # Utility functions
├── App.tsx              # Root App entry
├── app.json             # Expo config
├── package.json         # Project metadata
├── .gitignore           # Git exclusions
├── DACR-LICENSE         # Defensive AI Commercial Rights license
└── README.md            # Project overview (you are here)
````

---

## 🛠️ Tech Stack

* **Framework**: React Native (via Expo)
* **Language**: TypeScript
* **Styling**: Styled Components
* **State Management**: React Context + Hooks
* **Connectivity**: Bluetooth (BLE) + Wi-Fi (WebSocket-ready)
* **AI Integration**: Simulated data (ThermaSafe hook), future TensorFlow Lite
* **CI/CD**: GitHub Actions

---

## 📦 Installed Packages

```json
{
  "expo": "^49.x",
  "react": "^18.x",
  "react-native": "0.73.4",
  "styled-components": "^6.x",
  "expo-bluetooth": "^1.x",
  "react-navigation": "^6.x",
  "react-native-svg": "^13.x",
  "expo-status-bar": "~1.x",
  "react-native-safe-area-context": "^4.x"
}
```

---

## 📲 Features

* 🌡️ **Live Burner Temp Gauge**
* 🔍 **AI-Powered Cookware Detection**
* ⚠️ **Thermal Shock Alerts**
* 🧠 **Safety Assistant (optional GPT-powered)**
* 🔌 **Remote Burner Controls (low, med, high, off)**
* 📡 **Real-time Bluetooth/Wi-Fi Connection Status**

---

## ⚙️ Local Setup

```bash
git clone https://github.com/emcdo411/thermasafe-ai-mobile-app.git
cd thermasafe-ai-mobile-app
npm install
npx expo start
```

> ⚠️ Requires Expo Go app on mobile for testing (or Android Studio/iOS Simulator)

---

## ✅ Git Push & GitHub Actions

📤 Use these commands to push changes and trigger GitHub Actions:

```bash
git add .
git commit -m "Add new components and update mobile features"
git pull origin main --allow-unrelated-histories
git push -u origin main
```

> ✅ GitHub Actions will auto-run mobile build tests from `.github/workflows/mobile-ci.yml`

---

## 📸 Screenshots (Coming Soon)

* 🔥 Live Thermographic Visualization
* 📊 Safety Metrics Overlay
* 🧠 Assistant Warning Popups

---

## 💡 Why This Matters

Pyrex explosions and thermal kitchen accidents are not just rare — they’re underreported and **highly preventable**. ThermaSafeAI Mobile empowers users with **real-time heat feedback**, **material-aware AI logic**, and **remote safety controls**, all from their phone. This isn’t just smart cooking — it’s smart living.

---

## 🤝 Acknowledgements

Built with ❤️ by **Erwin Maurice McDonald**
Veteran | MSSA Cohort | Associate Solutions Architect

---

🛡️ **Licensed under [DACR – Defensive AI Commercial Rights](https://defensiveai.org/dacr-license)**
🌐 Explore more: [ThermaSafeAI Web Repo](https://github.com/emcdo411/thermasafe-ai)

```

---

Let me know if you’d like this turned into a downloadable `.md` file, or automatically added into your GitHub repo.
```

