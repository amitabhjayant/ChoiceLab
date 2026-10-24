# ChoiceLab — The Human Agency Gym

**Tagline:** Your AI knows you. But you define yourself.

A responsive, interactive concept prototype for **Flipkart APM ’29 — Prompt 1**. In a hypothetical 2040 world of personal AI agents, ChoiceLab helps users reflect on consequential decisions before viewing AI suggestions.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in any modern browser.
3. Navigate between **Overview**, **Decision Dojo**, **Values Vault**, and **Agency Mirror**.

No installation, API key, server, or internet connection is required. Alternatively, enable **GitHub Pages** under repository **Settings → Pages → Deploy from a branch → main / (root)**.

## Prototype features

- **Decision Dojo:** Explore two fictional job offers, record your priorities and reasoning, reveal a transparent simulated recommendation, and save a final reflection.
- **Values Vault:** Set four personal priority sliders and a free-text values statement.
- **Agency Mirror:** View saved reflection history and descriptive activity counts; delete history.
- **Local persistence:** Data is stored in browser `localStorage`.
- **Responsive interface:** Works on desktop and mobile widths.

## Important limitations

- The recommendation is **not real AI**: it is a deterministic mapping from the user's selected priority to one of two fictional job offers.
- The Values Vault is **not encrypted** and does not protect against someone with access to the same browser profile.
- No real AI agents are connected; the prototype does not intercept recommendations or transactions.
- Metrics are descriptive, not evidence of improved decision-making skill or long-term human agency.
- Career scenarios are illustrative, not professional career advice.

## Files

```
index.html
css/style.css
js/app.js
README.md
```

## Product hypothesis

A lightweight reflection step before AI advice may help people articulate priorities and understand trade-offs in consequential decisions, without interrupting routine automation. This hypothesis requires user research and controlled testing.

## Submission

This repository is an HTML/CSS/JavaScript-only prototype. Zip the files if submitting the downloadable prototype option required by the case brief. The two-page written case analysis is a separate deliverable.
