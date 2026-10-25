# Ansh — Software & Data Portfolio

Personal portfolio of **Ansh**, a BSc (Hons) Computer Science student at Delhi University, interested in software development and data analytics.

**Live site:** https://anshsharma2674.github.io

<!-- Add a screenshot of the site here once you have one:
![Portfolio preview](preview.png)
-->

## What's on the site

- **Hero:** an animated 3D intro (Three.js) with a friendly avatar greeting.
- **About:** who I am, what I'm studying, and what I'm looking for.
- **Projects:** a sideways-scrolling carousel of the things I've built.
- **Certifications:** completed job simulations and badges, linked to their verification pages.
- **Education and Skills:** the foundations I'm building on and the tools I'm learning.
- **Contact:** email, LinkedIn and GitHub.

## Projects

| Project | What it does | Live |
| --- | --- | --- |
| Student Productivity & Attendance Manager | Academic dashboard for attendance, assignments, exams, marks, CGPA and study tasks, with a 3D interface and Chart.js charts. | [Open](https://anshsharma2674.github.io/student-productivity-manager/) |
| CareerMatch AI — Resume & Skill Gap Analyzer | Compares a resume with a job description and explains the skill gap. Everything is parsed in the browser. | [Open](https://anshsharma2674.github.io/CareerMatch-AI-Resume-Skill-Gap-Analyzer/) |
| SpendWise AI — Smart Expense Analyzer | Private expense dashboard with budgets, savings goals and explainable, rule-based insights. Data stays in the browser. | [Open](https://anshsharma2674.github.io/SpendWise-AI-Smart-Expense-Analyzer/) |

## Certifications

- Deloitte Data Analytics Job Simulation (Forage)
- MongoDB Overview: Core Concepts & Architecture (badge)

## Built with

- HTML, CSS and vanilla JavaScript in a single `index.html`, with no build step
- [Three.js](https://threejs.org/) for the hero scene, with a 2D canvas fallback when WebGL isn't available
- Google Fonts: DM Sans, DM Mono and Playfair Display
- Hosted on GitHub Pages

The site also supports keyboard navigation, a skip link, visible focus states, a responsive layout, and reduced-motion preferences.

## Project structure

```text
.
├── index.html   # the whole site: styles, content data and scripts
└── README.md
```

## Run it locally

No install is needed.

1. Clone the repository:
   ```bash
   git clone https://github.com/anshsharma2674/anshsharma2674.github.io.git
   ```
2. Open `index.html` in your browser.

Optional: serve it locally with Python:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Editing the content

All text, links and project cards come from the `window.PORTFOLIO` object near the bottom of `index.html`. You rarely need to touch the HTML.

To add a new project, add an entry to the `projects` list:

```js
{
  number: "04",
  category: "SOFTWARE PROJECT",
  name: "Project name",
  description: "One or two sentences about what it does.",
  highlights: ["Feature one", "Feature two", "Feature three", "Feature four"],
  technologies: ["JavaScript", "HTML & CSS"],
  image: "data:image/svg+xml;base64,...", // or a path such as "images/project.png"
  imageAlt: "Short description of the image",
  links: [{ label: "View live project", url: "https://example.com/" }]
}
```

The project count, the carousel and the progress bar update automatically.

## Deploying

The repository is named `anshsharma2674.github.io`, so GitHub Pages serves it automatically.

1. Commit the updated `index.html` to the `main` branch.
2. Wait a minute or two for GitHub Pages to rebuild.
3. Refresh https://anshsharma2674.github.io (use a hard refresh if you still see the old version).

## Contact

- Email: ansh64515@gmail.com
- LinkedIn: [linkedin.com/in/ansh1605](https://www.linkedin.com/in/ansh1605/)
- GitHub: [github.com/anshsharma2674](https://github.com/anshsharma2674)

Open to software and data internships.
