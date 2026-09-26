# Lana Othman Portfolio — Vercel Base

This is the new portfolio foundation.

## Structure
- `index.html` — profile, experience, skills, and background
- `work/branding.html` — 3 branding projects
- `work/social-media.html` — social media index
- `work/social/page-01.html` through `page-06.html` — 6 social pages, 6 image slots each
- `work/packaging.html` — 2 packaging projects
- `work/print.html` — 7 print design works
- `work/logo.html` — logo selection
- `work/art.html` — 10 art slots
- `assets/images/` — put portfolio images here

## Design system
- Base: black + white
- Accent colors are isolated per category through CSS variables and can be changed later.
- The CSS first tries to use `Acumin Variable Concept` locally. If it is not installed, it falls back to Inter.
- No Campaign section is included.

## Vercel
This is a static site and can be deployed directly to Vercel by importing the folder/repository.
