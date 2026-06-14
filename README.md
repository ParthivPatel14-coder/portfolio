# Parthiv Patel — Developer Portfolio

A clean, responsive personal portfolio website built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no build tools — just fast, lightweight, and deployable anywhere.

**Live site →** https://parthivpatel14-coder.github.io/portfolio/

---

## About the Project

This portfolio was built to showcase my projects, skills, and certifications as a web developer. It is a single-page application with smooth scroll navigation, scroll-triggered animations, and a fully responsive layout that works on all screen sizes.

The design uses a warm cream background with an indigo accent system — intentionally avoiding the generic dark-theme developer portfolio look.

---

## Features

- **Single-page layout** with smooth scrolling between sections
- **Sticky navbar** with backdrop blur and a custom two-part logo badge
- **Hero section** with animated badge, call-to-action buttons, and social links
- **About section** with education timeline cards
- **Skills grid** organized by category (Backend, Frontend, Database, AI, etc.)
- **Projects section** with a featured card for the current active project
- **Certificates section** listing all LinkedIn Learning, Deloitte, and IIT Bombay certifications
- **Contact section** with direct-action cards (email, phone, LinkedIn, GitHub, resume download)
- **Scroll-triggered animations** via Intersection Observer API
- **Fully responsive** — tested on mobile, tablet, and desktop
- **No dependencies** — zero npm packages, zero build step

---

## Tech Stack

| Layer | Technology |

| Markup | HTML5 |
| Styling | CSS3 (custom properties, flexbox, grid) |
| Interactivity | Vanilla JavaScript (ES6) |
| Fonts | Google Fonts — Inter + Space Grandi |
| Animations | CSS keyframes + Intersection Observer API |



## Sections

| Section | Description |

| Home | Hero with name, title, CTA buttons, and contact links |
| About | Personal introduction and education history |
| Skills | Technical skills organized into six categories |
| Projects | Portfolio, Auto Care Pro, Stock Prediction Portal |
| Certificates | LinkedIn Learning, Deloitte, IIT Bombay, TATA |
| Contact | Direct-link cards for all contact channels |



## Projects Featured

### Stock Prediction Portal *(In Development)*
Full-stack stock analysis and prediction platform.
**Stack:** Django · React · Django REST Framework · Python · ML

### Auto Care Pro *(Completed)*
Multi-role vehicle service platform with booking, payments, and WhatsApp notifications.
**Stack:** Django · HTML · Bootstrap · Stripe · Twilio

### Personal Portfolio *(This project)*
**Stack:** HTML5 · CSS3 · Vanilla JavaScript

---

## File Structure

```
portfolio/
├── index.html                  # Main portfolio page (single file)
├── style.css
├── script.js
├── assets/
│   └──   Patel ParthivKumar.pdf  # Resume — linked from portfolio       
└── README.md
```

> **Note:** The resume PDF must be in the same directory as `index.html` for the download link to work.

---

## Getting Started

No installation or build step required.

**Option 1 — Open locally:**
```bash
git clone https://github.com/ParthivPatel14-coder/portfolio.git
cd portfolio
# Open index.html in any browser
```

**Option 2 — Deploy on GitHub Pages:**
1. Push the repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your site will be live at `https://ParthivPatel14-coder.github.io/portfolio`



## Customization

All content is in `index.html`. To update:

- **Name / title / bio** — edit the `#home` and `#about` sections
- **Projects** — find `#projects` and update or add `.project-card` blocks
- **Certificates** — find `#certificates` and update `.cert-card` blocks
- **Colors** — all design tokens are CSS custom properties in `:root` at the top of `<style>`
- **Resume** — replace `Patel_ParthivKumar_Resume.pdf` with your updated file (keep the same filename)

---

## Contact

**Parthiv Patel**
- LinkedIn: [linkedin.com/in/patel-parthiv-630252370](https://linkedin.com/in/patel-parthiv-630252370)
- GitHub: [github.com/ParthivPatel14-coder](https://github.com/ParthivPatel14-coder)
- Location: Ahmedabad, Gujarat, India

---

## License

This project is open source under the [MIT License](LICENSE).

Feel free to fork it, adapt it for your own portfolio, and give it a ⭐ if you found it useful.
