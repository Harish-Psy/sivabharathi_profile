# Siva Bharathi — UI/UX Designer Portfolio

A modern, responsive personal portfolio website built with vanilla HTML, CSS, and JavaScript.

---

## 🚀 How to Run

### Option 1: Open Directly (Simplest)

Just double-click the file:

```
d:\sivabharathi_profile\index.html
```

Or right-click → **Open with** → your preferred browser (Chrome, Edge, Firefox).

---

### Option 2: Local Development Server (Recommended)

A local server ensures all features work correctly (fonts, smooth scroll, etc.).

**Prerequisites:** [Node.js](https://nodejs.org/) installed on your machine.

```bash
# Navigate to the project folder
cd d:\sivabharathi_profile

# Start a local server (auto-installs http-server)
npx -y http-server . -p 8080 -c-1

# Open in your browser
# → http://localhost:8080
```

---

### Option 3: VS Code Live Server

1. Open the project folder in **VS Code**
2. Install the **Live Server** extension (by Ritwick Dey)
3. Right-click `index.html` → **Open with Live Server**
4. The site opens automatically at `http://127.0.0.1:5500`

---

## 📁 Project Structure

```
sivabharathi_profile/
├── index.html        ← Main website (all sections)
├── css/
│   └── styles.css    ← Design system, themes, responsive styles
├── js/
│   └── main.js       ← Interactions, dark mode, animations
└── README.md         ← This file
```

---

## ✨ Features

- 🌙 **Dark / Light Mode** — Toggle in the navigation bar, preference saved
- 📱 **Fully Responsive** — Desktop, tablet, and mobile layouts
- 🎯 **9 Sections** — Hero, About, Services, Case Studies, Skills, Timeline, Awards, Testimonials, Contact
- ✨ **Scroll Animations** — Elements reveal as you scroll
- 📋 **Case Study Modals** — Click any project card for full details
- 📊 **Animated Counters** — Stat numbers animate on scroll
- 🍔 **Mobile Menu** — Hamburger menu for small screens
- 📬 **Contact Form** — With validation and feedback

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 (semantic) |
| Styling | Vanilla CSS (custom properties, Grid, Flexbox) |
| Interactions | Vanilla JavaScript (no dependencies) |
| Font | [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts |

**No build step. No npm install. No dependencies.** Just open and go.
