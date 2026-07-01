# 🚀 Codeforces Metric Engine

A modern, high-performance, single-page web application designed for competitive programmers to track their live standings, submission habits, and contest history on Codeforces. 

Featuring a premium dark-mode dashboard interface, this tool aggregates data across multiple public Codeforces API endpoints seamlessly in real-time.

![Dashboard Preview](https://via.placeholder.com/850x450?text=Codeforces+Dashboard+Preview) ---

## ✨ Features

* **📇 Live Profile Hub:** Displays the user's current rank, live rating, peak rating, and avatar. The profile layout dynamically tints its border accent to match the official Codeforces rank coloring system (e.g., Expert Blue, Master Orange, Grandmaster Red).
* **📊 Rating-Wise Lifetime Distribution:** Aggregates all accepted (`OK`) submissions, filters out duplicate solutions to the same problem, and maps them across custom difficulty chip stats.
* **📅 Rolling 7-Day Output Timeline:** Tracks a rolling 7-day calendar window, breaking down exactly how many problems of each difficulty tier were resolved day-by-day.
* **🏆 Contest Performance Matrix:** Showcases the user's last 6 official contest appearances, capturing global rank finishes, net rating deltas ($\Delta$), and updated rating values.
* **⌨️ Smart Input Control:** Supports standard search buttons as well as immediate form submission via the `Enter` key.

---

## 🛠️ Tech Stack

* **HTML5:** Semantic architecture layout.
* **CSS3:** Custom properties (CSS variables), CSS Grid, Flexbox, and customized native scrollbars.
* **JavaScript (ES6+):** Asynchronous multi-endpoint fetching (`Promise.all`), `Set` operations for automatic problem deduplication, and dynamic DOM injection.
* **API Stream:** Public Codeforces Web API (`user.info`, `user.status`, `user.rating`).

---

## 🚀 Getting Started

Since this application is completely serverless and independent of heavy build tools, running it is incredibly straightforward:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/iam-rahul87/codeforcesMetricEngine]
