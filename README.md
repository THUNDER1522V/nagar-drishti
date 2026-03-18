# 🏙️ Nagar-Drishti — District Intelligence System

<p align="center">
  <img src="https://img.shields.io/badge/AI-Gemini_API-blue?style=for-the-badge&logo=google" />
  <img src="https://img.shields.io/badge/Backend-FastAPI-009688?style=for-the-badge&logo=fastapi" />
  <img src="https://img.shields.io/badge/Frontend-React_18-61DAFB?style=for-the-badge&logo=react" />
  <img src="https://img.shields.io/badge/Automation-n8n-EA4B71?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

> **AI-powered civic intelligence platform** that monitors district-level issues, predicts infrastructure failures, and accelerates government response — built for Bharat's 800+ districts.

---

## 🚨 Problem Statement

India's district administration receives **thousands of civic complaints daily** — potholes, waterlogging, broken streetlights, sanitation failures. But:

- ❌ No unified tracking system
- ❌ Manual classification wastes hours
- ❌ Citizens have zero visibility on resolution
- ❌ Officials react instead of predict

**Nagar-Drishti solves this with AI.**

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 📡 Real-time Issue Tracking | Citizens report via web/SMS, AI auto-classifies & routes |
| 🧠 Gemini AI Analysis | NLP on complaint data — extracts severity, category, urgency |
| ⚡ n8n Workflow Automation | Auto-escalation, official alerts, status SMS — zero manual effort |
| 🗺️ Geospatial Heat Maps | Visual hotspot mapping across ward boundaries |
| 📊 Predictive Intelligence | ML models predict infrastructure failures 3 weeks in advance |
| 🔒 Secure FastAPI Backend | JWT auth, rate limiting, end-to-end encryption |

---

## 🛠️ Tech Stack

```
Frontend   → React 18 + Vite + TailwindCSS
Backend    → Python 3.11 + FastAPI
AI Engine  → Google Gemini API
Automation → n8n Workflows
Database   → PostgreSQL
Realtime   → WebSockets
Deploy     → Docker + GitHub Actions
```

---

## 🚀 Quick Start

```bash
# Clone the repo
git clone https://github.com/THUNDER1522V/nagar-drishti.git
cd nagar-drishti

# Backend setup
cd backend
pip install -r requirements.txt
cp .env.example .env   # Add your Gemini API key
uvicorn main:app --reload

# Frontend setup
cd ../frontend
npm install
npm run dev
```

---

## 🏗️ Architecture

```
Citizen Report
      ↓
React Frontend  ──→  FastAPI Backend  ──→  Gemini API
                           ↓
                      PostgreSQL DB
                           ↓
                    n8n Automation Engine
                    ↙              ↘
            Official Alert      Citizen SMS Update
```

---

## 📸 Demo

🌐 **Live Demo:** [thunder1522v.github.io/nagar-drishti](https://thunder1522v.github.io/nagar-drishti)

---

## 👥 Team — Code Infantry

| Name | Role |
|---|---|
| Pushkar | Team Lead & AI Integration |

---

## 📄 License

MIT License — open source, free to use for any district administration.

---

<p align="center">Built with ❤️ for Bharat · HackXtreme 2025</p>
