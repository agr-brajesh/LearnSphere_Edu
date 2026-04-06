# LearnSphere 🎓

> A frictionless, interactive online learning platform engineered for seamless discovery and dynamic user engagement.

**Built by Brajesh Agrawal · Web Programming Project — 2025**

🔗 **Live Demo:** [agr-brajesh.github.io/LearnSphere](https://agr-brajesh.github.io/LearnSphere/)

---

## ✨ Features

### 🔍 Intelligent Discovery
- **Live Search Bar** — Filters 12 dynamic courses by title, category, or instructor in real-time. Auto-scrolls to results.
- **Category Toggles** — Instant isolation of Web Development, Data Science, Design, Marketing, and Business tracks. Active states visually highlighted.
- **Sort Dropdown** — Orders the JavaScript data array by Featured, Top Rated, Duration, or alphabetically (A–Z) instantly.

### 📚 Frictionless Engagement
- **Expandable Accordion Modules** — Clicking 'Modules' triggers a smooth Vanilla JS accordion panel, revealing full curriculum titles and durations without navigating away.
- **Client-Validated Enrollment Modal** — 5-step enrollment flow: Trigger → Input Collection → Validation Gate (Regex email check) → Success State → Auto-Resolution (3-second close).
- **Persistent Save Course Functionality** — Heart icon serializes the course object into `localStorage`. Survives page reloads and browser closures. Auto-populates the Saved Courses section on return.

### 🏗️ Seamless Architecture
- **Responsive Tri-Screen Design** — CSS Flexbox & Grid guarantee a pristine layout on desktop, tablet, and mobile.
- **Smooth Navigation & Scroll Spy** — Sticky navbar highlights the active section (Home, Courses, Saved, About) based on exact scroll coordinates.
- **Integrated Mission & About Sections** — Full story, tech-to-value matrix, and impact statistics.

---

## 🛠️ Tech Stack

| Technology | Purpose | User Value |
|---|---|---|
| **HTML5** | Semantic Foundation | Accessibility, SEO, logical page structure |
| **CSS3 (Flexbox/Grid)** | Cross-Device Fluidity | Responsive design & smooth animations |
| **Vanilla JavaScript** | Zero-Reload Interactivity | Real-time DOM manipulation for filtering, sorting, accordions |
| **localStorage API** | Session Persistence | Save & retrieve courses across browser sessions — no backend |
| **Google Fonts** | Premium Typography | Playfair Display + DM Sans for trust and readability |

---

## 📁 Project Structure

```
LearnSphere/
├── index.html      ← Entire application (HTML + CSS + JS in one file)
└── README.md       ← This file
```

Zero dependencies. Zero build steps. Runs natively in any modern browser.

---

## 🚀 Running Locally

**Option 1 — Instant Access:**
Double-click `index.html` to open directly in Chrome, Firefox, Edge, or Safari.

**Option 2 — Developer Mode (Recommended):**
```bash
# If you have VS Code with Live Server extension:
# Right-click index.html → Open with Live Server
# Opens at http://127.0.0.1:5500
```

**Option 3 — Python HTTP Server:**
```bash
cd LearnSphere
python -m http.server 5500
# Open http://localhost:5500
```

---

## 🌐 Deploying to GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select `main` branch → `/ (root)`
4. Click **Save**
5. Your site will be live at `https://<your-username>.github.io/LearnSphere/`

---

## 📸 Highlights

### The Three-Pillar Product Framework

```
Intelligent Discovery   Frictionless Engagement   Seamless Architecture
────────────────────   ─────────────────────────  ─────────────────────
Live Search             Data-driven Course Cards   Responsive Tri-Screen
Category Filtering      Expandable Accordions      Scroll Spy Navigation
Dynamic Sorting         Enrollment Modal           Integrated Sections
                        Persistent Save Feature
```

### The Persistence Loop

```
User clicks ♥  →  Vanilla JS serializes to localStorage
                              ↓
     DOM auto-populates     ←  Page refresh reads localStorage
     Saved Courses section
```

### Enrollment Flow (Zero-to-Enrolled)

```
[Enroll Now] → Input Fields → Regex Validation → ✅ Success → Auto-close (3s)
```

---

## 📊 Platform Stats

| Metric | Value |
|---|---|
| Active Learners | 1.5 Million+ |
| Accredited Partners | 250+ |
| Courses Available | 12 |
| Average Rating | 4.8 ★ |
| External Dependencies | Zero |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with ❤️ using only fundamental web technologies — no frameworks, no build tools, no bloat.*
