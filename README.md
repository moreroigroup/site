# Morero Intelligence Group — Website

This repository contains the static website for **Morero Intelligence Group (Pty) Ltd**.  
It’s a single-page HTML site (Tailwind via CDN, no build step) with a contact form wired to **Formspree**.

## Files
- `index.html` – main site
- `morero-logo.png` – logo in navbar and social cards
- `favicon.png` – browser tab icon
- `README.md` – this guide

## Contact Form (Formspree)
Already configured to submit to:
```
https://formspree.io/f/mkgvlllw
```
To change later, edit `index.html` and update the form’s `action` URL.

## Local Preview
Double‑click `index.html` to open in your browser.

## Deploy to GitHub Pages
1. Create a new GitHub repository (e.g., `morero-site`).  
2. Upload these files (drag‑drop or push via git).  
3. Open **Settings → Pages** in the repo:  
   - **Source:** *Deploy from a branch*  
   - **Branch:** `main` and `/ (root)` → **Save**  
4. Your site will be live at:  
   `https://<your-username>.github.io/<repo-name>`

### Updating
- Edit `index.html` and push — Pages redeploys automatically.
- Replace `morero-logo.png` to refresh branding (keep filename).

## Optional
- Add a `CNAME` file with your custom domain (e.g., `www.morero.group`).
- Add OpenGraph/Twitter meta tags and analytics in `<head>`.
- Hook the form to a CRM/webhook in addition to Formspree.

— Happy shipping!
