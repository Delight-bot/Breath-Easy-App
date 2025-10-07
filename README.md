# Breathe Easy : AI Respiratory Health Monitoring App

A comprehensive respiratory health application that helps users monitor air quality, log symptoms, and predict potential health impacts using AI-powered analytics.

![React](https://img.shields.io/badge/React-19.1.1-61DAFB?logo=react\&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7.1.2-646CFF?logo=vite\&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4.10-06B6D4?logo=tailwindcss\&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-12.3.0-FFCA28?logo=firebase\&logoColor=black)
![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-4.22.0-FF6F00?logo=tensorflow\&logoColor=white)

---

## Overview

Breathe Easy combines environmental monitoring and health tracking to help users understand and manage respiratory well-being through machine learning analytics.

---

## ⚙️ Features

### Air Quality Monitoring

* Real-time AQI tracking
* Location-based air data and alerts
* Historical air quality trends

### Symptom Logging

* Track symptoms with timestamps and severity levels
* Detect recurring patterns over time

### AI-Powered Predictions

* TensorFlow.js-based models for forecasting and risk assessment
* Personalized symptom trigger predictions

### Exposure Impact Analysis

* Correlate air quality data with symptom patterns
* Generate insights for long-term exposure tracking

### Device Integration

* Connect air quality monitors and respiratory health devices
* Real-time synchronization across multiple devices

### Care Team Connection

* Share health data securely with professionals
* Generate reports and schedule appointments

### Medical Resources

* Access verified medical content and treatment guides

### User Profile Management

* Customize health profiles and preferences
* Manage privacy settings

---

## Getting Started

### Prerequisites

* Node.js v18+
* npm or yarn
* Firebase account

### Installation

```bash
git clone https://github.com/yourusername/breathe-easy-app.git
cd breathe-easy-app
npm install
```

### Environment Variables

Create a `.env` file:

```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

### Run Locally

```bash
npm run dev
```

Then open: [http://localhost:5173](http://localhost:5173)

### Build for Production

```bash
npm run build
npm run preview
```

---

## Tech Stack

**Frontend:** React, Vite, TailwindCSS, React Router
**Backend:** Firebase
**ML Framework:** TensorFlow.js
**Tools:** ESLint, PostCSS, Autoprefixer

---

## Project Structure

```
breathe-easy-app/
├── src/
│   ├── components/
│   ├── pages/
│   ├── App.jsx
│   └── main.jsx
├── public/
├── index.html
└── package.json
```

---

## Key Components

### Onboarding

* Step-based questionnaire for personalized setup

### Dashboard

* Displays AQI, symptom trends, and AI predictions

### Condition Predictor

* Uses ML to analyze user and environmental data for proactive insights

---

## Security & Privacy

* Firebase Authentication
* HIPAA-aligned data handling
* End-to-end encryption
* User-controlled sharing permissions

---

## Acknowledgments

* [EPA AirNow API](https://www.airnow.gov/air-quality-and-health/) for air quality data
* Verified health sources for medical insights
* Community testers and contributors

---

## 🗺️ Roadmap

* [ ] Mobile app (iOS & Android)
* [ ] Wearable integration
* [ ] Multilingual support
* [ ] Telemedicine features
* [ ] Advanced ML models
* [ ] PDF report export

---

**Made with care for better respiratory health**

