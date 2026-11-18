# 🎓 StudentHub

**Study Smart. Achieve More.**

StudentHub is a lightweight, all-in-one student platform built with plain HTML, CSS and JavaScript. It brings together the everyday tools a student needs, a study planner, notes, a task manager and a CGPA calculator, in a clean, colorful interface with no frameworks, build steps or dependencies.

## ✨ Features

| Tool | Page | What it does |
|------|------|--------------|
| 📅 **Study Planner** | `planner.html` | Add subjects with a study time to build a daily schedule. Delete entries when plans change. |
| 📝 **Smart Notes** | `notes.html` | Write a titled note, save it to the page, and delete it when you're done. |
| ✅ **Task Manager** | `todo.html` | Add assignments and daily tasks, mark them complete (strikethrough), or remove them. |
| 🎯 **CGPA Calculator** | `calculator.html` | Enter up to four semester CGPAs (0–10 scale) and get the average. |

The landing page (`index.html`) includes a hero section, a progress overview card, feature cards linking to each tool, and a responsive layout that works on desktop, tablet and mobile.

## 📁 Project Structure

```
studenthub/
├── index.html       # Home / landing page
├── planner.html     # Study planner
├── notes.html       # Smart notes
├── todo.html        # Task manager
├── calculator.html  # CGPA calculator
└── README.md
```

Each page is fully self-contained, with its own styles and scripts inline.

## 🚀 Getting Started

No installation required.

1. Clone or download the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```
2. Open `index.html` in any modern browser.

Optionally, serve it locally:

```bash
# Python 3
python -m http.server 8000
# then visit http://localhost:8000
```

## 🛠️ Built With

- **HTML5** for structure
- **CSS3** for styling (Flexbox, Grid, gradients, media queries)
- **Vanilla JavaScript** for interactivity

## ⚠️ Current Limitations

- Planner entries, notes and tasks are **not persisted**; they reset when the page is refreshed.
- The CGPA calculator computes a simple average of the semester values entered, not a credit-weighted CGPA.
- The progress figures on the home page are static placeholders.

## 🗺️ Roadmap Ideas

- Save data with `localStorage` so it survives page reloads
- Credit-weighted CGPA calculation with per-subject grades
- Sanitize user input before rendering it into the page
- Shared stylesheet and navigation across pages
- Dark mode

## 🤝 Contributing

Contributions, issues and feature requests are welcome. Fork the repo, create a branch, and open a pull request.

## 📄 License

Add a license of your choice (for example, [MIT](https://choosealicense.com/licenses/mit/)).

---

Built for students ❤️
