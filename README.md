# 🎨 Premium Landing Page Templates

Two modern, responsive, framework-free landing page templates. Every template is a **single self-contained HTML file** — just open in a browser.

---

## ❄️ Frost — SaaS / Tech Landing

**Style:** Glassmorphism · Dark theme · Gradient mesh

![Preview](https://img.shields.io/badge/style-glassmorphism-6366f1)

| Section | Description |
|---------|-------------|
| Hero | Gradient mesh background, animated orbs, large headline with gradient text, dual CTAs with hover glow |
| Features | 3 glass cards with icons, hover lift + glow border effect |
| Pricing | 3-tier comparison with "Most Popular" badge, hover animations |
| Testimonials | Auto-advancing carousel with dots navigation |
| Footer | 4-column grid with newsletter signup form |

**Open:** `frost.html`

---

## 🏔️ Alpine — Restaurant / Hotel Landing

**Style:** Serif typography · Warm earth tones · Elegant minimal

![Preview](https://img.shields.io/badge/style-elegant_minimal-8b6914)

| Section | Description |
|---------|-------------|
| Hero | Full-width dark overlay with scroll indicator, serif display text |
| About | Split layout (image + text) with directional reveal animations |
| Menu | 3 elegant cards with image placeholders and pricing |
| Gallery | CSS grid masonry layout (6 items, mixed spans) |
| Reservation | Dark section with detailed booking form (date/time/guests/occasion) |
| Footer | Map placeholder + contact details + social links |

**Open:** `alpine.html`

---

## Features

- ✅ **Zero dependencies** — no frameworks, no build step
- ✅ **Single-file** — HTML + CSS + JS all inline
- ✅ **Mobile responsive** — tested across breakpoints
- ✅ **Scroll animations** — IntersectionObserver reveal effects
- ✅ **Accessible** — semantic HTML, aria labels, keyboard-friendly
- ✅ **Google Fonts** — Inter + Playfair Display (loaded via CDN)

## Usage

```bash
# Just open in browser
open frost.html
open alpine.html

# Or serve locally
python3 -m http.server 8000
```

## Customization

Everything is in CSS custom properties (`:root` variables). Change colors, fonts, and spacing in seconds:

```css
/* Frost */
--accent: #6366f1;    /* Primary color */
--bg: #0a0a0f;        /* Background */

/* Alpine */
--accent: #8b6914;    /* Gold accent */
--bg: #faf8f5;        /* Warm white */
```

Replace image placeholders with your own `<img>` tags or CSS `background-image` URLs.

---

**Author:** Diego Farango · [DILOmcfly](https://github.com/DILOmcfly)  
**License:** MIT
