# Frontend-Project-week-1
Static Webpage Design
# CloudVault — Secure Cloud Storage Landing Page

A responsive, dark-themed marketing landing page for **CloudVault**, a fictional cloud storage SaaS product.

## Project Structure

```
cloudvault/
├── index.html      # Main HTML document
└── style.css       # All styles (custom properties, layout, components, responsive)
```

## Tech Stack

- **HTML5** — semantic markup with ARIA labels and accessibility roles
- **CSS3** — custom properties, CSS Grid, Flexbox, responsive breakpoints
- No JavaScript, no frameworks, no build step

## Sections

| Section | ID | Description |
|---|---|---|
| Header | — | Sticky nav with logo and anchor links |
| Hero | — | Two-column grid with headline and feature image |
| Features | `#features` | Auto-fit card grid (encryption, collaboration, uptime) |
| Pricing | `#pricing` | Three-tier pricing cards with featured highlight |
| Security | `#security` | Compliance details + trust badge |
| CTA | `#contact` | Free trial call-to-action |
| Footer | — | Nav links + copyright |

## Design System

All design tokens live in `:root` inside `style.css`.

**Colors**
- `--color-primary`: `#c9a961` — luxurious gold
- `--color-accent`: `#d4af37` — bright gold for CTAs
- `--color-background`: `#0f0f1e` — deep dark base
- `--color-background-alt`: `#1a1a2e` — card/section backgrounds
- `--color-text-primary`: `#f5f5f0` — cream off-white
- `--color-text-secondary`: `#b0b0b0` — secondary text

**Typography**
- Body: system sans-serif stack
- Headings: Georgia/Garamond/Palatino serif stack

**Spacing scale:** `4px → 8 → 16 → 24 → 32 → 48 → 64px`

## Responsive Breakpoints

| Breakpoint | Changes |
|---|---|
| `≤ 768px` | Single-column hero, stacked nav, single-column grids |
| `≤ 480px` | Reduced font sizes and spacing, vertical nav |

## Accessibility

- WCAG AA contrast ratios (4.5:1) on all text
- ARIA labels on buttons and nav landmarks
- `:focus` outlines on all interactive elements
- Semantic HTML (`<header>`, `<main>`, `<footer>`, `<article>`, `<section>`, `<nav>`)

## Getting Started

No build tools needed. Just open `index.html` in a browser:

```bash
open index.html
# or
npx serve .
```
