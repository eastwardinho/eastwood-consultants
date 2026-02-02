# Eastwood Consultants Website

Professional B2B trade services website for Eastwood Consultants — bridging Vietnam, China, and Western markets.

## Quick Start

Open `index.html` in a browser, or run a local server:

```bash
# Python 3
python -m http.server 8000

# Node.js (if you have npx)
npx serve .

# Then visit http://localhost:8000
```

## Files

- `index.html` — Main page with all sections
- `styles.css` — All styling (responsive, mobile-first)
- `script.js` — Interactivity (smooth scroll, mobile menu, form handling)
- `favicon.svg` — Site favicon

## Features

✅ Clean, professional B2B design  
✅ Mobile responsive with hamburger menu  
✅ Smooth scroll navigation  
✅ Scroll-based navbar styling  
✅ Animated elements on scroll  
✅ Contact form with validation  
✅ All sections complete:
- Hero with stats
- About with values and founder profile
- 4 detailed services
- 6 industries grid
- Why Us with visual element
- 4-step process timeline
- 3 case studies
- 3 testimonials
- Contact form with info
- Full footer

## Colors

- **Navy:** #0f1c3f (primary dark)
- **Gold/Accent:** #c9a227 (CTAs, highlights)
- **White/Grays:** Clean backgrounds

## Typography

Uses [Inter](https://fonts.google.com/specimen/Inter) from Google Fonts.

## Customization

### To add real testimonials:
Edit the `.testimonial-card` sections in `index.html`.

### To add real case studies:
Edit the `.case-study-card` sections with actual client data.

### To connect the contact form:
Replace the `simulateFormSubmission()` function in `script.js` with an actual API call (e.g., Formspree, Netlify Forms, or your own backend).

Example with Formspree:
```html
<form action="https://formspree.io/f/YOUR_ID" method="POST">
```

### To add a real photo of Joe:
Replace the `.founder-placeholder` div with an actual `<img>` element.

## Deployment

This is a static site — deploy anywhere:
- Netlify (drag and drop)
- Vercel
- GitHub Pages
- Any web hosting

## Built For

Joe Eastwood / Eastwood Consultants  
Ho Chi Minh City, Vietnam

---

*Built 2026 by Frank Best*
