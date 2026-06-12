# Academic Dashboard

Interactive analytics dashboard for 8 semesters of B.Tech CSE (AI specialization) at Medicaps University - built as a single self-contained HTML file.

**Live:** [academic-dashboard-nu.vercel.app](https://academic-dashboard-nu.vercel.app)

## What it shows

- GPA trajectory - SGPA and CGPA across all 8 semesters
- Grade distribution and an outstanding-grades count
- Theory vs practical performance, credit-weighted
- Subject-level grade points as a combined heatmap
- Domain strength bars and radar (AI/ML, programming, core CS, theory)
- Per-semester course drill-down via tab selector
- SGPA vs credit-load bubble chart

## How it is built

- One HTML file: markup, styling, data, and charts together - no build step
- [Plotly.js](https://plotly.com/javascript/) (CDN) for the 8 charts, with the modebar hidden and responsive sizing
- Hand-written CSS: bento grid, mesh gradients, SVG noise texture, animated KPI counters, staggered fade-ups
- Honors `prefers-reduced-motion`

## Run locally

Open `index.html` in a browser. That is all.
