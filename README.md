# 🗄️ SQL Academy — Interactive SQL Server Learning App

![SQL Academy](https://img.shields.io/badge/SQL-Server%20%2F%20MS%20SQL-blue?style=for-the-badge&logo=microsoftsqlserver)
![HTML](https://img.shields.io/badge/Built%20With-HTML%20%2F%20JS-orange?style=for-the-badge&logo=html5)
![SQLite](https://img.shields.io/badge/Engine-SQLite%20WASM-lightgrey?style=for-the-badge&logo=sqlite)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> A fully interactive, browser-based SQL Server learning platform — no installation, no backend, no login required. Just open and start learning.

---

## 🌐 Live Demo

👉 **[Launch SQL Academy](https://suneelchalla.github.io/sql-academy/index.html)**

---

## ✨ Features

### 📚 30 Structured Lessons
Covers everything from the basics to advanced SQL Server concepts:

| Module | Topics |
|--------|--------|
| 🚀 Getting Started | SSMS setup, CREATE / ALTER / DROP Database, Tables & Data Types |
| 🔒 Constraints & Keys | DEFAULT, FOREIGN KEY (Cascading), CHECK, IDENTITY, UNIQUE |
| 🔍 Querying Data | SELECT, GROUP BY, JOINs (all types), Self Join, Anti-Join, UNION |
| ❓ NULLs & Set Operators | ISNULL, COALESCE, UNION / UNION ALL |
| 🔤 String Functions | LEN, UPPER/LOWER, SUBSTRING, CHARINDEX, REPLACE, STUFF, PATINDEX |
| 📅 Date & Time | GETDATE, DATEADD, DATEDIFF, DATENAME, DATEPART, ISDATE |
| 🔄 Conversion & Math | CAST, CONVERT, TRY_CAST, ABS, ROUND, CEILING, FLOOR |
| ⚙️ User-Defined Functions | Scalar UDFs, Inline TVFs, Multi-statement TVFs |
| 🗂️ Temporary Tables | #Temp, ##Global Temp, @Table Variables, CTEs |

### 🖥️ Live SQL Playground
- **SQLite WASM engine** runs entirely in the browser — no server needed
- 6 pre-loaded sample tables: `Employees`, `Departments`, `Projects`, `EmployeeProjects`, `Customers`, `Orders`
- Write and run any SQL query instantly
- **Save / Export / Import** your database between sessions

### 📝 Built-in Quizzes
- Every lesson ends with instant-graded questions
- **MCQ**, **SQL query**, and **text answer** question types
- SQL questions are auto-graded by actually running your query and comparing results

### 🎓 Three Final Tests
- **Level 1** — Foundations (DDL, constraints, basic SELECT)
- **Level 2** — Querying & Joins
- **Level 3** — Advanced (NULLs, strings, dates, conversions)

### 🗂️ Schema Quick Reference
- Collapsible schema panel appears above every quiz
- Shows all 6 tables with columns, PK/FK badges, and row counts
- **▶ Preview** button loads live data instantly

### 🔍 Google Search Integration
- Floating Google search button on every page
- Click → search bar opens → searches in a new tab
- Remembers your recent searches (up to 8) with one-click re-search

---

## 🚀 Getting Started

### Option 1 — Use it online
Click the **Live Demo** link above. Nothing to install.

### Option 2 — Run locally
```bash
# Clone the repo
git clone https://github.com/Suneelchalla/sql-academy.git

# Open in browser — no server needed!
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

### Option 3 — Download the file
1. Go to the repository
2. Click `index.html` → **Download raw file**
3. Open the downloaded file in any modern browser

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Vanilla HTML / CSS / JS** | Zero dependencies, no framework |
| **[sql.js](https://github.com/sql-js/sql.js/)** (SQLite WASM) | In-browser SQL engine |
| **Google Fonts** | Space Grotesk + Inter + JetBrains Mono |
| **GitHub Pages** | Free hosting |

No Node.js. No npm. No build step. It's a single HTML file.

---

## 📁 Project Structure

```
sql-academy/
│
├── index.html        # The entire app — all CSS, JS, and content in one file
└── README.md         # You are here
```

---

## 🖼️ Screenshots

### Dashboard
> Course overview with progress tracking and module navigation

### Lesson View
> Rich lesson content with layman explanations, real-world analogies, and live code examples

### SQL Console
> Run queries against the live sample database right in the browser

### Quiz
> Instant-graded questions with schema reference panel

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repo
2. Create a branch: `git checkout -b feature/my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push: `git push origin feature/my-new-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and share.

---

## 👤 Author

**Suneelchalla**

- GitHub: [@Suneelchalla](https://github.com/Suneelchalla)

---

## ⭐ Show Your Support

If this project helped you learn SQL, give it a **⭐ star** on GitHub — it means a lot!

---

*Built with ❤️ for SQL learners everywhere.*
