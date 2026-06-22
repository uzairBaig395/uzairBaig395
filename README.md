# 🚀 Mirza Uzair Baig — Portfolio

> Frontend Developer | Self-Taught Builder | Space Science Explorer

A single-page, fully responsive developer portfolio built with vanilla JavaScript, Tailwind CSS, and Firebase-ready architecture — featuring a live light/dark theme switcher, an animated logo intro, a command palette, and real-time GitHub stats.

<p align="center">
  <img src="./preview.gif" alt="Portfolio loading screen and homepage preview" width="800">
  <br>
  <em>👆 Add a screen-recording GIF here (see "Adding the Preview GIF" below)</em>
</p>

<p align="center">
  <a href="https://uzairBaig395.github.io/portfolio/"><strong>🔗 Live Demo</strong></a>
</p>

---

## ✨ Highlights

| | |
|---|---|
| 🎬 **Animated Logo Intro** | A 5-second "U" logo reveal with a spinning progress ring plays on every load |
| 🌓 **Theme Toggle** | Switch between Dark (black + gray) and Light (gray + white) — preference saved across visits |
| ⌘ **Command Palette** | Press `Ctrl/Cmd + K` to jump to any section instantly |
| 🌐 **Live GitHub Stats** | Pulls real repo, follower & following counts straight from the GitHub API |
| ✨ **Interactive Particle Network** | A canvas constellation that reacts to mouse movement |
| 🎯 **3D Tilt + Shine Cards** | Project and skill cards tilt and catch light on hover |
| 🧭 **Scroll-Spy Navigation** | Nav links and a side dot-nav highlight the active section automatically |
| 📋 **One-Click Email Copy** | Copies your email to clipboard with a toast confirmation |
| 🎉 **Confetti on Submit** | A celebratory burst when the contact form is submitted successfully |
| ♿ **Accessible & Responsive** | Respects `prefers-reduced-motion`, works on touch devices, mobile-first |

---

## 🛠️ Tech Stack

- **HTML5 / CSS3** — semantic structure, custom properties, animations
- **Tailwind CSS** (via CDN, JIT) — utility-first styling
- **Vanilla JavaScript** — no frameworks, no build step
- **Firebase / Firestore** — used in linked sub-projects (Todo App, etc.)
- **Font Awesome 6** — iconography
- **Google Fonts** — `Syne`, `DM Sans`, `Fira Code`
- **GitHub REST API** — live profile stats

---

## 📂 Project Structure

```
portfolio/
├── index.html          # Entire site — markup, styles, and scripts
├── Images/
│   └── uzairbaig.jpg.jpeg
└── README.md
```

This is intentionally a **single-file portfolio** — everything (HTML, CSS, JS) lives in `index.html` for maximum portability. No build tools, no `npm install`, no bundler. Clone it and open it.

---

## 🚀 Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/uzairBaig395/portfolio.git
cd portfolio

# 2. Open it — that's it!
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or just double-click `index.html`. No server required (though a local server like `npx serve` avoids any `file://` CORS quirks with the GitHub stats fetch).

### Deploying for free
- **GitHub Pages**: Settings → Pages → Deploy from branch → `main` → `/ (root)`
- **Netlify / Vercel**: drag-and-drop the folder, zero config needed

---

## 🎨 Customizing

| Want to change... | Edit this... |
|---|---|
| Name, bio, taglines | Hero & About sections in `index.html` |
| Color accents | `tailwind.config` block (`sky`, `violet` colors) near the top |
| Light theme palette | The `[data-theme="light"]` CSS block |
| Projects | The `#projects` section — duplicate a `.portfolio-item` card |
| GitHub stats username | Find `api.github.com/users/uzairBaig395` in the `<script>` and swap the username |
| Resume / CV | Add a file named `Mirza-Uzair-Baig-CV.pdf` next to `index.html` |

---

## 🎬 Adding the Preview GIF

To make this README pop on GitHub:
1. Record a short screen capture of the site loading (the "U" logo intro is great for this) using [ScreenToGif](https://www.screentogif.com/), [Kap](https://getkap.co/) (Mac), or `Cmd/Win + Shift + R`.
2. Trim it to ~8–10 seconds and export as `.gif`.
3. Save it in the repo root as `preview.gif`.
4. It will automatically appear at the top of this README.

---

## 📬 Contact

- **Email:** [mirzauzair448@gmail.com](mailto:mirzauzair448@gmail.com)
- **GitHub:** [@uzairBaig395](https://github.com/uzairBaig395)
- **LinkedIn:** [Mirza Uzair Baig](https://www.linkedin.com/in/uzair-baig-1699563ab/)
- **X / Twitter:** [@Uzairbaig3x](https://x.com/Uzairbaig3x)

---

## 📄 License

This project is open for reference and learning. If you fork or reuse the design, a credit/link back is appreciated. 🙌

<p align="center">Made with ☕ and curiosity in Karachi, Pakistan.</p>
