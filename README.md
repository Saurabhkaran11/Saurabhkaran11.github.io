# saurabhkaran11.github.io

Personal portfolio of **Saurabh (Karan) Agrawal** — backend engineer (ex-PayPal) working on payments, fraud-decisioning systems and multi-agent AI.

**Live:** https://saurabhkaran11.github.io/

## Featured on the site

| Project | What it is | Live |
|---|---|---|
| [PitchCoach](https://github.com/Saurabhkaran11/pitchcoach) | Scores a spoken startup pitch like a YC partner, rewrites it in your voice | [Demo](https://pitchcoach-five.vercel.app/) |
| [IncidentPilot](https://github.com/Saurabhkaran11/IncidentPilot) | Investigates a failed AWS workflow and issues a verified recovery receipt | — |
| [Local Loop](https://github.com/Saurabhkaran11/web-mcp) | Shopify storefront where shopper and browser agent share one cart, via WebMCP | [Demo](https://web-mcp-mu.vercel.app/) |
| [EnterpriseOS](https://github.com/Saurabhkaran11/EnterpriseOS) | An AI employee operating five connected enterprise tools | [Demo](https://enterprise-os-gamma.vercel.app/) |
| [ForgeOS](https://github.com/Saurabhkaran11/ForgeOS) | Six coordinated AI agents that research, spec and go to market | — |
| [LegalMesh](https://github.com/Saurabhkaran11/LEGALMESH) | 7 agents over 6.7M legal cases — Stanford LLM × Law Hackathon | — |

## Structure

| File | Purpose |
|------|---------|
| `index.html` | The entire site — HTML, CSS and JS in one file, no build step |
| `README.md` | This file |

## Run locally

```bash
git clone https://github.com/Saurabhkaran11/Saurabhkaran11.github.io.git
cd Saurabhkaran11.github.io
python3 -m http.server 8000     # then open http://localhost:8000
```

## Deploy

GitHub Pages serves the `main` branch root — push and it is live in under a minute:

```bash
git add . && git commit -m "Update portfolio" && git push origin main
```

## Editing

- **Projects** — edit the `<div class="card">` blocks in the Projects section.
- **Stack** — edit the `.chip` spans in the Stack section.
- **Colours** — change the CSS custom properties under `:root`.
- **Recently updated** — populated live from the GitHub API; no edit needed.

## Contact

[LinkedIn](https://www.linkedin.com/in/saurabhagrawal11/) · saurabhkaran11@gmail.com · San Jose, CA
