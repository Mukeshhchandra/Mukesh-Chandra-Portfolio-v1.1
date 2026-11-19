# Changelog

## v1.1 — November 2026

First published version of the redesigned portfolio.

### Design
- New "aurora glass" theme: frosted, translucent panels over slowly drifting teal, sky and amber light
- Light and dark modes, with a circular reveal when switching
- Sora headings and Inter body text
- Equal content edges across the nav, every section and the footer at all widths

### Landing page
- Headline-led hero with profile photo, availability badge and two clear actions
- Results card with the three headline outcomes from LTIMindtree (45+ stores, ~50% less weekly reporting effort, ~35% faster financial reporting)

### Sections
- **Work** moved directly after the hero; four project cards, each opening a full case study in a native popover panel
- **About** reduced to a photo, a short bio and four facts
- **Journey** timeline of experience and education
- **Skills** shown as pills tagged by evidence (production, project, academic), with filters and a "Show evidence" switch
- **Resume** shows the Data / BI version, with "Quantified only" and "Save as PDF" (prints just the resume)
- **Contact** with email, LinkedIn and GitHub buttons and a copy-email control

### Content fixes
- Availability updated to "Available now"
- Experience stated accurately as 2 years 7 months
- First-person voice throughout; internal notes removed from the page
- Claims without evidence removed (React, the "Role fit" scores and gaps)
- Phone number removed from the public page; long LinkedIn address replaced by a short link

### Behaviour and quality
- Native scrolling, no preloader, no custom cursor
- One-time entrance on load and gentle section reveals; everything rests under `prefers-reduced-motion`
- Mobile menu, skip link, visible focus states, labelled controls
- Page title, description, favicon and link-preview tags
- Checked with no horizontal overflow at 1440, 1024, 768, 390 and 320 px
