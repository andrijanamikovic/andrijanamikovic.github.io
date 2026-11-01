# Andrijana Miković — Portfolio

**Live site:** [andrijanamikovic.github.io](https://andrijanamikovic.github.io)

## About me

I'm a full-stack software engineer at GDi Solutions in Belgrade, Serbia, working on a configurable enterprise Web GIS platform used by clients across many industries, including electricity distribution, sewerage networks, telecommunications and the oil industry. I joined in April 2024 and was promoted to Software Engineer I in April 2026.

I work across the whole stack: Vue.js on the frontend, Node.js and Java on the backend, PostgreSQL, Oracle and MySQL databases, Python/ArcPy for geoprocessing, and Docker-based deployments on client servers. Highlights:

- Helped lay the groundwork for the new generation of the platform: code structure, JSON-based configuration and global error handling for the configuration and sewerage network modules.
- Built JWT authentication with role-based access control as part of the Java-to-Node.js migration.
- Built an AI-assisted configuration generator on a self-hosted Llama model that cut a configuration from about an hour to a few minutes.
- Deployed the platform for more than 10 clients and worked with GIS specialists in GDi group offices in several countries.

I hold an M.Sc. in Software Engineering and a B.Sc. in Computer Engineering & Information Technology from the University of Belgrade's School of Electrical Engineering.

- LinkedIn: [andrijana-mikovic382](https://www.linkedin.com/in/andrijana-mikovic382/)
- GitHub: [andrijanamikovic](https://github.com/andrijanamikovic)
- Email: andrijana.mikovic00@gmail.com

## About this website

A static portfolio site: a home page with selected work, tech stack and projects, an experience timeline, an education page, and a CV page with a downloadable PDF.

**Stack:** plain HTML, CSS and JavaScript with no build step. Dark theme built on CSS custom properties, Google Fonts (Inter and JetBrains Mono), Font Awesome icons, and a small vanilla JS script for the mobile nav and scroll-reveal animations.

To run it locally, serve the folder with any static server, for example:

```bash
python -m http.server 8000
```

**Structure:**

```
Portfolio/
├── index.html            # Home: selected work, tech stack, projects
├── experience.html       # Work experience timeline
├── education.html        # Education
├── cv.html               # CV page with downloadable PDF
├── assets/
│   ├── css/style.css     # Design system (dark theme, components)
│   ├── js/app.js         # Nav toggle and scroll-reveal
│   ├── webfonts/         # Font Awesome fonts
│   └── AndrijanaMikovicCV.pdf
├── CV/                   # CV source (Word) and PDF
└── images/
```

## Credits

- The site first started from the "Massively" template by [HTML5 UP](https://html5up.net). It has since been rewritten from scratch, and no template code remains.
- Redesigned and updated with help from Claude (Anthropic's AI assistant).
- Icons: [Font Awesome Free](https://fontawesome.com) (icons CC BY 4.0, fonts SIL OFL 1.1, code MIT).
- Fonts: [Inter](https://rsms.me/inter/) and [JetBrains Mono](https://www.jetbrains.com/lp/mono/) via Google Fonts (SIL OFL 1.1).

## License

The site's code is available under the MIT License. My personal content (text, CV, photos and project images) is not covered by it. See [LICENSE.txt](LICENSE.txt).
