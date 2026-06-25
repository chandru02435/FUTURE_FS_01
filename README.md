# Chandru A — Personal Portfolio Website

A futuristic AI-inspired personal portfolio website.

## Description

A fully responsive, dark-themed personal portfolio website built using pure HTML, CSS, and JavaScript — no frameworks required. The site features an animated Canvas-based particle system with 150 floating stars, a moving cyan grid background, glowing ambient orbs, a typewriter effect cycling through professional roles, and smooth scroll-reveal animations. It showcases the developer's skills, projects, experience, and contact information in a visually immersive futuristic interface. The contact form is powered by Formspree for real-time email delivery. Hosted for free on GitHub Pages.

---

## Getting Started

### Dependencies

* Windows 10 or above (also works on macOS and Linux)
* Any modern web browser — Google Chrome, Firefox, Microsoft Edge (latest versions)
* Internet connection (required for Formspree contact form to send emails)
* VS Code (recommended code editor)
* Live Server extension for VS Code (for local development)
* Git (for version control and pushing to GitHub)
* A free Formspree account at [formspree.io](https://formspree.io) (for contact form)
* A free GitHub account at [github.com](https://github.com) (for hosting)

---

### Installing

* Download or clone this repository from GitHub:

```
git clone https://github.com/chandru02435/FUTURE_FS_01.git
```

* Or download the ZIP file directly from the GitHub repository page and extract it

* No additional libraries or packages need to be installed — the project is a single self-contained HTML file

* If using the contact form, open `index.html` and replace the Formspree form ID with your own:

```
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

---

### Executing Program

* **Method 1 — Open directly in browser:**

```
Double-click index.html → Opens in your default browser
```

* **Method 2 — Using VS Code Live Server (Recommended):**

Step 1 — Install Live Server extension in VS Code

Step 2 — Open the project folder in VS Code

Step 3 — Right-click `index.html` in the Explorer panel

Step 4 — Click "Open with Live Server"

```
Site runs at: http://127.0.0.1:5500/index.html
```

* **Method 3 — View live on GitHub Pages:**

```
https://chandru02435.github.io/FUTURE_FS_01
```

---

## Help

**Site appears fully white after deploying to GitHub Pages:**
```
Make sure your file is named exactly index.html (not chandru_portfolio.html)
Then go to Settings → Pages → Branch: main / root → Save
Wait 2-3 minutes and hard refresh with Ctrl + Shift + R
```

**Contact form shows "Bad form post request":**
```
Make sure every input has a name attribute:
name="name" / name="email" / name="message"
Also make sure the form tag has method="POST"
```

**Particles or grid animation not showing:**
```
Open the site in Google Chrome or Firefox
Clear browser cache with Ctrl + Shift + R
Make sure JavaScript is enabled in your browser settings
```

**Git push failing with "src refspec main does not match":**
```
git add .
git commit -m "first commit"
git push -u origin main
```

---

## Authors

**Chandru A**
- Email: chandru02531@gmail.com
- Phone: +91 8248657655
- LinkedIn: [@chandru-a-170a13383](https://www.linkedin.com/in/chandru-a-170a13383)
- Location: Erode, Tamil Nadu, India

---

## Version History

* 1.0
    * Contact form integration using Formspree
    * Scroll reveal animations added
    * Responsive design fixes for mobile
    * See [commit history](https://github.com/chandru02435/FUTURE_FS_01/commits/main)

* 0.1
    * Initial Release
    * Hero section with typing animation
    * Canvas particle system and moving grid background
    * Skills, Projects, Experience, and Contact sections
    * Deployed on GitHub Pages

---

## License

This project is licensed under the MIT License — see the LICENSE.md file for details.

---

## Acknowledgments

Inspiration, design references, and resources used:

* [Dribbble](https://dribbble.com) — UI/UX design inspiration for layout and components
* [Awwwards](https://www.awwwards.com) — High quality website design inspiration
* [Behance](https://www.behance.net) — Real developer portfolio references
* [GitHub Portfolio Examples](https://github.com/topics/portfolio-website) — Open source portfolio projects
* [Formspree](https://formspree.io) — Contact form email handling
* [GitHub Pages](https://pages.github.com) — Free static site hosting
* [MDN Canvas API Docs](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API) — Canvas animation reference
* [CSS Tricks](https://css-tricks.com) — Flexbox and Grid layout guidance
