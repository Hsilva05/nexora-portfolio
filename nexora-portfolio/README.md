# Nexora Web Studio — Starter Portfolio

An original, responsive HTML/CSS/JS portfolio built as a **fictional agency demonstration**. No real client projects, awards, metrics or testimonials are claimed.

## Preview locally
Open `index.html` in a modern browser. Internet is needed to load Google Fonts; system fonts will work offline.

## Customize BEFORE publishing
1. Replace **Nexora Web Studio** with your own checked, legally available studio name.
2. Replace `hello@example.com` in `index.html` (including `mailto:`).
3. Adjust copy, country focus and service descriptions to reflect what you actually offer.
4. Replace Fieldwork and Apex concept mockups with your own real examples over time.
5. Add a privacy notice and business identification as appropriate before operating commercially or collecting personal data.
6. Do not claim example projects are clients.

## Publish for free via Cloudflare Pages
1. Create a GitHub repository named `nexora-portfolio`.
2. Upload `index.html`, `styles.css` and `script.js` to the repository root.
3. In Cloudflare dashboard, go to Workers & Pages > Create > Pages > Connect to Git.
4. Choose the repository and branch `main`.
5. Choose no framework / static HTML. If a build command is required, use `exit 0`; use `/` (project root) for output directory.
6. Deploy, then open your new `<project>.pages.dev` link.
7. Later, attach a purchased domain using Cloudflare Pages > Custom domains.

Cloudflare has been promoting Workers for new projects. This straightforward static project can also be deployed as static assets with Workers; choose Pages when its integration is offered in your dashboard.

## Limitations
Contact button is a `mailto:` link — it opens a visitor's mail application and is not a server-side contact form. No analytics, booking system or backend has been installed. Test all content and devices before publishing.
