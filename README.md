# Andrijana Miković — Portfolio

**Live site:** [andrijanamikovic.github.io](https://andrijanamikovic.github.io)

## About me

I'm a Software Engineer I at GDi Solutions in Belgrade, Serbia, working across the full stack — Vue.js on the frontend, Node.js and PostgreSQL on the backend, with some Python/ArcPy for geoprocessing work and continued maintenance of a legacy Java/Vuetify platform for existing customers. I'm currently leading the build-out of our in-house UI component library (an in-progress Vuetify replacement) and getting increasingly involved in architecture and design decisions.

I hold an M.Sc. in Software Engineering from the University of Belgrade's School of Electrical Engineering (thesis: *Analysis of trends in world cinematography in the early 21st century*, a social-network-analysis project in Python/NetworkX), and a B.Sc. in Computer Engineering & Information Technology from the same school.

- LinkedIn: [andrijana-mikovic382](https://www.linkedin.com/in/andrijana-mikovic382/)
- GitHub: [andrijanamikovic](https://github.com/andrijanamikovic)
- Email: andrijana.mikovic00@gmail.com

## About this website

This repository is the source for my personal portfolio site, built as a set of static pages: a projects/home page, an experience timeline, an education page, and a CV page with a downloadable PDF/DOCX.

It started from the free ["Massively" template by HTML5 UP](https://html5up.net/massively) (see `LICENSE.txt` for the original template's CCA 3.0 license and credits). In August 2026, the site was substantially redesigned and updated with the help of **Claude** (Anthropic's AI assistant): the visual design was rebuilt from scratch into a dark, developer-focused theme (custom CSS design system, a dedicated tech-stack/skills section, a project card grid, and a timeline layout for work experience), and the content was updated to properly reflect my full-stack experience — including the platform's migration from Java to Node.js/PostgreSQL, the geoprocessing and LLM-based tools I built, and my master's thesis project — rather than reading as frontend-only.

**Stack:** plain HTML/CSS/JS — no build step. Dark theme via CSS custom properties, Google Fonts (Inter + JetBrains Mono), Font Awesome icons, and a small vanilla-JS script for the mobile nav toggle and scroll-reveal animations.

**Structure:**

```
Portfolio/
├── index.html          # Home — intro, tech stack, project grid
├── experience.html      # Work experience timeline
├── education.html       # Education history
├── cv.html               # CV page with downloadable PDF
├── assets/
│   ├── css/style.css     # Design system (dark theme, components)
│   ├── js/app.js         # Nav toggle + scroll-reveal
│   └── AndrijanaMikovicCV.pdf
└── images/
```

## Credits

Originally built on the "Massively" template by HTML5 UP (html5up.net), used under the CCA 3.0 license — see `LICENSE.txt`. Icons by Font Awesome.
