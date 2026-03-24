# tmfittro Personal Web Page

## Overview
A simple personal website created for the BAIS 3300 course at the University of Iowa. It features a homepage with photos and interests, and a schedule page.

## Tech Stack
- **Languages:** HTML5, CSS3
- **Backend:** None (static site)
- **Server (dev):** Python's built-in HTTP server on port 5000

## Project Structure
- `index.html` — Main homepage
- `schedule.html` — Course schedule page
- `style/stylesheet.css` — Site-wide styles
- `images/` — Profile photos

## Running the App
The workflow starts a Python HTTP server:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment
Configured as a **static** deployment with `publicDir: "."`.
