# Zeesan Tarafdar — Developer Portfolio

A responsive personal portfolio styled like a code editor. Each section is a "file tab" (`index.html`, `about.js`, `skills.json`, `projects.md`, `contact.txt`), with a dark theme, syntax-highlight colors and a blinking cursor.

**Live site:** _add your deployed link here_

## Features

- Code-editor look: tab bar, line numbers, terminal-style contact section
- Sticky tab bar that highlights the section you are viewing
- Smooth scrolling and fade-in on scroll
- Fully responsive; the mobile hero fits on one screen
- Respects `prefers-reduced-motion` and has visible keyboard focus
- No frameworks or build step, just HTML, CSS and vanilla JavaScript

## Sections

| Tab | Content |
|---|---|
| `index.html` | Intro, skill badges, call-to-action buttons |
| `about.js` | Summary and education (BCA, MAKAUT) |
| `skills.json` | Languages, frameworks, tools, soft skills |
| `projects.md` | Live project cards |
| `contact.txt` | Email and phone in a terminal-style box |

## Projects featured

| Project | Description | Link |
|---|---|---|
| Docsuite | Medical-store app for purchases from distributors and sales to customers | https://docsuite.web.app/ |
| BikeShowroom | Showroom management for purchasing and selling products | https://joygopalevauto.web.app/ |
| SchoolManagement | Attendance, fees, results and salary management (in development) | https://erp.thebsahowrah.com/ |

## Tech stack

- **HTML5**: semantic structure
- **CSS3**: custom properties, flexbox, grid, media queries
- **JavaScript**: `IntersectionObserver` for active tab and scroll reveal
- **Fonts**: JetBrains Mono and Inter (Google Fonts)

## Project structure

```
portfolio/
├── index.html
├── style.css
└── README.md
```

## Run locally

1. Clone or download the project
2. Open `index.html` in a browser

Or use the VS Code **Live Server** extension for auto-reload.

## Customize

- **Colors:** change the variables in `:root` in `style.css`
- **Content:** edit the text in `index.html`
- **Add a tab:** add a new `<a class="tab">` in the `<nav>` and a matching `<section id="...">`

## Deploy

Works on any static host: GitHub Pages, Netlify, Firebase Hosting or Vercel. Upload `index.html` and `style.css` together.

## Contact

- Email: zeesantarafdar617@gmail.com
- Phone: +91 7478376833

© Zeesan Tarafdar