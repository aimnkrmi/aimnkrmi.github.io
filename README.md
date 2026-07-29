<p align="center">
  <img src="assets/images/readme-banner.svg" alt="Aiman Karami — Applied Mathematics × Backend Systems" width="100%">
</p>

<h1 align="center">Personal Portfolio — aimnkrmi.github.io</h1>

<p align="center"><em>A static, dependency-free portfolio built from scratch with plain HTML, CSS, and JavaScript.</em></p>

<p align="center">
  <a href="https://aimnkrmi.github.io"><img alt="Live site" src="https://img.shields.io/badge/live-aimnkrmi.github.io-8B5CF6?style=for-the-badge&logo=githubpages&logoColor=white"></a>
  <img alt="Built with vanilla JS" src="https://img.shields.io/badge/built%20with-vanilla%20JS-38BDF8?style=for-the-badge">
  <img alt="No build step" src="https://img.shields.io/badge/build%20step-none-72E2AE?style=for-the-badge">
</p>

---

## ✨ Highlights

- **Zero frameworks, zero build tools** — just `index.html`, `styles.css`, and `script.js`. Open the file, and it runs.
- **Fully local** — fonts, icons, and documents are self-hosted under `assets/`. No CDNs, no external requests.
- **Motion in vanilla JS** — custom cursor, scroll reveals, animated counters, a typing effect, tilt cards, an interactive skill constellation, and an in-page terminal.
- **Mathematics theme** — a scrolling equation band, background math glyphs, and terminal commands like `euler`, `fib`, and `pi`.
- **Performance-minded** — GPU-friendly transforms, `content-visibility` on offscreen sections, and an automatic low-power mode for weaker devices.
- **Mobile-first & accessible** — responsive from 320px up, semantic HTML, keyboard navigation, and full `prefers-reduced-motion` support.
- A few **easter eggs** — try typing `robin`, the Konami code, or double-clicking the logo. 🌸

## 🚀 Run it locally

No install, no build. Clone and open:

```bash
git clone https://github.com/aimnkrmi/aimnkrmi.github.io.git
cd aimnkrmi.github.io
# open index.html directly, or serve it:
python -m http.server 5500   # http://localhost:5500
```

## 🌐 Deployment

This repository is named `aimnkrmi.github.io`, so GitHub Pages serves it automatically
at **https://aimnkrmi.github.io/** from the default branch. Just push to `main`:

```bash
git add .
git commit -m "Update site"
git push
```

## 📁 Project structure

```txt
.
├── index.html        # markup — all sections
├── styles.css        # mobile-first styles, animations, responsive layers
├── script.js         # vanilla JS: preloader, cursor, reveals, terminal, skills…
└── assets/
    ├── fonts/         # Inter, Space Grotesk, JetBrains Mono (self-hosted woff2)
    ├── docs/          # résumé + academic PDFs
    ├── images/        # banner, og placeholders
    └── icons/ videos/ audio/ css/ js/
```

## 🙏 Credits

- Fonts: [Inter](https://github.com/rsms/inter), [Space Grotesk](https://github.com/floriankarsten/space-grotesk), and [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono) — all under the SIL Open Font License.
- Everything else is hand-written. No template, no page builder.

## 📫 Connect

- 🌐 Portfolio: [karami.my](https://karami.my)
- 💼 LinkedIn: [aimankarami](https://www.linkedin.com/in/aimankarami)
- ✉️ Email: aimankarami27@gmail.com
