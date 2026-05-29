# World One Enterprise — Website

A single self-contained static site (`index.html`) plus the AI Data Centre brochure PDF.

## Files
- `index.html` — the entire website (HTML/CSS/JS in one file)
- `Astra-Cyber-City-World-Class-Consortium-Driving-Indias-AI-Future.pdf` — downloads when you click "Download PDF" on the AI Data Centre brochure
- `.nojekyll` — tells GitHub Pages to serve files as-is

> Keep `index.html` and the PDF in the SAME folder, or the brochure download link will break.

## View locally
Just double-click `index.html` (needs an internet connection, since the hero images and Tailwind/icons load from the web).

## Option A — GitHub Pages (free)
1. Create a new repository on github.com (e.g. `worldone-website`).
2. Upload all files in this folder (Add file -> Upload files -> drag them in -> Commit).
3. Go to the repo's **Settings -> Pages**.
4. Under "Build and deployment", set **Source: Deploy from a branch**, **Branch: main / (root)**, Save.
5. Wait ~1 minute. Your site will be live at:
   `https://<your-username>.github.io/worldone-website/`

## Option B — Netlify / Vercel / Cloudflare Pages (free, drag-and-drop)
- Netlify: go to app.netlify.com -> "Add new site" -> "Deploy manually" -> drag this whole folder in. Done.
- Vercel / Cloudflare Pages work the same way (import the folder or connect the GitHub repo).

## Notes
- The contact form shows a confirmation message but does not send email (a static site has no backend). To make it send, connect a form service like Formspree, Netlify Forms, or your own endpoint.
- Hero images currently load from the original hosted URLs. If you want a fully offline site, the images can be downloaded and bundled too.
