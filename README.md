<div align="center">

<br />

```
████████╗███████╗ ██████╗██╗  ██╗    ██╗  ██╗ ██████╗ ██████╗ ██╗███████╗ ██████╗ ███╗   ██╗
╚══██╔══╝██╔════╝██╔════╝██║  ██║    ██║  ██║██╔═══██╗██╔══██╗██║╚══███╔╝██╔═══██╗████╗  ██║
   ██║   █████╗  ██║     ███████║    ███████║██║   ██║██████╔╝██║  ███╔╝ ██║   ██║██╔██╗ ██║
   ██║   ██╔══╝  ██║     ██╔══██║    ██╔══██║██║   ██║██╔══██╗██║ ███╔╝  ██║   ██║██║╚██╗██║
   ██║   ███████╗╚██████╗██║  ██║    ██║  ██║╚██████╔╝██║  ██║██║███████╗╚██████╔╝██║ ╚████║
   ╚═╝   ╚══════╝ ╚═════╝╚═╝  ╚═╝    ╚═╝  ╚═╝ ╚═════╝ ╚═╝  ╚═╝╚═╝╚══════╝ ╚═════╝ ╚═╝  ╚═══╝
```

**🔭 Future Technology Intelligence Platform**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)

<br />

A single-file, zero-dependency intelligence dashboard covering **12 technology domains** with real-time market forecasts, probability-based milestone predictions, and interactive data visualisations.

<br />

[🚀 Live Demo](#) · [🐛 Report a Bug](issues/new?template=bug_report.md) · [✨ Request a Feature](issues/new?template=feature_request.md)

<br />

</div>

---

## 📋 Table of Contents

- [🌟 Overview](#-overview)
- [✨ Features](#-features)
- [⚙️ Tech Stack](#️-tech-stack)
- [🚀 Getting Started](#-getting-started)
- [📁 Project Structure](#-project-structure)
- [🗂️ Data Model](#️-data-model)
- [🗺️ Pages & Navigation](#️-pages--navigation)
- [🎨 Customisation](#-customisation)
- [🛣️ Roadmap](#️-roadmap)
- [🤝 Contributing](#-contributing)
- [👩‍💻 Author](#-author)
- [📜 License](#-license)

---

## 🌟 Overview

TechHorizon is a **client-side intelligence platform** built as a single HTML file. It provides structured market analysis, probability forecasts, and competitive landscape data across the most in-demand technology fields — from Artificial Intelligence and Quantum Computing to Clean Energy and Biotechnology.

The platform is designed for:

- 👩‍💻 **Developers & engineers** researching which domains to upskill in
- 📊 **Analysts & researchers** tracking technology market trajectories
- 💼 **Investors & founders** exploring sector growth and key players
- 🎓 **Educators** presenting technology landscape data visually

> 💡 No backend. No build step. No dependencies to install. Download one file and open it.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🗂️ **12 Technology Domains** | Comprehensive coverage from AI/ML to Quantum, Biotech, and Clean Energy |
| 📊 **Interactive Dashboard** | Market projections, demand distribution, growth rates, and maturity matrix |
| 🔮 **Probability Forecasts** | Data-driven confidence scores for major technological milestones through 2030 |
| 🔍 **Field Detail Pages** | Per-domain deep-dives with growth charts, skills, tools, and future outlook |
| 📡 **Live Ticker** | Real-time styled market signals across all tracked sectors |
| 🔢 **Animated Counters** | Platform statistics rendered with smooth count-up animations |
| 📱 **Fully Responsive** | Optimised for desktop, tablet, and mobile viewports |
| ⚡ **Zero Dependencies** | Pure HTML/CSS/JS — no framework, no build tooling, no npm |

---

## ⚙️ Tech Stack

| 🔧 Layer | 💻 Technology | 📌 Purpose |
|---|---|---|
| 🏗️ Markup | HTML5 | Structure and semantic layout |
| 🎨 Styling | CSS3 (custom properties, grid, flexbox) | Theming, layout, animations |
| ⚙️ Logic | Vanilla JavaScript (ES6+) | Navigation, data rendering, counters |
| 📈 Charts | [Chart.js 4.4](https://www.chartjs.org/) | Line, bar, doughnut, and bubble charts |
| 🎯 Icons | [Font Awesome 6.5](https://fontawesome.com/) | UI iconography |
| 🖋️ Typography | Playfair Display + Instrument Sans + JetBrains Mono | Display, body, and monospace text |

---

## 🚀 Getting Started

### ⚡ Option 1 — Open directly

```bash
# 📥 Clone the repository
git clone https://github.com/Muqadas-g/techhorizon.git

# 🌐 Open in your browser — no server required
open techhorizon.html
```

### 🖥️ Option 2 — Serve locally (recommended for development)

```bash
# 🐍 Using Python
python3 -m http.server 8080

# 📦 Using Node.js (npx)
npx serve .

# 💻 Using VS Code
# Install the "Live Server" extension, then right-click → Open with Live Server
```

Then visit `http://localhost:8080` in your browser.

### ☁️ Option 3 — Deploy as a static site

TechHorizon is a single static file and deploys to any static hosting provider:

```bash
# 🔺 Vercel
vercel --prod

# 🟩 Netlify (drag & drop)
# Upload techhorizon.html to https://app.netlify.com/drop

# 🐙 GitHub Pages
# Push to a repo → Settings → Pages → deploy from root or /docs
```

---

## 📁 Project Structure

```
techhorizon/
│
├── 📄 techhorizon.html        # Entire application (HTML + CSS + JS, self-contained)
├── 📝 README.md               # This file
├── 📜 LICENSE                 # MIT License
└── 📂 .github/
    ├── 📂 ISSUE_TEMPLATE/
    │   ├── 🐛 bug_report.md
    │   └── ✨ feature_request.md
    └── 🤝 CONTRIBUTING.md
```

All application code lives in `techhorizon.html`, structured internally as:

```
📄 techhorizon.html
│
├── 🏷️  <head>
│   ├── 🖋️  Google Fonts (Playfair Display, Instrument Sans, JetBrains Mono)
│   ├── 🎯  Font Awesome CDN
│   ├── 📈  Chart.js CDN
│   └── 🎨  <style> — CSS custom properties, layout, components
│
├── 🏗️  <body>
│   ├── 🧭  <nav>               Navigation bar
│   ├── 📡  .status-bar         Live ticker strip
│   ├── 🏠  #page-home          Hero, feature strip, top fields, predictions table
│   ├── 🗂️  #page-fields        All 12 technology field cards
│   ├── 📊  #page-dashboard     Four interactive Chart.js visualisations
│   ├── 🔢  #page-stats         Animated platform statistics
│   ├── 🔍  #page-detail        Dynamic single-field detail view
│   └── 🦶  <footer>
│
└── ⚙️  <script>
    ├── 📦  FIELDS              Data object — all 12 domains
    ├── 🃏  fieldCardHTML()     Field card renderer
    ├── 🔍  showDetail()        Detail page population
    ├── 🧭  nav()               Client-side page router
    ├── 📈  initHeroChart()     Hero area line chart
    ├── 📊  initDashCharts()    Dashboard charts (lazy-loaded)
    └── 🔢  runCounters()       Animated stat counters
```

---

## 🗂️ Data Model

Each technology field follows this schema inside the `FIELDS` object:

```javascript
'field-id': {
  title:       string,           // 🏷️  Display name
  icon:        string,           // 🎨  Emoji icon
  badge:       'growth' | 'emerging' | 'mature',
  desc:        string,           // 📝  Short description (shown in cards)
  growth:      number,           // 📈  Annual growth rate (%)
  market:      number,           // 💰  Current market size ($B)
  demand:      number,           // 🔥  Talent demand index (0–100)
  players:     string[],         // 🏢  Key companies / organisations
  skills:      string[],         // 🛠️  Top skills in this domain
  tools:       string[],         // 🔧  Popular tooling / frameworks
  predictions: [                 // 🔮  Milestone forecasts
    {
      year:    number,
      event:   string,
      prob:    number            // 📊  Probability (0–100)
    }
  ],
  future:      string            // 🌐  Long-form outlook paragraph
}
```

> ✅ To add or update a field, edit the `FIELDS` constant at the top of the `<script>` block. Cards, charts, and detail pages are all rendered dynamically — no other changes required.

---

## 🗺️ Pages & Navigation

TechHorizon uses a lightweight client-side router. All navigation calls `nav(pageName)` or `showDetail(fieldId)`.

| 🔗 Page | 🆔 ID | 📋 Description |
|---|---|---|
| 🏠 Overview | `home` | Hero, feature strip, top 6 fields, predictions table |
| 🗂️ Fields | `fields` | All 12 technology field cards |
| 📊 Dashboard | `dashboard` | Four interactive Chart.js visualisations (lazy-loaded) |
| 🔢 Statistics | `stats` | Animated platform metrics |
| 🔍 Field Detail | `detail` | Dynamically populated from `FIELDS` data |

---

## 🎨 Customisation

### 🖌️ Changing the colour theme

All colours are defined as CSS custom properties in `:root`:

```css
:root {
  --void:    #080B10;    /* 🌑 Page background        */
  --deep:    #0E1219;    /* 🌒 Secondary background   */
  --surface: #141920;    /* 🌓 Card background        */
  --azure:   #3B7CFF;    /* 🔵 Primary accent         */
  --emerald: #10C07A;    /* 🟢 Positive / growth      */
  --topaz:   #FFB020;    /* 🟡 Warning / mature       */
  --rose:    #FF4B6E;    /* 🔴 Negative / alert       */
}
```

### ➕ Adding a new technology field

1. 📝 Add an entry to the `FIELDS` object following the [data model](#️-data-model) above
2. 🌟 Optionally include its ID in `HOME_FIELDS` to feature it on the overview page (max 6)
3. ✅ Done — the card and detail page are generated automatically

### 🖋️ Swapping fonts

Replace the Google Fonts `<link>` in `<head>` and update the three CSS variables:

```css
--serif: 'Playfair Display', Georgia, serif;
--sans:  'Instrument Sans', system-ui, sans-serif;
--mono:  'JetBrains Mono', 'Courier New', monospace;
```

---

## 🛣️ Roadmap

- [ ] 🔍 Search and filter across all fields
- [ ] ↕️ Sortable fields grid (by growth, market size, demand)
- [ ] 📥 Export predictions table to CSV / PDF
- [ ] ☀️ Light theme toggle
- [ ] 🔖 LocalStorage bookmarking for saved fields
- [ ] ♿ Accessibility audit and ARIA improvements
- [ ] 🚀 Additional domains: Space Tech, AR/VR, Autonomous Vehicles
- [ ] 🌍 Internationalisation (i18n) support

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. 🍴 Fork the repository
2. 🌿 Create a feature branch: `git checkout -b feature/your-feature-name`
3. 💾 Commit your changes: `git commit -m 'Add: brief description'`
4. 📤 Push to the branch: `git push origin feature/your-feature-name`
5. 🔁 Open a Pull Request

> 💡 For significant changes, please open an issue first to discuss the proposed approach. Data additions (new fields, updated forecasts) should include cited sources where possible.

---

## 👩‍💻 Author

<div align="center">

### Muqaddas Imtiaz

🎓 BS Data Science · QUEST Nawabshah, Sindh, Pakistan  
💻 Web Developer · Data Science Student

| 🔗 Platform | 📌 Link |
|---|---|
| 🐙 GitHub | [@Muqadas-g](https://github.com/Muqadas-g) |
| 💼 LinkedIn | [Muqaddas Imtiaz](https://www.linkedin.com/in/muqaddas-imtiaz-5635b0301) |
| 📓 Kaggle | [muqaddasimtiaz](https://www.kaggle.com/muqaddasimtiaz) |
| 🛒 Fiverr | [Hire Me](https://www.fiverr.com/pe/pdlxXgp) |
| 📧 Email | muqaddasjutt57@gmail.com |

</div>

---

## 📜 License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for details.

---

<div align="center">

🌟 *"Code. Create. Innovate."* 🌟

Built with ❤️ by [Muqaddas Imtiaz](https://github.com/Muqadas-g) · Powered by open web standards

<br />

If you find this useful, please consider leaving a ⭐ — it means a lot!

</div>
