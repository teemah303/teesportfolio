# Teeshub — Responsive Multi-page Portfolio

A responsive, accessible, multi-page portfolio template built with HTML5, CSS, and vanilla JavaScript. Ideal for showcasing projects, services, and collecting contact inquiries.

## Features
- Semantic HTML5 structure
- Responsive layout (mobile-first)
- Interactive elements: mobile nav, modal project details, contact form validation
- Clean folder structure and well-commented files
- Easy to deploy (GitHub Pages / Netlify / Vercel)

## Project structure
my-portfolio/
├─ index.html
├─ about.html
├─ services.html
├─ contact.html
├─ css/styles.css
├─ js/main.js
├─ images/
└─ README.md

## Development
1. Clone the repo
2. Edit files in `index.html`, `about.html`, etc.
3. Add images to `images/`
4. Test locally: open `index.html` in a browser or use a simple static server:
   - `npx http-server` or `python -m http.server 8000`

## Deployment

### GitHub Pages (static)
1. Create a GitHub repository and push the project.
2. In GitHub, go to **Settings → Pages** and select the branch (e.g. `main`) and root directory.
3. Save — your site will be published at `https://<username>.github.io/<repo>/` in a few minutes.

### Netlify (drag & drop)
1. Zip your project or link GitHub repo.
2. Drag & drop to Netlify or connect repository and follow the deploy steps.
3. Netlify gives a live URL and supports forms and redirect rules.

### Vercel
1. Import the repo into Vercel.
2. Configure build (none for static) and deploy.
3. Vercel gives a live URL and automatic preview deployments.

## Notes & next steps
- Replace placeholder images and text with your real content.
- For production contact forms, connect to an email/API (Formspree, Netlify Forms, or build a serverless function).
- Add analytics and SEO meta tags.
- Optionally convert to React/Next.js or add Supabase backend for user data and admin.

## License
MIT
