# RyMow.com — Project Brief

## Site Goal
A personal portfolio and brand presence for Ryan Mowery, UI/UX and Graphic Designer. The primary goal is to convert visitors into clients or collaborators.

**Primary user action:** Get in touch / Start a project

---

## Tech Stack
- Plain HTML, CSS, JavaScript — no frameworks, no build tools
- Single file per page (clean, portable)
- No CMS — content managed by editing files directly

---

## Infrastructure
- **GitHub repo:** https://github.com/rymowery1/portfolio
- **Hosting:** Digital Ocean
- **Deployment:** Files pushed to GitHub repo, served via Digital Ocean
- **Security:** HTTPS via SSL certificate

---

## Information Architecture

```
Home
├── Work
│   ├── Project 01
│   ├── Project 02
│   └── Project 03...
├── About
└── Contact
```

### Pages

| Page | Key Content |
|---|---|
| **Home** | Hero, Selected Work (3–4 projects), About teaser, CTA |
| **Work** | Full project grid, filterable by category |
| **Project Detail** | Hero image, overview, process, gallery, next project |
| **About** | Photo, bio, skills/services, clients, CTA |
| **Contact** | Contact form, direct email, social links |

### Global Elements
- **Nav:** Logo/Name · Work · About · Contact
- **Footer:** © Ryan Mowery · Social links · Email

---

## File Structure (target)
```
index.html
work.html
about.html
contact.html
project-[name].html
css/
  style.css
js/
  script.js
assets/
  images/
```

---

## Design
Design aesthetic and system are defined separately in `design-brief.md` (provided by Ryan). Always refer to that file for typography, color, spacing, and visual direction.

---

## Notes
- Ryan is not a developer — keep code clean, well-commented, and easy to hand-edit
- Ryan will provide Figma designs/wireframes before each build phase
- Mobile responsiveness required on all pages
