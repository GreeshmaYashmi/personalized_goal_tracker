# Personalized_goal_tracker
<div align="center">


**A minimal full-stack personal tracking system to monitor tasks, consistency, health habits, and career progress with real-time analytics and streak-based discipline.**  
Stay consistent. Track progress. Build discipline.

![GitHub last commit](https://img.shields.io/github/last-commit/your-username/ai-journey-tracker)
![GitHub stars](https://img.shields.io/github/stars/your-username/ai-journey-tracker?style=social)
![License](https://img.shields.io/badge/license-MIT-blue)

</div>

---

## 📖 Overview

Most productivity tools track tasks — but ignore **consistency**, **reality checks**, and **health balance**.  
This tracker bridges that gap by monitoring your:

| Dimension | What It Tracks |
|-----------|---------------|
| 🧠 Output | Tasks, DSA problems |
| ⏱️ Effort | Hours of focused work |
| 🔥 Discipline | Streaks |
| 🧘 Lifestyle | Health + Life logs |

> *"Consistency beats intensity."*

---

## ✨ Features

### 📌 Core Productivity

| Feature | Description |
|---------|-------------|
| ✅ Task Tracker | Full CRUD with categories |
| 🔥 Streak System | Tracks daily consistency |
| 📊 Dashboard | Real-time stats overview |
| 🧠 Daily Reflection | Log learnings & improvements |

### 💼 Career Tracking

| Field | Details |
|-------|---------|
| Company & Role | Track every application |
| Status | `Applied` → `Interview` → `Offer` / `Rejected` |
| Notes | Add context per application |

### 🧘 Health & Lifestyle

| Habit | Target |
|-------|--------|
| 💧 Water Intake | 3–4 L/day |
| 🚶 Steps | 11k–20k/day |
| 🏋️ Gym | Daily log |
| 🧘 Meditation | Daily log |
| 📚 Reading | Daily log |
| 📓 Journaling | Daily log |

### 📈 Analytics & Graphs

- Weekly productivity (tasks + hours)
- Health trends (water + steps)
- Application funnel over time
- Monthly summaries & budget tracking

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | React (Hooks + Functional Components) |
| **HTTP Client** | Axios |
| **Charts** | Recharts |
| **Routing** | React Router |
| **Backend** | Spring Boot (REST API) |
| **ORM** | JPA / Hibernate |
| **Architecture** | Controller → Service → Repository |
| **Database** | MySQL |
| **Environment** | Linux (Ubuntu) |

---

## 🧱 Project Structure
ai-journey-tracker/
│
├── tracker-backend/
│   ├── entity/
│   ├── repository/
│   ├── service/
│   ├── controller/
│   └── application.properties
│
└── journey-frontend/
└── src/
├── api/
├── components/
├── pages/
├── App.jsx
└── index.js

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ai-journey-tracker.git
cd ai-journey-tracker
```

### 2️⃣ Backend Setup (Spring Boot)

```bash
cd tracker-backend
./gradlew bootRun
```

Configure your database in `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/journey_tracker
spring.datasource.username=root
spring.datasource.password=your_password
```

### 3️⃣ Frontend Setup (React)

```bash
cd journey-frontend
npm install
npm start
```

---

## 🌐 Application URLs

| Service | URL |
|---------|-----|
| Frontend | http://localhost:3000 |
| Backend API | http://localhost:8080 |

---

## 📊 Dashboard Metrics

| Metric | Description |
|--------|-------------|
| ✅ Tasks Completed | Daily & weekly count |
| ⏱️ Hours Studied | Total focused work time |
| 🔢 DSA Problems | Problems solved |
| 💼 Job Applications | Total & by status |
| 💧 Water Intake | Daily vs. target |
| 🚶 Steps | Daily vs. target |
| 🔥 Current Streak | Consecutive valid days |

---

## 🔥 Streak Logic

A day is counted as **valid** if either condition is met: 

✅ ≥ 2 tasks completed
OR
✅ ≥ 2 hours of focused work

---

## 🎨 UI Design

| Element | Value |
|---------|-------|
| 🎨 Palette | Japanese earthy tones |
| 🟤 Colors | Beige, Sand, Brown, Charcoal |
| 🖥️ Style | Minimal, clean, content-first |

---

## 📌 Roadmap

| Feature | Status |
|---------|--------|
| 🔐 JWT Authentication | 🔜 Planned |
| 🤖 AI Productivity Insights | 🔜 Planned |
| 🔔 Smart Reminders | 🔜 Planned |
| 📱 Mobile App (React Native) | 🔜 Planned |
| ☁️ Deployment (AWS / Vercel) | 🔜 Planned |

---

## 💡 Who Is This For?

- 🎓 Students preparing for placements
- 🤖 Aspiring AI/ML engineers
- 💻 Developers building personal discipline systems

---

## 👤 Author

**Your Name**  
AI/ML Enthusiast | Full Stack Developer

[![GitHub](https://img.shields.io/badge/GitHub-your--username-181717?logo=github)](https://github.com/your-username)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin)](https://linkedin.com/in/your-profile)

---

<div align="center">

⭐ **If this project helps you, consider giving it a star!** ⭐

</div>
