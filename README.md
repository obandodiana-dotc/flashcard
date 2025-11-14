# 🇩🇪 1-Month German A1 Plan (Day-by-Day) ✨

**A self-contained, gamified web application for mastering German A1 fundamentals in 30 days. A personal project demonstrating pure front-end development and commitment to language learning.**

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Built with Vanilla JS](https://img.shields.io/badge/Tech-Vanilla_JS-yellow.svg)](https://developer.mozilla.org/en/docs/Web/JavaScript)
[![CEFR Level Target](https://img.shields.io/badge/CEFR_Level-A1-orange.svg)](https://www.coe.int/en/web/common-european-framework-reference-languages/level-descriptions)

## 🌟 Project Overview

This is a **personal educational project** developed to serve as a structured and motivating digital tutor for German A1. The primary goal was to create a comprehensive **30-day learning curriculum** that is fully **self-contained**.

The application is built exclusively with **HTML, CSS (Tailwind via CDN), and pure JavaScript (Vanilla JS)**. This design choice highlights the ability to manage complex state and persistent data without relying on any back-end or database. All user progress, streaks, and journal entries are securely saved locally using the browser's `localStorage`.

## 💡 Personal Motivation & Technical Goals

This project addresses a dual objective:

1.  **Linguistic Goal:** Provide a clear, step-by-step path to achieve conversational proficiency at the German A1 level.
2.  **Technical Goal (Portfolio Piece):** Showcase strong foundational front-end skills by implementing:
    * **State Management:** Handling the daily progress, task completion, and long-term streak entirely with **Vanilla JavaScript** and `localStorage`.
    * **Data Persistence:** Developing robust **Export/Import** functionality to allow users to back up and transfer their progress (as a JSON file).
    * **Modular UI:** Utilizing JavaScript to dynamically render complex daily lesson content and task lists from a simple data array.
    * **Modern Styling:** Rapidly building a clean, responsive, and intuitive interface using **Tailwind CSS utilities**.

## 🎯 Key Educational Features

The application is engineered to promote effective self-study:

| Feature | Pedagogical Benefit |
| :--- | :--- |
| **30-Day Curriculum** | Breaks down the German A1 syllabus (greetings, verbs *sein/haben*, articles, *W-Fragen*) into manageable daily units. |
| **Lesson & Task Tabs** | Separates theory (*Clase del Día*) from active application (*Práctica y Tareas*), ensuring both understanding and practice occur. |
| **Practice Journal** | A dedicated text area for daily writing prompts, crucial for active language production and long-term memory. |
| **Gamified Metrics** | Displays a **Total Progress (%)** and a **Streak** counter to encourage consistency and celebrate learning milestones. |
| **Wort des Tages** | Focuses the learner on a single key vocabulary word daily, complete with plural form and translation. |

## 💻 Technologies Used

| Technology | Role in the Project |
| :--- | :--- |
| **HTML5** | Core application structure and content templates. |
| **Vanilla JavaScript** | All business logic, DOM manipulation, and state persistence via `localStorage`. |
| **Tailwind CSS (CDN)** | Utility-first CSS framework for a responsive, modern, and clean design. |
| **Canvas Confetti** | Provides positive visual feedback upon task completion. |

## 🚀 Installation and Usage

This project is a static web application and requires no complex setup or server.

1.  **Download:** Clone the repository or download the main `index.html` file.
2.  **Run:** Simply double-click the `index.html` file.
3.  **Start Learning:** The application will open immediately in any modern web browser.

> **Data Safety:** Since all data is stored locally, it is highly recommended to use the **Export** button in the Journal section regularly to save a backup of your progress (as a JSON file) in case the browser cache is cleared.

## 🤝 Contributions

While this project originated as a personal learning initiative, pull requests are welcome for:

* Improving the clarity or accuracy of the German lesson content.
* Enhancing the front-end performance or accessibility (A11Y).
* Adding simple interactive quizzes or grammar exercises.

---

## 📜 License

This project is distributed under the **MIT License**. See the `LICENSE` file for more details.

***

**Viel Erfolg beim Deutschlernen!** (Good luck with your German learning!)
