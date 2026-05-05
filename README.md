# Elite Company Digital — Landing Page v2.0

> High-performance marketing landing page built for a Brazilian digital agency. Pure HTML/CSS/JS — zero frameworks, zero build steps, production-ready.

**[→ Live Demo](https://jovemegidio.github.io/EliteLP-II/)**

---

## Preview

![Elite Company Digital Hero](uploads/IMG_9818.PNG)

---

## What's Inside

A single-file landing page engineered for conversion. Every pixel serves one goal: get the visitor to WhatsApp.

```
index.html          ← entire page (HTML + CSS + JS, self-contained)
uploads/            ← reference screenshots from the brand
.nojekyll           ← GitHub Pages config
```

---

## Tech Highlights

| Area | Approach |
|---|---|
| **Layout** | CSS Grid + Flexbox, no framework |
| **Typography** | Sora · Instrument Serif · JetBrains Mono (Google Fonts) |
| **Animations** | Pure CSS keyframes — float, ticker, reveal on scroll |
| **Scroll reveal** | Vanilla IntersectionObserver, no library |
| **Logo** | Inline SVG with gradient defs — crisp at any size |
| **Performance** | 1 HTTP request for markup · Fonts loaded async |
| **Hosting** | GitHub Pages (static, CDN-backed) |

---

## Features

- **Sticky header** with blur + transparency on scroll
- **Animated ticker** — live social proof loop
- **Hero brand display** — real logo mark with CSS glow and float animation
- **Floating data cards** — ROAS, conversion rate, real-time lead notification
- **Bento grid** — about section with magic-border hover effect
- **Service cards** with icon + hover lift
- **Process timeline** — numbered steps with connector lines
- **Results / case study** section with metric cards
- **FAQ accordion** — pure JS, smooth max-height transition
- **CTA section** — all buttons deep-linked to WhatsApp with pre-filled message
- **Responsive** — 3 breakpoints, mobile-first media queries
- **Semantic HTML** — proper `<header>`, `<nav>`, `<section>`, `<footer>`, ARIA labels

---

## Design System

```css
/* Color tokens */
--bg-0: #03060d          /* darkest background */
--blue-500: #1f8bff      /* primary brand blue */
--cyan-400: #2cc8ff      /* accent cyan */
--grad-blue: linear-gradient(135deg, #6ee2ff → #0a52b8)

/* Type scale */
Hero h1:  clamp(56px, 9.6vw, 152px)
Section:  clamp(44px, 5.6vw, 78px)
Body:     16px / 1.6
```

---

## Running Locally

No build step needed:

```bash
# Clone
git clone https://github.com/jovemegidio/EliteLP-II.git
cd EliteLP-II

# Open directly in browser
start index.html          # Windows
open index.html           # macOS
xdg-open index.html       # Linux
```

Or with any static server:

```bash
npx serve .
# → http://localhost:3000
```

---

## Business Context

Built for **Elite Company Digital**, a performance marketing agency led by Daniel Brito (São Paulo, Brasil).

| Metric | Value |
|---|---|
| Impressions generated | 13M+ |
| Companies served | 120+ |
| Average ROAS | 7.4× |
| Revenue generated for clients | R$ 4M+ |

The page implements the agency's **Elite Performance Method** positioning — strategy-first, results-focused, no vanity metrics.

---

## Customization

**WhatsApp number** — replace `5511999999999` globally with the real number (DDD + number, digits only):

```bash
# macOS / Linux
sed -i 's/5511999999999/YOUR_NUMBER/g' index.html

# Windows PowerShell
(Get-Content index.html) -replace '5511999999999','YOUR_NUMBER' | Set-Content index.html
```

---

## License

Private project. All rights reserved — Elite Company Digital © 2026.
