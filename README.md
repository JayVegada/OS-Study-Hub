# ⚙️ OS Study Hub

<!-- Jay Vegada | Pirate ☠ -->

<div align="center">

![GTU](https://img.shields.io/badge/GTU-Semester%204-blue?style=for-the-badge&logo=graduation-cap&logoColor=white)
![Subject](https://img.shields.io/badge/Subject-Operating%20Systems-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)

**An interactive, exam-focused study resource for Operating Systems**  
*Built for GTU Semester 4 students — ELI10 analogies, structured answers, exam-ready.*

[🚀 Live Site](https://jayvegada.github.io/OS-Study-Hub) · [📂 Browse Topics](#-topics-covered) · [🎯 Exam Prep](#-exam-prep-features)

</div>

---

## 📖 What is this?

**OS Study Hub** is a purpose-built interactive study website for the **Operating Systems** subject under **Gujarat Technological University (GTU)** — Semester 4, B.E. Computer Engineering.

OS is one of those subjects where concepts look simple but exam answers need precision. This hub gives you:

- **ELI10 analogies** that make abstract OS concepts stick (processes as employees, scheduler as a manager, etc.)
- **Searchable question bank** organized by unit
- **Filter by Priority** (High / Medium / Low) for focused revision
- **Accordion-style answer cards** — test yourself, then reveal
- **Exam-frequency indicators** based on PYQ analysis

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 🔍 **Smart Search** | Instantly filter questions by keyword across all units |
| 🏷️ **Mark-wise Filter** | View only 2-mark, 4-mark, or 7-mark questions |
| 🧠 **ELI10 Mode** | Toggle plain-English analogies alongside formal answers |
| 📐 **Unit-wise Tabs** | Jump to any unit without scrolling through everything |
| 🎯 **Exam Frequency Tags** | High / Medium / Low frequency based on PYQ analysis |
| 📱 **Responsive Design** | Works on mobile, tablet, and desktop |
| ⚡ **No Install Needed** | Pure HTML/CSS/JS — just open and study |

---

## 📚 Topics Covered

> Full syllabus coverage as per GTU B.E. (Computer Engineering) Semester 4

| Unit | Topics |
|------|--------|
| **Unit 1** | Introduction to OS — Types, Structure, System Calls, OS Services |
| **Unit 2** | Process Management — Process States, PCB, Context Switching, Threads |
| **Unit 3** | CPU Scheduling — FCFS, SJF, Round Robin, Priority, Multilevel Queue |
| **Unit 4** | Process Synchronization — Critical Section, Mutex, Semaphores, Monitors, Classic Problems |
| **Unit 5** | Deadlock — Conditions, Prevention, Avoidance (Banker's Algorithm), Detection & Recovery |
| **Unit 6** | Memory Management — Paging, Segmentation, Virtual Memory, Page Replacement Algorithms |
| **Unit 7** | File Systems & I/O — File Allocation, Directory Structure, Disk Scheduling, Protection |

---

## 🎯 Exam Prep Features

### 🔖 Question Bank
All questions sourced from:
- GTU Previous Year Papers (2019–2024)
- Standard textbook exercises
- Conceptual questions on algorithms (scheduling, page replacement, Banker's)

### 🏷️ Frequency System
Each question card is tagged:

```
🔴 HIGH   → Appeared in 3+ recent papers — must prepare
🟡 MEDIUM → Appeared 1–2 times — good to cover
🟢 LOW    → Rarely asked — revise if time permits
```

### 🧠 ELI10 Analogy System
Every complex concept has a plain-English analogy:

```
Semaphore      → Token counter at a parking lot gate
Deadlock       → 4 cars at a 4-way stop, all waiting for others to move
Banker's Algo  → Bank checking if it can lend money and still serve everyone else
Page Fault     → Looking for a book on your desk, not finding it, fetching from shelf
```

### 📝 Answer Format
Answers follow the GTU exam writing style:
- **3-mark:** Direct, 2–4 line definition or comparison
- **4-mark:** Explanation with diagram/table where needed
- **7-mark:** Full structured answer with diagrams, examples, and sub-points

---

## 🛠️ Tech Stack

```
HTML5        → Structure
CSS3         → Styling, responsive layout, animations
Vanilla JS   → Search, filter, accordion, ELI10 toggle, tab switching
GitHub Pages → Hosting (zero cost, zero setup)
```

No frameworks. No dependencies. No build step.

---

## 🚀 Getting Started

### Option 1 — Use the Live Site (Recommended)
```
https://jayvegada.github.io/OS-Study-Hub
```

### Option 2 — Run Locally
```bash
git clone https://github.com/JayVegada/os-notes.git
cd OS-Study-Hub
open index.html
```

---

## 📁 Project Structure

```
os-notes/
│
├── index.html          # Main study hub — all units, search, filters, ELI10 toggle
├── style.css           # Stylesheet — dark theme, card layout
├── script.js           # Search, filter, accordion, ELI10 logic
│
├── data/
│   ├── unit1.js        # Q&A data — OS Introduction & Structure
│   ├── unit2.js        # Q&A data — Process Management
│   ├── unit3.js        # Q&A data — CPU Scheduling
│   ├── unit4.js        # Q&A data — Process Synchronization
│   ├── unit5.js        # Q&A data — Deadlock
│   ├── unit6.js        # Q&A data — Memory Management
│   └── unit7.js        # Q&A data — File Systems & I/O
│
└── README.md
```

---

## 📌 Reference Books

As per GTU syllabus:

1. **Operating System Concepts** — Silberschatz, Galvin, Gagne *(Primary — "Dinosaur Book")*
2. **Modern Operating Systems** — Andrew S. Tanenbaum
3. **Operating Systems: Internals and Design Principles** — William Stallings

---

## 🤝 Contributing

Found a wrong answer? Missing topic? Better analogy?

1. Fork this repo
2. Make your changes
3. Open a Pull Request with a short description

---

## 👤 Author

**Jay Vegada**  
B.E. Computer Engineering — Semester 4  
Ahmedabad Institute of Technology (AIT), GTU

[![GitHub](https://img.shields.io/badge/GitHub-JayVegada-black?style=flat-square&logo=github)](https://github.com/JayVegada)

---

## 📄 License

MIT License — fork, share, and build on it freely.

---

<div align="center">

*Built with 💻 and the fear of a 7-mark deadlock question.*  
*If this helped you pass, consider starring ⭐ the repo.*

</div>
