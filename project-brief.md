# rymow.com — Project Brief

## Overview
Personal portfolio site for Ryan Mowery, UI/UX and product designer. Hand-coded HTML/CSS/JS, no CMS. Ryan designs in Figma; code is managed separately. Direct file editing, no build process.

**Live site:** rymow.com
**Repo:** github.com/rymowery1/portfolio
**Hosting:** Digital Ocean

---

## Stack
- HTML / CSS / JS (plain, no frameworks)
- CSS custom properties (variables) for theming
- No Tailwind, no Pico, no preprocessors

---

## Information Architecture

```
rymow.com/
├── index.html (Home)
├── work/
│   ├── index.html (Work — case studies + more work)
│   ├── yahoo-global-navigation/
│   │   └── index.html
│   ├── yahoo-video-player/
│   │   └── index.html
│   ├── yahoo-wallet-payments/
│   │   └── index.html
│   ├── sendoso-send-tracking/
│   │   └── index.html
│   ├── ey-career-center/
│   │   └── index.html
│   ├── cengage-website-redesign/
│   │   └── index.html
│   ├── wells-fargo-remediation/
│   │   └── index.html
│   ├── nike-ey-storytelling/
│   │   └── index.html
│   ├── miscellaneous/
│   │   ├── index.html
│   │   ├── taco-bell-loyalty/
│   │   │   └── index.html
│   │   ├── bta-album-cover/
│   │   │   └── index.html
│   │   ├── good-day-bad-day/
│   │   │   └── index.html
│   │   ├── nike-data-design-system/
│   │   │   └── index.html
│   │   └── brand-identity-logos/
│   │       └── index.html
│   └── experiments/
│       ├── index.html
│       ├── ascii-weather/
│       │   └── index.html
│       ├── ccms-signage/
│       │   └── index.html
│       ├── 100-days-2020/
│       │   └── index.html
│       └── 100-days-2026/
│           └── index.html
├── writing/
│   ├── index.html (Writing — post index)
│   └── [post-slug]/
│       └── index.html
├── about/
│   └── index.html
└── contact/
    └── index.html
```

---

## Content Structure

### Case Studies (full dedicated pages)
Deep-dive project pages with narrative, process, and outcomes.

| Project | Client | Role |
|---------|--------|------|
| Global Navigation | Yahoo | Product Design Lead |
| Video Player | Yahoo | Product Design Lead |
| Wallet + Payments | Yahoo | Product Design Lead |
| Send Tracking & Management | Sendoso | Product Design Lead |
| EY Career Center | EY | UX Design & Strategy Lead |
| Website Redesign | Cengage | UX Design |
| Remediation Platform | Wells Fargo | UX Design & Strategy Lead |
| Nike & EY Storytelling | Nike / EY | Visual Design Lead |

### Miscellaneous (lighter showcase pages)
Work worth showing without a full case study treatment.
- TacoBell Loyalty
- BTA Album Cover
- Good Day Bad Day
- Nike Data Design System
- Brand Identity / Logos

### Experiments (lighter showcase pages)
Personal and side projects.
- ASCII Weather
- CCMS Signage
- #100DaysProject | 2020
- #100DaysProject | 2026

### Writing
Individual post pages. Post index at /writing/.

---

## Work Page Structure
The main Work page (work/index.html) uses a tiered layout:
1. **Case studies** — 8 featured projects, full cards
2. **More Work** — secondary section with links to Miscellaneous and Experiments index pages

---

## Design Notes
- Ryan designs in Figma first; a separate design-brief.md will be added once the Figma aesthetic is finalized
- CSS approach: plain CSS with custom properties — intentional choice to keep simple pages simple while enabling art-directed layouts without framework constraints
- Password protection strategy for client work TBD

---

## Status
- [ ] Finalize Figma design
- [ ] Add design-brief.md
- [ ] Scaffold all HTML pages per IA above
- [ ] Connect GitHub repo to Digital Ocean for deployment
