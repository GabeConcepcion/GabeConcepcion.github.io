# Gabe Concepcion — Technical Portfolio & Systems Showcase

[![Live Site](https://img.shields.io/badge/Live_Site-gabeconcepcion.com-38bdf8?style=flat&logo=google-chrome&logoColor=white)](https://gabeconcepcion.com/)
[![GitHub Profile](https://img.shields.io/badge/GitHub-GabeConcepcion-1e293b?style=flat&logo=github&logoColor=white)](https://github.com/GabeConcepcion)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gabe_Concepcion-0284c7?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabe-concepcion/)

Source code for [https://gabeconcepcion.com](https://gabeconcepcion.com), an interactive technical portfolio showcasing enterprise IT systems administration, endpoint diagnostics, and security detection engineering workflows.

---

## Architecture & Features

- **Custom Domain & DNS:** Deployed via **GitHub Pages** with apex domain routing and DNS managed via **Cloudflare**.
- **Dynamic GitHub API Ingestion:** Automatically fetches, parses, and renders technical investigation reports and detection walkthroughs directly from the [`Threat-Hunting-Reports`](https://github.com/GabeConcepcion/Threat-Hunting-Reports) repository via the GitHub REST API.
- **Search & Recruiter Optimization:** Includes Schema.org `Person` JSON-LD structured metadata, OpenGraph tags, and canonical indexing tags for search engine discovery.
- **Pure Native Web Stack:** Built with zero runtime frameworks or heavy libraries—relying on semantic HTML5, modern CSS Grid/Flexbox with custom variables, and vanilla asynchronous JavaScript (`fetch`).

---

## Tech Stack

| Layer | Technologies / Services |
| :--- | :--- |
| **Frontend** | HTML5, CSS3 (Custom Properties, Glassmorphism UI), Vanilla JavaScript (Async/Await) |
| **Hosting & DNS** | GitHub Pages, Cloudflare DNS (Apex & Subdomain routing) |
| **Data & APIs** | GitHub REST API v3 (Dynamic repository content ingestion) |
| **Typography** | Inter, Fira Code (Google Fonts CDN) |
