# Baysahtech Portfolio Templates

**8 free, production-quality portfolio templates** for developers, designers, and tech professionals — built by **BaysaTech**.

Each template is a single HTML file. No npm. No build step. No frameworks. Download, edit your name, deploy in minutes.

> Built by [Baysah](https://github.com/Statisticsage) · MIT License · Free forever

---

## Live Previews

| # | Template | Style | Best For | Preview |
|---|----------|-------|----------|---------|
| 1 | **Orbital** | Dark space, particle animation | Developers / Engineers | [Live Preview →](https://statisticsage.github.io/Baysahtech-portfolio-templates/orbital.html) |
| 2 | **Editorial** | Off-white serif, magazine layout | Product Designers | [Live Preview →](https://statisticsage.github.io/Baysahtech-portfolio-templates/editorial.html) |
| 3 | **Terminal** | Monospace CLI aesthetic | Systems / Backend Engineers | [Live Preview →](https://statisticsage.github.io/Baysahtech-portfolio-templates/terminal.html) |
| 4 | **Studio** | Full-bleed, agency-grade | Freelancers / Creative Directors | [Live Preview →](https://statisticsage.github.io/Baysahtech-portfolio-templates/studio.html) |
| 5 | **Precision** | Swiss grid, pure typography | EMs / PMs / Senior Leaders | [Live Preview →](https://statisticsage.github.io/Baysahtech-portfolio-templates/precision.html) |
| 6 | **Freelance Platform** | Deep navy, conversion-focused | Freelancers / Contractors | [Live Preview →](https://statisticsage.github.io/Baysahtech-portfolio-templates/freelance_platform_hero_ui.html) |
| 7 | **Aura** | Dark, avatar + orbiting icons | UI/UX Designers / Developers | [Live Preview →](https://statisticsage.github.io/Baysahtech-portfolio-templates/aura.html) |
| 8 | **Cinematic** | Full-viewport person cutout, bold Bebas | Creative Devs / Designers | [Live Preview →](https://statisticsage.github.io/Baysahtech-portfolio-templates/cinematic.html) |

---

## Screenshots

| Orbital | Editorial | Terminal |
|---------|-----------|----------|
| ![Orbital](previews/orbital.png) | ![Editorial](previews/editorial.png) | ![Terminal](previews/terminal.png) |

| Studio | Precision | Freelance |
|--------|-----------|-----------|
| ![Studio](previews/studio.png) | ![Precision](previews/precision.png) | ![Freelance](previews/freelance.png) |

| Aura | Cinematic |
|------|-----------|
| ![Aura](previews/aura.png) | ![Cinematic](previews/cinematic.png) |

---

## How to Use

**Option A — Download one file**
1. Click any Live Preview link above
2. Go back to the repo and click the `.html` file
3. Click the **Raw** button
4. Right-click → **Save As** → save as `index.html`
5. Open in your editor, replace placeholder text with your info
6. Deploy to GitHub Pages, Vercel, or Netlify — all free

**Option B — Clone the whole repo**
```bash
git clone https://github.com/Statisticsage/Baysahtech-portfolio-templates.git
```

---

## Replacing the Avatar / Photo (Aura & Cinematic)

Both **Aura** and **Cinematic** use SVG figure placeholders. To replace with your real photo:

**Aura template:**
```html
<!-- Find this in the hero section -->
<div class="avatar-img">
  <svg class="avatar-figure" ...> ... </svg>
</div>

<!-- Replace with your photo -->
<div class="avatar-img">
  <img src="your-photo.jpg" alt="Your Name"
    style="width:100%;height:100%;object-fit:cover;border-radius:50%;">
</div>
```

**Cinematic template:**
```html
<!-- Find this -->
<div class="hero-avatar">
  <svg class="avatar-svg" ...> ... </svg>
</div>

<!-- Replace with your photo — use a PNG with transparent background -->
<div class="hero-avatar">
  <img src="your-cutout.png" alt="Your Name"
    style="width:100%;filter:drop-shadow(0 0 80px rgba(140,100,255,.2));">
</div>
```

> **Tip for Cinematic:** Use a photo with a plain/dark background, or remove the background using [remove.bg](https://remove.bg) (free) to get a clean PNG cutout. This makes the person blend naturally into the dark hero.

---

## What's Inside Each Template

- ✅ Single HTML file — CSS and JS fully embedded
- ✅ Google Fonts via CDN — no local files needed
- ✅ Zero dependencies — works offline after first load
- ✅ Fully mobile responsive
- ✅ Clean, readable code — easy to customize
- ✅ CSS variables at the top — change colors in seconds

---

## Quick Customization

Every template has CSS variables at the top of the `<style>` block:

```css
:root {
  --accent: #4f8ef7;   /* change to your brand color */
  --bg: #050b18;
}
```

Then find and replace the placeholder name, email, and links throughout the file.

---

## Roadmap

- [ ] Template 9 — **Aurora** (gradient mesh, glassmorphism, UI/UX designers)
- [ ] Template 10 — **Minimal** (single page, ultra-clean, students / new grads)
- [ ] Template 11 — **Data** (chart-heavy, data scientists / analysts)
- [ ] Screenshot previews for all templates

---

## License

MIT — free to use, modify, and distribute for personal and commercial projects.

---

*If this helped you, give the repo a ⭐ — it helps others find it.*

*Made with care by [BaysaTech](https://github.com/Statisticsage)*
