# Mike Coen personal website

A responsive, dependency-free static portfolio built with HTML, CSS, JavaScript, and a canvas network visualization. No backend, tracking, external fonts, or third-party scripts.

## Preview
Run `npm run dev`, then open http://127.0.0.1:4173.

## Build
Run `npm run build`. Upload the contents of `dist/` to the website's document root on Hostinger after approval. No Node.js runtime is required on the hosting server. Source repository: https://github.com/mcoen/mcoen.github.io. Hostinger deployment is a separate step.

## Content
Adapted from https://michaelcoen.com on November 15, 2026. Original career history and education preserved, with Veritext added from owner-provided context and TeleTracking's end year set to 2026. Skills copy is newly written from that background; the original Skills section was empty. Footer uses the current year. Contact uses public email and phone. LinkedIn (https://www.linkedin.com/in/michaelcoen) and GitHub (https://github.com/mcoen) appear in the hero and contact section. Other original social icons were placeholders and are omitted. Contact actions open the visitor's email or telephone application; no form submission service is configured.

The resume link points to the existing https://www.michaelcoen.com/resumes/MichaelCoenResume.pdf. Preserve that Hostinger path during deployment. The PDF is excluded from the public source repository. The design uses Mike as the preferred name. Original site lists freelance availability; this redesign does not assert current availability given the CTO role.

## Editing
Content: index.html. Design and responsive breakpoints: styles.css. Navigation and reduced-motion-aware animation: app.js. Downloadable resume: existing /resumes/MichaelCoenResume.pdf on Hostinger.

## Launch checklist
Review copy, career dates, and resume; select the personal GitHub repository; confirm Hostinger site/document root; back up current WordPress site; deploy static files and verify domain/SSL, download, links, and mobile display. Existing WordPress paths should be reviewed for redirects before replacement. None of those hosting changes has been performed.

## Design revision
Sky-blue accents (#8cc4ff), cool graphite backgrounds, larger navigation (16px), larger supporting labels (12–13px), and 16px body copy. Network animation, contact panel, buttons, and favicon use the blue palette.
