# Auspicious Munemo | Portfolio

Personal portfolio for **Auspicious Munemo**, a Business and Data Analyst completing an MS in Business Analytics at Drexel University's LeBow College of Business.

**Live site:** [auspiciousmunemo.com](https://auspiciousmunemo.com)

## What's on the site

- **Hero:** positioning statement, availability status, and a one-click résumé download
- **Impact stats:** animated counters for key results from my experience
- **About:** how I work with stakeholders, data and automation
- **Projects:** case studies with links to the code
  - [Car Rental Service Relational Database](https://github.com/ausiemun-ux/SQL-Database-Analysis-Design-Project-Car-Rental-Service-Relational-Database-Design-): Oracle APEX and multi-table SQL on fleet utilization, customer retention and payment risk
  - [SmartShoe Generative Agentic AI](https://github.com/ausiemun-ux/Generative-Agentic-AI-Project): multi-agent AI prototype on Stack AI for a retail organization
- **Experience:** expandable timeline of roles, plus certifications
- **Skills:** SQL, Power BI, Tableau, Python, R, Advanced Excel, Jira and cloud platforms
- **Résumé:** view the PDF in the page or download it
- **Contact:** email, phone, location, LinkedIn and GitHub, with a copy-email button
- **Extras:** dark/light theme toggle, scroll progress bar, typing effect, scroll animations, mobile-friendly layout, and reduced-motion support

## Tech stack

Plain **HTML, CSS and JavaScript** with no framework and no build step.

| File | Purpose |
|---|---|
| `index.html` | Page structure and content |
| `styles.css` | Layout, theming (dark/light) and responsive styles |
| `script.js` | Theme toggle, animations, counters, accordion and copy-email |
| `Auspicious-Munemo-Resume.pdf` | Résumé served by the download button and page viewer |

Fonts: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) and [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts.

## Run locally

No installation needed. Download or clone the repo and open `index.html` in a browser.

To serve it on a local address instead:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deployment

Hosted on [Vercel](https://vercel.com), connected to this repository. Every commit to `main` redeploys the site automatically. The domain is registered with Namecheap and points to Vercel through DNS records.

## Updating content

- **Résumé:** upload a new PDF named exactly `Auspicious-Munemo-Resume.pdf` to replace the existing one.
- **Text, projects or experience:** edit `index.html`.
- **Colors and fonts:** edit the variables at the top of `styles.css`.

## Contact

- Email: [ausie.mun@gmail.com](mailto:ausie.mun@gmail.com)
- LinkedIn: [linkedin.com/in/auspiciousmunemo](https://www.linkedin.com/in/auspiciousmunemo)
- GitHub: [github.com/ausiemun-ux](https://github.com/ausiemun-ux)

© Auspicious Tinotenda Munemo. All rights reserved.
