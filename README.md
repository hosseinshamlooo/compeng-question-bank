# 🚀 KonkurCS — Gamified Persian CS Exam Prep

A Persian-first, RTL, gamified web platform for Iranian students preparing for Konkur, Computer Science university entrance exams, and Olympiad-style problem solving — built as a fast, modular MVP with zero backend.

## 🎯 What is this?

KonkurCS is a lightweight web app that turns dry CS exam prep into a game-like experience:

✅ Subject-based practice
✅ Difficulty filtering
✅ Randomized quizzes
✅ Streaks, XP, levels, badges
✅ Fully Persian (RTL) interface
✅ JSON-powered expandable question bank
✅ No backend required (pure frontend MVP)

Designed specifically for:

🇮🇷 Iranian students
🎓 10th–12th graders
⏳ Gap-year takers
🧠 Konkur & CS entrance exam candidates

## 🧩 Features
### 📚 Subjects

Data Structures & Algorithms
Operating Systems
Computer Architecture
Databases
Computer Networks
Artificial Intelligence
Signals & Systems

### 🎮 Gamification

XP system
Streak tracking
Levels
Badges
Session stats
Progress persistence via localStorage

## ⚡ Core Functionality

Choose subject
Choose difficulty or random
Instant feedback
Clean Persian RTL UI
Fully modular JSON question bank
Add new questions without touching JS

## 🏗️ Tech Stack

Layer	Tech
Frontend	HTML, CSS, Vanilla JS
Data	JSON
Direction	RTL Persian
Storage	Browser localStorage
Backend	❌ None (by design)

## 📂 Project Structure
/
├── index.html      # Main UI
├── style.css       # RTL styling + animations
├── app.js          # Game logic
├── questions.json  # Expandable question bank
└── README.md

## 🧠 Question Bank Format

Questions are stored in questions.json like this:

{
  "dsa": [
    {
      "id": 1,
      "difficulty": "easy",
      "question": "پیچیدگی زمانی الگوریتم جستجوی دودویی چیست؟",
      "options": ["O(n)", "O(log n)", "O(n log n)", "O(1)"],
      "answer": 1,
      "explanation": "در هر مرحله فضای جستجو نصف می‌شود."
    }
  ]
}


Add unlimited questions without touching code.