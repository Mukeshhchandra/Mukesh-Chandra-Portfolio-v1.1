# Mukesh Rudravaram — Portfolio

Personal portfolio for **Naga Mukesh Chandra Naidu Rudravaram**, a Data & BI Analyst in the San Francisco Bay Area (SQL, Python, Power BI across retail, supply chain and sales analytics).

A single, self-contained page: no framework, no build step, no tracking.

**Version 1.1**

## What's on the page

- **Hero** with a results card from my LTIMindtree analytics work
- **Work**: four projects, each opening a full case study in a glass panel
- **About**, **Journey** (experience and education timeline)
- **Skills**, each tagged by where it was used (production, project, academic), with a "Show evidence" switch
- **Resume** with "Quantified only" filter and **Save as PDF** (prints just the resume)
- **Contact**: email, LinkedIn, GitHub

## Design and build

- "Aurora glass" theme: frosted, translucent panels over slowly drifting colour light, with light and dark modes (circular reveal on theme switch, via the View Transitions API)
- Case studies use the native Popover API, so they open and close without JavaScript
- Respects `prefers-reduced-motion`; every section is readable with JavaScript off
- Layout checked at 1440, 1024, 768, 390 and 320 px wide with no horizontal overflow
- Plain HTML, CSS and JavaScript; fonts from Google Fonts (Sora, Inter, JetBrains Mono)

## Run it locally

Any static server works, for example:

```bash
python -m http.server 8765
```

Then open http://127.0.0.1:8765/index.html.

## Structure

```
index.html              the whole site: markup, styles and scripts
images/mukesh-studio.webp
```
