🏋️‍♂️ FitTrack Pro

A premium, high-performance fitness tracking application built with React and modern frontend tooling.
Designed for visual excellence, performance, and data-driven fitness insights.

📌 Overview

FitTrack Pro is a modern Single Page Application (SPA) that enables users to:

Maintain daily fitness streaks

Log and track workout sessions

Analyze performance trends through interactive charts

Monitor goals and personal health metrics

The application emphasizes clean architecture, premium UI design, and scalable frontend practices.

✨ Core Features
🚀 Dynamic Dashboard

Real-time streak tracking

KPI summary cards

Monthly goal progress visualization

Performance overview in a single glance

🏋️ Workout Library

Categorized workout plans:

Strength

Cardio

Yoga

Multi-layer filtering:

Beginner

Intermediate

Advanced

Structured and scalable data rendering

📊 Progress Analytics

Interactive charts powered by Recharts

Track:

Weight trends

Calories burned

Workout frequency

Responsive and visually intuitive data visualization

📝 Session Logging

Advanced workout logger

Live form validation

Session rating system

Historical workout tracking

👤 User Profiles

Editable profile management

Built-in BMI calculator

Personal goal configuration

🎨 Premium UI/UX

Modern dark theme

Smooth gradient transitions

Glassmorphism effects

Fully responsive layout

Centralized design system using CSS Variables

🛠️ Tech Stack
Technology	Role	Reason for Selection
React 18	UI Framework	Component-based architecture for scalable SPA development
Vite 5	Build Tool	Ultra-fast HMR and optimized production builds
Recharts	Data Visualization	Declarative charting for React applications
CSS Variables	Design System	Centralized theming and maintainable styling
JSON Server	Mock Backend	Rapid prototyping with RESTful API simulation
🏗️ Architecture Highlights

Modular component structure

Centralized styling system

Clean separation of UI and data layer

RESTful data simulation via JSON Server

Optimized build pipeline with Vite

📂 Project Structure
fitness-tracker/
│
├── src/
│   ├── App.jsx              # Core application logic & routing
│   ├── main.jsx             # React entry point
│   ├── index.css            # Global styles & design system
│   ├── components/          # Reusable UI components
│   └── assets/              # Static assets
│
├── public/
│   └── screenshots/         # Documentation screenshots
│
├── db.json                  # Mock database
├── vite.config.js           # Vite configuration
├── netlify.toml             # Deployment config
└── package.json
🏁 Getting Started
🔧 Prerequisites

Node.js ≥ v18

npm ≥ v9

📥 Installation
git clone <repository-url>
cd fitness-tracker
npm install
▶ Running the Application

You must run both the frontend and mock API server.

1️⃣ Start the Mock API
npx json-server --watch db.json --port 3000
2️⃣ Start the Development Server
npm run dev
3️⃣ Open in Browser
http://localhost:5173
🌍 Deployment

The project is deployment-ready and supports:

Netlify

Vercel

Any static hosting provider

Ensure the mock API is replaced with a production backend before deployment.

🚀 Future Enhancements (Roadmap)

 Migration from db.json to MySQL/PostgreSQL

 User Authentication (JWT-based login system)

 Persistent user-specific data storage

 Social features & leaderboard system

 Mobile app using React Native

 Backend integration (Node.js / Express)

📈 Learning Outcomes

This project demonstrates:

Advanced React component architecture

State management patterns

Data visualization implementation

UI/UX design principles

API integration workflows

Frontend performance optimization