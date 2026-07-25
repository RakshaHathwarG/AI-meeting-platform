# 🧠 AI Meeting Intelligence Platform

> An AI-powered meeting preparation assistant that researches companies, analyzes industry trends, and generates executive-ready meeting briefs using multiple AI agents.

---

## 📖 Overview

Preparing for an important business meeting often requires researching the company, understanding industry trends, planning an agenda, and anticipating possible questions.

This project automates the entire process using CrewAI agents powered by Google's Gemini 2.5 Flash model.

The generated report includes:

- Executive Summary
- Company Background
- Industry Insights
- Meeting Agenda
- Strategic Recommendations
- Expected Questions & Answers

---

## ✨ Features

✅ Company Research

✅ Industry Analysis

✅ Executive Meeting Brief

✅ AI-generated Meeting Agenda

✅ Strategic Recommendations

✅ Potential Questions & Answers

✅ Clean Streamlit User Interface

---

## 🏗️ Architecture

![Architecture](images/architecture.png)

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Backend |
| Streamlit | User Interface |
| CrewAI | Multi-Agent Orchestration |
| Gemini 2.5 Flash | Large Language Model |
| Serper API | Web Search |
| Google Gemini API | AI Responses |

---

## 🤖 AI Workflow

```text
User Inputs
      │
      ▼
Meeting Context Agent
      │
      ▼
Industry Research Agent
      │
      ▼
CrewAI
      │
      ▼
Gemini 2.5 Flash
      │
      ▼
Executive Meeting Brief
```

---

## 📷 Application Screenshots

### Home Page

![Home](images/home.png)

---

### Meeting Information

![Input](images/input.png)

---

### Generated Executive Brief

![Output](images/output.png)

---

## 📂 Project Structure

```text
AI-Meeting-Platform
│
├── meeting_agent.py
├── requirements.txt
├── README.md
├── .gitignore
└── images
    ├── home.png
    ├── input.png
    ├── output.png
    └── architecture.png
```

---

## 🚀 Installation

```bash
git clone https://github.com/RakshaHathwarG/AI-meeting-platform.git

cd AI-meeting-platform

pip install -r requirements.txt

streamlit run meeting_agent.py
```

---

## 🔑 API Keys Required

- Google Gemini API Key
- Serper API Key

---

## 👩‍💻 Author

Raksha Hathwar
