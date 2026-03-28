[README.md](https://github.com/user-attachments/files/26320138/README.md)
# Christopher Wozniak — Personal Website

A fully self-contained personal portfolio website built with HTML, CSS and JavaScript as part of the **AI-Native training programme** at [Pursuit.org](https://pursuit.org).

---

## 🌐 Live Features

- **Hero section** — introduction with embedded profile photo
- **About section** — bio, skill tags and stat cards
- **Photo gallery** — 5 embedded travel & adventure photos
- **Experience timeline** — animated career history
- **Interactive map** — Leaflet.js map pinpointing the Pursuit.org training facility in Long Island City, NY
- **Contact section** — links to email, LinkedIn and GitHub
- **Dark / Light mode toggle** — smooth theme switch including map tile swap

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Styling, layout, animations, theme variables |
| JavaScript (vanilla) | Theme toggle, map initialisation, scroll animations |
| [Leaflet.js](https://leafletjs.com/) | Interactive map |
| [CARTO tile layers](https://carto.com/) | Dark & light map tiles |
| [Google Fonts](https://fonts.google.com/) | Playfair Display & DM Sans typefaces |
| Base64 encoding | All images embedded directly in HTML — no external files needed |

---

## 📁 Project Structure

```
index.html    ← The entire website in one single file
README.md     ← This file
```

No frameworks, no build tools, no dependencies to install. Just open `index.html` in any browser.

---

## 🚀 How to Run

1. Download `index.html`
2. Open it in any modern web browser (Chrome, Firefox, Edge, Safari)
3. That's it — no server or internet connection required (except for the map tiles and fonts)

---

## 🗺️ Training Facility Location

**Pursuit.org**  
47-10 Austell Pl, 2nd Floor  
Long Island City, NY 11101

---

## 📬 Contact

- **Email:** christopher.wozniak@pursuit.org
- **LinkedIn:** [linkedin.com/in/christopher-wozniak-a0b2683b7](https://www.linkedin.com/in/christopher-wozniak-a0b2683b7)
- **GitHub:** [github.com/ChrisWozniak](https://github.com/ChrisWozniak)

---

## 📌 Notes

- All photos are embedded as Base64 strings inside the HTML file, so the website works as a single portable file with no image folder required.
- The dark/light toggle also swaps the map between dark and light tile styles to match the overall theme.
- The experience timeline items animate in on scroll using the Intersection Observer API.

---

*Built as a first project during the AI-Native Programme at Pursuit.org — 2026*
