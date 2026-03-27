# 🧠 Snehal AIML Planner

> A daily planner + tracker + roadmap system built for AIML students preparing for internships.

![HTML](https://img.shields.io/badge/HTML-5-orange?style=flat-square)
![CSS](https://img.shields.io/badge/CSS-3-blue?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat-square)
![Storage](https://img.shields.io/badge/Storage-LocalStorage-purple?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 📌 Overview

**Snehal AIML Planner** is a single-file, zero-dependency productivity web app designed for a 3rd-year AI/ML student. It combines a daily task system, a 30-day structured roadmap, topic progress tracker, and an internship application manager — all in one beautifully designed dark-mode interface.

No server. No login. No installation. Just open the HTML file in your browser and start grinding.

---

## ✨ Features

### 📅 Today Tab
- **Daily checklist** with 7 task categories (DSA, Python, AI/ML, NLP/GenAI, Project, Applications, LinkedIn DMs)
- **Live progress bar** showing daily completion percentage
- **Dynamic task panel** — tasks change based on which day you're on (Day 1–30)
- **Day slider** to jump to any day and preview its tasks
- **Motivational banner** + rotating inspirational quotes

### 🗺️ 30-Day Roadmap Tab
- Visual grid of all 30 days organized by week
- Click any day to expand and see its specific tasks
- Today's day is highlighted with a purple glow
- Completed days are marked in green

### 📚 Topics Tab
- 6 topic areas: Python, DSA, AI/ML, NLP, Generative AI, RAG
- Click each chip to mark individual topics as **learned**
- Per-topic progress bar fills as you learn more
- All progress is saved automatically

### 💼 Internship Tracker Tab
- Add applications with: Company, Role, Date Applied, Status
- Status options: Applied, Pending, Interview, Offer, Rejected
- Color-coded status badges
- Delete entries any time

### 📊 Stats Tab
- 9 stat cards: days completed, streak, tasks done, topics learned, apps sent, interviews, offers, and more
- Weekly breakdown with individual progress bars for each of the 4 weeks

---

## 🗂️ 30-Day Curriculum

| Week | Days | Focus Areas |
|------|------|-------------|
| Week 1 | 1–7 | Python Basics + Arrays & Strings DSA |
| Week 2 | 8–14 | HashMaps, Sliding Window, ML Fundamentals |
| Week 3 | 15–21 | NLP, Generative AI, Prompt Engineering, RAG |
| Week 4 | 22–30 | Build AI Chatbot + Resume Analyzer, Intensive Applications |

---

## 📚 Topics Covered

**Python** — Basics, OOP, comprehensions, generators, regex, file I/O

**DSA** — Arrays, Strings, Two Pointers, Sliding Window, HashMaps, Recursion, Sorting, Binary Search

**AI / ML** — Linear & Logistic Regression, Decision Trees, Overfitting, Cross-Validation, Evaluation Metrics

**NLP** — Tokenization, Bag of Words, TF-IDF, Word2Vec, GloVe, spaCy, Sentiment Analysis

**Generative AI** — LLM internals, GPT vs BERT, Prompt Engineering (zero-shot, few-shot, chain-of-thought, ReAct), API usage

**RAG** — Retrieval Augmented Generation, Vector DBs (FAISS, Chroma), LangChain pipeline, end-to-end RAG chatbot

---

## 🚀 Getting Started

### Option 1 — Open directly
1. Download `snehal-aiml-planner.html`
2. Double-click to open in any browser (Chrome, Firefox, Edge, Safari)
3. Start with Day 1 and check off tasks as you go

### Option 2 — Host locally
```bash
# Using Python
python -m http.server 8000
# Then visit: http://localhost:8000/snehal-aiml-planner.html
```

### Option 3 — Deploy to GitHub Pages
1. Push the HTML file to a GitHub repo
2. Enable GitHub Pages (Settings → Pages → Deploy from branch)
3. Access your planner at `https://yourusername.github.io/repo-name/snehal-aiml-planner.html`

---

## 💾 Data Persistence

All data is saved automatically in your browser's **localStorage** under the key `snehalAIMLPlanner_v2`. This includes:

- Current day and streak count
- Daily checklist states (per day)
- Completed days list
- Learned topics (per category)
- Internship applications

> ⚠️ Clearing browser data or cache will erase your progress. To back up, open DevTools → Application → Local Storage → copy the value.

---

## 🎨 Design

- **Theme:** Dark mode with a lavender/violet-to-pink gradient palette
- **Typography:** Syne (headings) + DM Sans (body)
- **Animations:** CSS transitions, progress bar animations, fade-in on tab switch
- **Responsive:** Works on desktop, tablet, and mobile
- **Zero dependencies:** No frameworks, no npm, no build step

---

## 📁 Project Structure

```
snehal-aiml-planner/
└── snehal-aiml-planner.html   # Entire app — HTML + CSS + JS in one file
└── README.md                  # This file
```

---

## 🛠️ Customization

All data lives at the top of the `<script>` block inside the HTML file:

| Variable | What to change |
|---|---|
| `QUOTES` | Add your own motivational quotes |
| `CHECKLIST_ITEMS` | Modify the 7 daily task categories |
| `DAY_PLAN` | Edit tasks for any specific day |
| `WEEK_META` | Change week titles or day ranges |
| `TOPICS` | Add/remove topics in any category |

---

## 🔮 Roadmap (Future Improvements)

- [ ] Export progress as PDF report
- [ ] Dark/light mode toggle
- [ ] Calendar heatmap view (like GitHub contributions)
- [ ] Pomodoro timer integration
- [ ] Email/WhatsApp daily reminder via backend
- [ ] Shareable progress card for LinkedIn
- [ ] Multi-user support with Firebase

---

## 🙌 Acknowledgements

Built with 💜 for **Snehal** — a 3rd-year AIML student on the path to landing an AI internship. Stay consistent, trust the process, and ship the projects.

---

## 📄 License

MIT License — free to use, modify, and share.

---

> *"Every line of code you write today is one step closer to that offer letter."*# snehal-s-planner
