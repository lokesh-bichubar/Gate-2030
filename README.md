<div align="center">

# 🧱 lokesh Gate Tracker-2030

### Every single GATE CS topic. One checkbox at a time. 💥

![GATE](https://img.shields.io/badge/GATE-CS_2030-ff6b6b?style=for-the-badge&logoColor=white)
![Topics](https://img.shields.io/badge/Checkboxes-96-ffd93d?style=for-the-badge&logoColor=black)
![Sections](https://img.shields.io/badge/Sections-10-4d96ff?style=for-the-badge)
![Build](https://img.shields.io/badge/Build-Single_HTML_File-6bcb77?style=for-the-badge)
![Dependencies](https://img.shields.io/badge/Dependencies-Zero_🔥-ff9f45?style=for-the-badge)
![Style](https://img.shields.io/badge/Style-Neo--Brutalism-b388ff?style=for-the-badge)

A **neo-brutalist checklist website** that breaks the entire GATE Computer Science
syllabus into **96 trackable checkboxes across 10 sections** — with progress that
saves itself, dark mode, search, and confetti when you finally conquer it all. 👑

<!-- 📸 TIP: drop a screenshot.png in this folder and uncomment the line below -->
<!-- ![Screenshot](screenshot.png) -->

</div>

---

## ✨ Features

- ✅ **96 topic checkboxes** covering every line of the official GATE CS syllabus
- 💾 **Persistent progress** — auto-saved to `localStorage`, survives refreshes & restarts
- 📊 **Dashboard** — big % counter, striped progress bar, topics/sections stats, motivational status chips (*"Halfway hero 🔥"*)
- 📌 **Sticky top progress strip** that follows you while scrolling
- 🏆 **"MASTERED" stamp** slams onto any section card you complete
- 🔍 **Live search** — filter topics instantly (try `Bayes` or `pipelining`)
- 🌙 **Dark mode** — fully themed, still brutal
- 🎉 **Confetti explosion** at 100% completion
- 🔗 **Quick-jump nav chips** to any of the 10 sections
- ⟲ **Two-step reset** so you never wipe progress by accident
- 📱 **Fully responsive** — desktop grid → mobile stack
- ⚡ **Zero dependencies** — one self-contained HTML file, no build step, no backend

## 📚 Syllabus Coverage

| # | Section | Topics | Color |
|---|---------|:------:|-------|
| 01 | 🧮 Engineering Mathematics | 18 | `#ff6b6b` |
| 02 | ⚡ Digital Logic | 6 | `#ffd93d` |
| 03 | 🖥️ Computer Organization & Architecture | 8 | `#4d96ff` |
| 04 | 💻 Programming & Data Structures | 8 | `#6bcb77` |
| 05 | ⚙️ Algorithms | 10 | `#ff9f45` |
| 06 | ∞ Theory of Computation | 6 | `#b388ff` |
| 07 | 🔧 Compiler Design | 9 | `#2ec4b6` |
| 08 | 🗂️ Operating System | 9 | `#ff85a1` |
| 09 | 🗄️ Databases | 9 | `#a3e635` |
| 10 | 🌐 Computer Networks | 13 | `#f15bb5` |
| | **Total** | **96** | 🌈 |

Sub-groups included where the syllabus has them — Discrete Maths / Linear Algebra /
Calculus / Probability in Section 1, design techniques & graph algorithms in Section 5,
and OSI-layer-wise grouping in Section 10.

## 🛠️ Tech Stack

| Layer | Tech |
|-------|------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, `color-mix()`, keyframe animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | [Archivo Black](https://fonts.google.com/specimen/Archivo+Black) + [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) via Google Fonts |
| Storage | Browser `localStorage` (with graceful in-memory fallback) |

## 🚀 Run Locally

**Option 1 — just open it:**

```bash
# double-click index.html, or:
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

**Option 2 — serve it (recommended):**

```bash
git clone https://github.com/<your-username>/lokesh-gate-tracker-2030.git
cd lokesh-gate-tracker-2030
python3 -m http.server 8000
# → http://localhost:8000
```

## 🌐 Deploy on GitHub Pages

1. Push this repo to GitHub (commands below 👇)
2. Repo → **Settings** → **Pages**
3. Source: **Deploy from a branch** → `main` / `/ (root)` → **Save**
4. Your tracker goes live at `https://<your-username>.github.io/lokesh-gate-tracker-2030/`

```bash
git init
git add .
git commit -m "feat: lokesh Gate Tracker-2030 — neo-brutalist GATE CS checklist"
git branch -M main
git remote add origin https://github.com/<your-username>/lokesh-gate-tracker-2030.git
git push -u origin main
```

## 🎨 Design Notes — Neo-Brutalism

- 🧱 Chunky **3px solid black borders** on everything
- 🕳️ **Hard offset shadows** (`6px 6px 0`) — no blurs, no mercy
- 🟡 High-contrast palette: cream canvas, dotted texture, 10 punchy section colors
- 📐 **Tilted stickers & stamps** for that raw, hand-pinned feel
- 🔤 Archivo Black headlines, lowercase on purpose
- 👆 Press-down micro-interactions on every button and checkbox row

## 📁 Project Structure

```
lokesh-gate-tracker-2030/
├── index.html    # the entire app — markup, styles & logic in one file
└── README.md     # you are here
```

## 📄 Syllabus Source

Topics extracted from the official **GATE Computer Science & Information Technology**
syllabus PDF (GATE 2027, IIT Madras — Organizing Institute).

---

<div align="center">

**Built for Lokesh. No excuses, only checkboxes.** 🧱🔥

Target: **GATE 2030** 🎯

</div>
