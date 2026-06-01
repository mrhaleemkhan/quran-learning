# Learn with Essa — Online Quran Academy

Live site: **[learnwithesha.com](https://learnwithesha.com/)**

A clean, enterprise-grade one-page website for an online Quran teaching service.
Single self-contained file (`index.html` — HTML + CSS + JS, no framework, no build).
The brand mark is **`assets/logo.svg`**, used in the navbar, footer and as the favicon.

---

## Page sections

1. **Sticky navbar** — logo, primary navigation, click-to-call, "Book Free Trial" button, mobile drawer
2. **Hero** — Bismillah, value proposition, two CTAs (Free Trial / WhatsApp), trust line, glass info card with checklist + admissions phone
3. **Courses** — 4 program cards
4. **Why Learn with Essa** — 4 differentiators + testimonial
5. **Lead instructor** — one featured teacher profile
6. **How it works** — three steps
7. **FAQ**
8. **CTA band**
9. **Contact** — info + inquiry form
10. **Footer**
11. **Floating WhatsApp**

> No public pricing page — admissions discusses fees after your trial.

## Design system

- **Indigo + amber** palette via CSS variables in `:root`
- Cool **slate** neutrals — restrained, professional
- Plus Jakarta Sans for UI, Amiri for the Bismillah
- Subtle 1px borders, minimal shadows, flat icons (no heavy gradients)
- Reveal-on-scroll, mobile-responsive down to 360px, `prefers-reduced-motion` honored

## SEO & meta

- `<link rel="canonical" href="https://learnwithesha.com/">`
- Open Graph tags
- SVG favicon
- Semantic HTML

## Deployment

Upload **`index.html`** + the **`assets/`** folder to any static host:

- Netlify / Vercel / Cloudflare Pages — drag-and-drop or Git
- GitHub Pages — push to `main` and enable Pages
- cPanel / Hostinger — upload to `public_html`

No build step.

## Customization

| Item             | Current value                  |
|------------------|--------------------------------|
| Domain           | `https://learnwithesha.com/`   |
| Email            | `essajehangiri@gmail.com`      |
| Phone / WhatsApp | `+92 306 5444488`              |
| Stats            | _(removed — no counter strip)_ |

### Colors

```css
--brand-600: #4f46e5;   /* primary indigo */
--brand-700: #4338ca;
--brand-500: #6366f1;
--gold-500:  #f59e0b;   /* amber accent */
```

### Logo

Edit `assets/logo.svg` or replace with your own. Keep the filename to avoid
updating `<img src="assets/logo.svg">` and `<link rel="icon">`.

### Form backend

The `<form id="trialForm">` has a demo submit handler. Wire to Formspree,
Web3Forms, Netlify Forms, or your own API as documented in the script section
of `index.html`.

## License

Free to use for personal and commercial Quran academy projects.
