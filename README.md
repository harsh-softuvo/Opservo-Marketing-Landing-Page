# Opservo — Marketing Landing Page

A premium, single-page B2B SaaS marketing landing page for **Opservo**, an AI-powered infrastructure operations platform that monitors Linux servers, explains what's broken in plain English, and fixes issues automatically.

This project was built as part of a design internship task — using an AI design tool (Open Design AI) for the initial generation, followed by manual refinement in code.

---

## 🧠 About the Project

Opservo is positioned as *"the AI ops engineer for teams without an SRE"* — built for CTOs, DevOps leads, and startup founders who don't have a dedicated Site Reliability Engineer. This landing page was designed to communicate that value proposition within 5 seconds of landing on the page.

## 🎨 Design

- **Style:** Premium enterprise SaaS — inspired by Stripe, Vercel, Linear, Datadog, and Grafana
- **Colors:** Dark navy hero (`#0F172A`), white content sections, accent blue (`#2563EB`)
- **Typography:** Inter
- **Cards:** 16px rounded corners, soft shadows
- **Layout:** Fully responsive (desktop)

## 📄 Sections

| Section | Description |
|---|---|
| Navigation | Logo, Features, How It Works, Pricing, Contact, Get Started Free |
| Hero | Headline, sub-tagline, description, primary + secondary CTA |
| How It Works | 3-step flow — Install, Monitor, Fix |
| Core Features | Systems View, Inventory, Automate, Ask AI |
| Why Choose Opservo | 3-column comparison — Traditional Monitoring vs. Hiring an SRE vs. Opservo |
| Benefits | 6 supporting benefit cards |
| Pricing | Free Plan vs. Enterprise Plan |
| Final CTA | "Ready to Modernize Your Infrastructure?" |
| Footer | Product links, legal links, copyright |

## 🛠️ Tools & Process

- **Initial generation:** [Open Design AI](https://opendesign.ai) — from a single detailed prompt covering design direction, sections, and copy
- **Manual refinement:** Fixed broken image paths, wired up button interactivity, and added a Contact section (not part of the original AI generation)
- Full process, prompt used, and design decisions are documented in [`DESIGN-HANDOFF.md`](./DESIGN-HANDOFF.md)

## 📁 Files

- `opservo-landing.html` — the final landing page (open directly in a browser)
- `DESIGN-HANDOFF.md` — design/process documentation
- `DESIGN-MANIFEST.json` — design tokens and structure reference

## 🚀 View Locally

Clone the repo and open the HTML file directly:

```bash
git clone https://github.com/harsh-softuvo/Opservo-Marketing-Landing-Page.git
cd Opservo-Marketing-Landing-Page
open opservo-landing.html
```

No build step or dependencies required — it's a static HTML file.

## 👤 Author

**Harsh Gupta**
Design Intern, Softuvo Solutions
