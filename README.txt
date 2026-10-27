Arquebus Intelligence homepage redesign preview
================================================

Static HTML/CSS site. No build step or framework required.

Files:
- index.html: concise homepage
- styles.css: shared styling and responsive layout
- services/index.html: service details
- how-we-work/index.html: process and measurement approach
- who-we-help/index.html: ICP, qualification and prospecting priorities
- about/index.html: founder and philosophy
- strategic-visibility-review/index.html: conversion page and enquiry form
- robots.txt, sitemap.xml, site.webmanifest
- Existing brand assets and favicons

Deployment:
Upload these files to a branch/repository and deploy as a static site on Vercel.
All routes use directory index.html files so clean trailing-slash URLs resolve on static hosting.

Important form note:
The enquiry form retains the existing Google Apps Script endpoint and sends the same core fields (name, email, company, website, type). The endpoint is called with mode:no-cors, which means the browser cannot verify the server-side response. Before production release, test a real submission and confirm the data arrives in the expected destination. Do not treat a browser-side success state as proof of server-side recording until that test passes.

The sitemap lastmod dates are set to 2026-10-27 for this preview; update them to the actual deployment/revision date before publishing if needed.
