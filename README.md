# ☁️ Cloud Architect

> An interactive **AWS architecture diagram builder** — drag, drop, connect, and get AI-powered architecture reviews right in the browser.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-cloud--architect--deploy.vercel.app-brightgreen?style=flat-square&logo=vercel)](https://cloud-architect-deploy.vercel.app/)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Claude AI](https://img.shields.io/badge/Claude%20AI-Anthropic-blueviolet?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

**[→ Try it live](https://cloud-architect-deploy.vercel.app/)**

---

## What it does

Design AWS architectures visually without any cloud account needed. Drag services onto a canvas, connect them, then ask Claude AI to review your design for best practices, security gaps, and cost considerations.

![Demo preview — drag-and-drop AWS diagram builder with AI review panel]

---

## Features

| Feature | Description |
|---------|-------------|
| Drag & drop canvas | Add EC2, S3, Lambda, RDS, and 15+ AWS services |
| Visual connections | Click to draw arrows between services |
| AI architecture review | Claude AI reviews your design for best practices |
| Save & load | Diagrams persist in browser LocalStorage |
| Export as PNG | Download your architecture as an image |
| Service search | Find AWS services quickly from the sidebar |
| Mini-map | Overview panel for large diagrams |
| Undo support | `Ctrl+Z` for mistake recovery |

---

## Demo

**[→ cloud-architect-deploy.vercel.app](https://cloud-architect-deploy.vercel.app/)**

No installation needed — runs entirely in the browser.

### How to use the AI Review

1. Design your architecture on the canvas
2. Enter your Anthropic API key (`sk-ant-...`) in the input field
3. Click **✨ AI Review** — Claude analyses your diagram and returns feedback

> Get a free API key at [console.anthropic.com](https://console.anthropic.com)

---

## Running locally

```bash
# Clone the repo
git clone https://github.com/Shreyaaaaaak/cloud_architect.git
cd cloud_architect

# Open directly in browser — no server or install needed
open cloud_architect.html
```

---

## Architecture

```
Browser
  │
  ├── HTML5 Canvas API       ← renders the diagram
  ├── Vanilla JS             ← drag-and-drop, connection logic
  ├── LocalStorage           ← save/load diagrams
  ├── Canvas → PNG export    ← screenshot utility
  └── Anthropic Claude API   ← AI review (client-side fetch)
```

No backend. No build step. Everything runs in a single HTML file.

---

## Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Rendering:** HTML5 Canvas API
- **AI:** Claude API (Anthropic) — client-side
- **Storage:** Browser LocalStorage
- **Deployment:** Vercel

---

## Project Structure

```
cloud_architect/
├── cloud_architect.html    # Entire app — canvas, logic, and styles
└── README.md
```

---

## Example use cases

- Designing multi-tier AWS architectures (VPC, ALB, EC2, RDS)
- Studying for AWS certifications — visualise service relationships
- Creating architecture diagrams for project presentations
- Getting instant AI feedback on architecture decisions

---

## Limitations

- Diagrams stored in browser only (no account/cloud sync)
- Requires your own Anthropic API key for AI review
- Single-page app — no collaboration features yet

---

## Future improvements

- [ ] Multi-cloud support (Azure, GCP icons)
- [ ] Shareable diagram links
- [ ] Pre-built architecture templates (3-tier web app, serverless, etc.)
- [ ] Backend storage with user accounts
- [ ] Export to AWS CloudFormation / Terraform

---

## Built by

**Shreya Kaushik** — ECE @ KIIT University (2027)  
[GitHub](https://github.com/Shreyaaaaaak) · [LinkedIn](https://www.linkedin.com/in/shreyakaushik2308)

---

## License

MIT — open to fork and build on.
