# Taryn Fittro — Personal Landing Page

## Overview
A professional personal landing page for Taryn Fittro, a Business Analytics & Information Systems senior at the University of Iowa (graduating May 2026). Built to showcase skills, projects, and career interests in analytics and real estate to recruiters and hiring managers.

## Tech Stack
- **Languages:** HTML5 (semantic), CSS3 (external stylesheet only)
- **Fonts:** Inter via Google Fonts
- **Server (dev):** Python's built-in HTTP server on port 5000
- **No JavaScript, no backend, no frameworks**

## Project Structure
```
index.html              — Single-page landing site
css/stylesheet.css      — All styles (no inline CSS)
images/
  taryn1.jpeg           — Headshot used in hero section
  taryn2.jpeg           — Additional photo
PRD.md                  — Product requirements document
STANDARDS.md            — Technical and design standards
```

## Sections
- **Hero** — Name, tagline, photo, CTA buttons
- **About Me** — Bio, university info, career focus
- **Skills** — Python, Excel, data cleaning, Orange, Tableau, communication
- **Projects** — StreamFlix analysis (Random Forest, R²=0.477) and Data Mining classification project
- **Contact** — Email, LinkedIn, GitHub links

## Things Still Needed
- Update `mailto:your.email@example.com` in index.html with real email
- Update LinkedIn `href="#"` with real LinkedIn URL
- Update GitHub `href="#"` with real GitHub URL

## Running the App
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment
Configured as a **static** deployment with `publicDir: "."`.
