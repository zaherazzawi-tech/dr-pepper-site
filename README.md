# Dr Pepper Fan Website

A modern, interactive fan-made website for Dr Pepper — built with pure HTML, CSS, and JavaScript. No frameworks, no build tools, no dependencies. Just drop it on GitHub Pages and go.

## Features

- 🎯 Custom animated cursor with lag effect
- 🫧 Floating bubble hero animation
- 🥫 Animated 3D-style Dr Pepper can
- 📊 Count-up stats on scroll
- 🃏 Hover-reveal flavor cards
- 📜 Scrolling ticker strip
- 🎚️ Interactive flavor mixer with dynamic results
- ✨ Scroll-triggered reveal animations
- 📱 Fully responsive

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Hit **Save** — your site will be live at `https://yourusername.github.io/dr-pepper-site/`

## Local Development

No build step needed. Just open `index.html` in your browser:

```bash
# Option 1: Open directly
open index.html

# Option 2: Use a local server (recommended for full features)
npx serve .
# or
python3 -m http.server 8080
```

## File Structure

```
dr-pepper-site/
├── index.html      # Everything lives here — self-contained
└── README.md
```

## Customization

All styles use CSS variables at the top of the file:

```css
:root {
  --pepper-red: #8B1A1A;
  --pepper-dark: #3D0A0A;
  --pepper-crimson: #C0392B;
  --pepper-gold: #C8934A;
  --pepper-cream: #FAF3EC;
}
```

Change these to retheme the entire site instantly.

---

> ⚠️ Fan-made concept site. Not affiliated with Dr Pepper / Keurig Dr Pepper.
