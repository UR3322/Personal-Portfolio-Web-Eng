# Personal Portfolio Website

Personal portfolio website of **Muhammad Usman** — FinTech developer and final-year Financial Technology student at FAST-NUCES, Islamabad.

## Overview

A multi-page, fully responsive portfolio site built with pure HTML5 and CSS3 — no frameworks, no JavaScript, no build step. It showcases my profile, projects, skills, career goals, and contact details in a dark, professional theme.

## Features

- **7 pages:** Home, Profile, Gallery, Goals, Projects, Skills, Contact
- **Fully responsive:** layouts adapt for mobile (≤640px), tablet (≤1024px), and desktop
- **Pure CSS layouts:** Flexbox for navigation and profile sections, CSS Grid for project and gallery cards
- **Project showcase:** 9 projects, each with a direct link to its GitHub repository
- **Professional details:** SEO meta tags, favicon, sticky navbar, footer with social links

## Tech Stack

- HTML5
- CSS3 (Flexbox & Grid)
- FontAwesome icons
- Google Fonts (Inter)

## Setup

No build step needed — it's a static site.

1. Clone the repository:
   ```bash
   git clone https://github.com/UR3322/Personal-Portfolio-Web-Eng.git
   ```
2. Add your profile photo as `assets/profile.jpg`.
3. Open `index.html` in a browser — or serve the folder with any static server:
   ```bash
   npx serve .
   ```

## Project Structure

```
├── index.html      # Home / hero
├── profile.html    # About + focus areas
├── projects.html   # Project showcase with GitHub links
├── skills.html     # Skills with proficiency bars
├── goals.html      # Career roadmap
├── gallery.html    # Visual showcase
├── contact.html    # Contact details + social links
├── styling.css     # All styles (single stylesheet)
└── assets/
    └── profile.jpg # Profile photo (add your own)
```

## License

MIT — see [LICENSE](LICENSE).

## Author

**Muhammad Usman** — [GitHub](https://github.com/UR3322) · [LinkedIn](https://www.linkedin.com/in/muhammad-usman-142a9528b)
