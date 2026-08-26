# Wildlife Conflict and Movement Predictor Using AI

A web-based platform designed to help monitor wildlife movement, report human-wildlife conflict incidents, visualize risk areas, and support authorities with AI-based wildlife movement predictions.

## 📌 Project Overview

Human-wildlife conflict is a major challenge in areas located near forests and wildlife habitats. This project provides a centralized dashboard where wildlife incidents and movement patterns can be monitored and analyzed.

The system combines an interactive map, incident reporting, analytics, wildlife movement data, and an AI-based prediction module to help identify potential risk areas and support faster decision-making.

## 🚀 Key Features

* **Live Wildlife Movement Map**

  * Interactive map for visualizing wildlife movement and activity.
  * Helps users understand areas with increased wildlife presence.

* **Incident Reporting**

  * Allows incidents involving wildlife to be recorded.
  * Stores important information for further analysis.

* **AI Risk Prediction**

  * Uses historical wildlife movement and incident data to predict potential future risk areas.
  * Helps identify areas that may require additional attention.

* **Analytics Dashboard**

  * Displays wildlife and incident-related statistics.
  * Provides an overview of movement and conflict patterns.

* **Report Management**

  * Centralized handling of reported wildlife incidents.
  * Supports monitoring and analysis of collected data.

* **Data Management**

  * Wildlife movement and incident datasets can be managed through the system.
  * Includes sample and structured data for testing the platform.

## 🖥️ Technology Stack

### Frontend

* React.js
* Vite
* JavaScript
* HTML
* CSS

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

### AI / Prediction

* Python
* Machine Learning
* Historical wildlife movement and incident data

### Other Tools

* Git
* GitHub
* REST APIs
* Interactive map libraries

## 📂 Project Structure

```text
human-wildlife-conflict-dashboard/
│
├── hwc-backend/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── ...
│
├── public/
│
├── src/
│
├── Internship_Documents/
│   ├── Internship_Certificate.pdf
│   ├── Internship_Report.pdf
│   └── Project_Presentation.pptx
│
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
├── README.md
└── vite.config.js
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/abhishek25scs1003001223-art/2025-2029_AbhishekKumarMishra_25SCS1003001223_3rdSemester_2CSE31.git
```

### 2. Open the project

```bash
cd 2025-2029_AbhishekKumarMishra_25SCS1003001223_3rdSemester_2CSE31
```

### 3. Install frontend dependencies

```bash
npm install
```

### 4. Start the frontend

```bash
npm run dev
```

### 5. Backend setup

Open the backend directory:

```bash
cd hwc-backend
```

Install the backend dependencies:

```bash
npm install
```

Make sure MongoDB is available and the required database configuration is set before starting the backend.

## 🗄️ Database

The project uses **MongoDB** for storing application data such as:

* User information
* Wildlife incidents
* Wildlife movement data
* Prediction-related data

The backend uses **Mongoose** for database interaction.

## 🤖 AI Prediction Module

The prediction component analyzes available wildlife movement and incident data to identify patterns and estimate potential future conflict or movement risk.

The objective is to provide an additional decision-support layer for wildlife monitoring rather than replacing human judgment.

## 📊 Internship Documentation

The `Internship_Documents` folder contains the supporting documentation related to the project, including:

* Internship Certificate
* Internship Report
* Project Presentation

## 🎯 Project Objective

The main objective of this project is to develop a technology-assisted platform that can help:

* Monitor wildlife movement
* Record human-wildlife conflict incidents
* Identify potential risk zones
* Analyze historical data
* Support wildlife authorities and field teams
* Improve awareness and response to wildlife-related incidents

## 🔮 Future Improvements

Possible future enhancements include:

* Real-time GPS-based wildlife tracking
* Integration with IoT and camera-trap systems
* SMS and mobile notifications
* Improved machine learning models with larger datasets
* Mobile application for field officers
* More advanced geospatial analysis
* Automated alerts for high-risk areas

## 👨‍💻 Author

**Abhishek Kumar Mishra**

B.Tech – Computer Science and Engineering
IILM University, Greater Noida

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
