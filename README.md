# dev-portfolio-templates

** production-quality portfolio templates** for developers, designers, and other tech professionals. Each template is a single self-contained HTML file — no build tools, no frameworks, no dependencies to install. Download and use immediately.

> Built by [@baysah](https://github.com/Statisticsage) · MIT License · Free forever

---

## Templates

| # | Name | Style | Best for | Live Preview |
|---|------|-------|----------|--------------|
| 1 | **Orbital** | Dark space, animated particles | Developers / Engineers | [View →](https://baysah.github.io/dev-portfolio-templates/templates/orbital/) |
| 2 | **Editorial** | Off-white serif, magazine layout | Product Designers | [View →](https://baysah.github.io/dev-portfolio-templates/templates/editorial/) |
| 3 | **Terminal** | Monospace CLI aesthetic | Systems / Backend Engineers | [View →](https://baysah.github.io/dev-portfolio-templates/templates/terminal/) |
| 4 | **Studio** | Full-bleed, agency-grade | Freelancers / Creative Directors | [View →](https://baysah.github.io/dev-portfolio-templates/templates/studio/) |
| 5 | **Precision** | Swiss grid, pure typography | EMs / PMs / Senior Leaders | [View →](https://baysah.github.io/dev-portfolio-templates/templates/precision/) |

---

## How to use

**Option A — Download directly**

1. Go to the template folder you want (e.g. `templates/editorial/`)
2. Open `index.html`
3. Click the **Raw** button
4. Right-click → Save As → `index.html`
5. Open in your editor and replace the placeholder content with your own

**Option B — Clone the whole repo**

```bash
git clone https://github.com/baysah/dev-portfolio-templates.git
cd dev-portfolio-templates/templates/editorial
# open index.html in your editor
```

**Option C — Use as GitHub Pages**

1. Fork this repo
2. Go to your fork → Settings → Pages
3. Set source to `main` branch → `/templates/<name>` folder
4. Your portfolio is live at `https://yourusername.github.io/dev-portfolio-templates/templates/<name>/`

---

## What's inside each template

- **Single HTML file** — everything embedded (CSS + JS). No npm, no build step.
- **Google Fonts** — loaded via CDN, no local files needed.
- **Zero dependencies** — works offline after first load.
- **Mobile responsive** — tested down to 375px.
- **Production-level code** — clean, commented, easy to customize.

---

## Customizing

Every template uses CSS custom properties (variables) at the top of the `<style>` block. To change colors, fonts, or spacing — edit those variables first before touching anything else.

```css
:root {
  --accent: #4f8ef7;   /* ← change this to your color */
  --bg: #050b18;
  --font: 'Space Grotesk', sans-serif;
}
```

To swap your name, title, and links — search for placeholder text like `Alex Rivera`, `maya@example.com`, or `Your Name` and replace throughout.

---

## Templates in detail

### 1. Orbital — Developer / Engineer
Dark space-themed portfolio with an animated star field canvas, orbit ring graphic, scroll reveals, and a custom cursor. Signature element: the canvas star field — everything else is calm. For developers who want presence without being flashy.

### 2. Editorial — Product Designer
Off-white magazine-layout portfolio built around typographic hierarchy. Signature element: the cursor expands into a reading circle when hovering text. Project work presented as editorial rows, not cards. For designers who let craft speak.

### 3. Terminal — Systems / Backend Engineer
Pure monospace, CLI-aesthetic portfolio. Looks like a terminal session — nav has a shell prompt, projects are displayed like git repos, skills have animated progress bars that fill on scroll. No color except green on black. For engineers who mean business.

### 4. Studio — Freelancer / Creative Director
Full-bleed case study layout with a page loader, magnetic cursor that appears over project images, and large typographic hero. Project work presented as full-width case studies with image + details. For freelancers who want to look like a studio.

### 5. Precision — Engineering Manager / PM / Senior Leader
Swiss-grid layout built entirely on a 12-column grid. No decorations — pure typographic hierarchy and information density. Work presented as a scannable table. For senior professionals who want to be taken seriously immediately.

---

## Roadmap

- [ ] Template 6 — **Aurora** (gradient mesh, glassmorphism, for UI/UX designers)
- [ ] Template 7 — **Minimal** (single-page, ultra-clean, for students / new grads)
- [ ] Template 8 — **Data** (chart-heavy, for data scientists / analysts)
- [ ] Dark mode variants for Editorial and Precision
- [ ] Screenshot previews for all templates

---

## Contributing

Found a bug? Have a suggestion? PRs and issues are welcome.

If you use one of these templates, I'd love to see it — drop the link in [Discussions](https://github.com/baysah/dev-portfolio-templates/discussions) or tag me on Twitter.

---

## License

MIT — free to use, modify, and distribute for personal and commercial projects. No attribution required (though appreciated).

---

*If this helped you, consider giving the repo a ⭐ — it helps others find it.*
