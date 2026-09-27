# The Lagoon Legacy Project

The website for The Lagoon Legacy Project, supporting environmental education and community participation around the Indian River Lagoon.

[Visit the website](https://thelagoonlegacyproject.vercel.app)

## Website work

This repository contains the site's HTML, CSS, JavaScript, and Vercel API handlers. The implementation includes county chapter pages, a searchable team directory, contact forms, and an application form for new chapters.

- Shared page styling and navigation live in `assets/site.css` and `assets/site.js`.
- Team profiles and chapter membership are maintained in `assets/team-data.js` and rendered by the directory scripts.
- County pages have their own folders, including `brevard/`, `indianriver/`, and `stlucie/`.
- `api/contact.js` and `api/chapter-application.js` validate submitted fields and can forward submissions to configured webhooks.

The website is one part of the organization's work. This repository documents its implementation; environmental projects and chapter activities are described on the site.

## Website guide

[Website guide](WEBSITE_GUIDE.md) describes the application files and how to use them.

## Research papers

My separate computational biomechanics research is included here for readers looking for the rest of my work:

- [2023–24: Web visualization of blood flow (PDF)](papers/science-research-2023-24.pdf)
- [2024–25: Virtual reality and CFD (PDF)](papers/science-research-2024-25.pdf)
- [2025–26: Aneurysm detection and rupture modeling (PDF)](papers/science-research-2025-26.pdf)

