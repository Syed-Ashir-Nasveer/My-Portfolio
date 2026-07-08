<div align="center">

# 🛡️ Ashir — Cyber Portfolio

### Offensive Security Portfolio with Terminal Boot Intro & Live 3D Recon Network

<a href="https://syed-ashir-nasveer.github.io/My-Portfolio/" target="_blank">
  <img src="https://img.shields.io/badge/🌐_Live_Demo-34D399?style=for-the-badge&logoColor=black" alt="Live Demo" height="35">
</a>
<a href="https://github.com/Syed-Ashir-Nasveer/ashir-cyber-portfolio" target="_blank">
  <img src="https://img.shields.io/badge/📂_View_Repo-8B96A8?style=for-the-badge&logoColor=black" alt="Repo" height="35">
</a>

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Made with](https://img.shields.io/badge/Made_with-HTML%2FCSS%2FJS-34D399)](#)
[![Zero Dependencies](https://img.shields.io/badge/Build_Step-None-8B96A8)](#)

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎨 Design & UI
- Terminal boot-sequence intro (skippable)
- Restrained cyber aesthetic (`#34D399`, `#0B0D0F`)
- Live 3D recon-network hero (Three.js)
- Ambient matrix rain background
- Autonomous wandering hacker character
- Custom crosshair cursor
- Scroll-triggered reveal animations
- Fully responsive design

</td>
<td width="50%">

### 🛠️ Technical Stack
- Pure Vanilla JavaScript
- Three.js (CDN, r128)
- CSS Grid & Flexbox
- Custom CSS animations
- Intersection Observer API
- Single-file build — zero dependencies

</td>
</tr>
</table>

### 📋 Complete Sections
**Hero** • **About** • **Skills** • **Projects** • **Experience** • **Contact**

---

## 🚀 Quick Start

No build step, no install — it's a single HTML file.

```bash
# Clone repository
git clone https://github.com/Syed-Ashir-Nasveer/ashir-cyber-portfolio.git
cd ashir-cyber-portfolio

# Option 1: Open directly
start index.html          # Windows
open index.html           # macOS
xdg-open index.html       # Linux

# Option 2: Use a local server (recommended for the 3D canvas + fonts)
python -m http.server 8000
# Then visit: http://localhost:8000
```

> **Requirements:** Modern browser (Chrome, Firefox, Safari, Edge) with WebGL support

---

## 📁 Project Structure

```
ashir-cyber-portfolio/
│
├── index.html          # Everything — markup, styles, and scripts in one file
├── README.md           # Project documentation
└── LICENSE             # MIT License
```

Single-file by design: no bundler, no `node_modules`, no build pipeline. Open it and it runs.

---

## 🎨 Customization

### Colors
All theme colors are CSS custom properties at the top of `index.html`:

```css
:root{
  --bg: #0b0d0f;      /* Background */
  --amber: #34d399;    /* Primary accent — muted emerald */
  --cyan: #8b96a8;      /* Secondary — neutral cool gray */
  --text: #e8eaed;      /* Body text */
  --muted: #6b7280;     /* Secondary text */
}
```

### Content
| Section | Where to Edit |
|---|---|
| Name, role, tagline | `.hero` block |
| Boot sequence lines | `#bootScreen` block |
| About / stats | `#about` section |
| Skills & proficiency | `#skills` section (`data-w` = bar %) |
| Projects | `#projects` section |
| Timeline | `#experience` section |
| Contact links | `#contact` section |

### Behavior
| File Region | Controls |
|---|---|
| `<script>` — boot screen | Boot intro timing / skip logic |
| `<script>` — matrix rain | Falling character density & speed |
| `<script>` — hacker NPC | Wandering character movement & status lines |
| `<script>` — 3D hero network | Node count, connection distance, rotation |

---

## 🌐 Compatibility

**Browsers:** Chrome, Firefox, Safari, Edge (latest) • **Mobile:** Responsive down to ~360px (cursor & NPC effects disabled on touch devices for performance)

---

## ⚡ Performance

✅ Intersection Observer for scroll reveals • ✅ Canvas-based rain (no DOM thrash) • ✅ Single WebGL context • ✅ No external framework overhead

---

## 🛠️ Built With

**HTML5** • **CSS3** (Grid, Flexbox, Custom Properties, Keyframes) • **Vanilla JavaScript** • **Three.js** (3D network)

---

## 📝 Future Enhancements

- [ ] Blog / write-up section for CTF & bug bounty reports
- [ ] Project detail pages with case studies
- [ ] Contact form backend integration
- [ ] Certifications section
- [ ] Dark/light theme toggle
- [ ] PWA support

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Syed Ashir** — BS Cybersecurity, University of Wah • President, Nexus Cyber Club • Red Team / Bug Bounty (Bugcrowd)

🌐 **Live:** [syed-ashir-nasveer.github.io/My-Portfolio](https://syed-ashir-nasveer.github.io/My-Portfolio/)

[GitHub](https://github.com/Syed-Ashir-Nasveer) • [LinkedIn](https://www.linkedin.com/in/syed-ashir-209b39351/) • [Bugcrowd](https://bugcrowd.com/0x007b) • [Email](mailto:ashirsec@gmail.com)

## 💬 Support

Give it a ⭐️ if you like it. For issues, ideas, or a pull request — open one on GitHub.

---

<div align="center">

**Built by [Syed Ashir](https://github.com/Syed-Ashir-Nasveer)**

</div>
