# Top 10 Projects by Connect Shiksha – Student Guide

Welcome! This repository contains 10 modern, responsive website projects built with HTML, Tailwind CSS (CDN), and vanilla JavaScript, plus a special Portfolio card on the landing page.

This guide helps you run, explore, customize, and deploy the projects.

## Live Demo

Deployed site: https://connect-shiksha-projects.netlify.app

---

## 1) Quick Start

- Option A: Double-click any `index.html` to open in your browser.
- Option B (Recommended): Use VS Code + Live Server
  1. Open the folder in VS Code.
  2. Install the "Live Server" extension.
  3. Right-click `index.html` at the root (landing page) → "Open with Live Server".
     - Note: Live Server is configured to use port 5503 in `.vscode/settings.json`.

- Landing page: `index.html` (links to all projects)
- Open any project: go into its folder → open `index.html` (e.g., `Coffee Store/index.html`)

---

## 2) What’s Included

- Landing page: `index.html` with cards for 10 projects and one "SPECIAL" Portfolio card.
- Projects (each is a self-contained single HTML file):
  - Medical Store / Pharmacy
  - Coffee Shop
  - Gym Website
  - Kirana Store / Grocery
  - School Website
  - College Website
  - Restaurant Website
  - Real Estate Agency
  - Travel Agency
  - Beauty Salon / Spa

All pages use:
- Tailwind CSS CDN: `https://cdn.tailwindcss.com`
- Font Awesome (icons): `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css`
- Vanilla JS inside a `<script>` tag at the bottom of the page

---

## 3) Landing Page (index.html)

The landing page shows:
- A centered hero section with Connect Shiksha branding and logo
- A grid of cards linking to each project (View) and the GitHub code (Code)
- A highlighted "SPECIAL" Portfolio card (you can point this to your own portfolio)

Key places to customize:
- Branding logo and link (header & footer):
  - Logo URL: `https://connectshiksha.com/assets/mainlogo-BVXvkrYL.png`
  - Brand link: `https://connectshiksha.com`
- Contact details (footer):
  - Phone: `9131782103 , 7748893097`
  - Email: `connectshikshaofficial@gmail.com`
  - Address: `In Front of Sindhu Bhavan, Gondia Road, Balaghat (M.P)`
- Portfolio card (top of grid):
  - Update the View link to your portfolio file (currently `/Portfolio/index.html`)
  - Update the Code link to your portfolio’s repository

Adding/Editing a project card:
1. Duplicate an existing card block inside the grid.
2. Change the title, description, View link (folder `/Your Project/index.html`), and Code link (GitHub path).

Tip: Folder names with spaces work in the browser; GitHub URLs auto-encode spaces as `%20`.

---

## 4) Editing Any Project

Open the project’s `index.html`. You’ll find:
- Tailwind utility classes for layout and styling
- Font Awesome icons
- A small JS section at the bottom handling interactions (smooth scroll, mobile menu, alerts, etc.)

Common customizations:
- Colors: Change Tailwind classes like `bg-red-600`, `text-blue-600`, etc.
- Sections: Add or remove `<section>` blocks (e.g., Gallery, Contact, Pricing)
- Icons: Replace `<i class="fas fa-...">` with any from Font Awesome 6
- Copy: Edit headings, descriptions, addresses, phone numbers, and timings

If styles don’t load:
- Ensure you’re connected to the internet (Tailwind and icons are from a CDN).
- Confirm the `<script src="https://cdn.tailwindcss.com"></script>` tag exists in `<head>`.

---

## 5) Creating a New Project

1. Create a folder at the repo root (e.g., `New Project`).
2. Create `index.html` inside it (you can copy one of the existing project files as a template).
3. Add a new card to the landing page grid linking to your new folder.
4. Test via Live Server or by opening the file in your browser.

---

## 6) Deployment

### GitHub Pages (quick and free)
1. Push this repository to GitHub.
2. On GitHub, go to Settings → Pages.
3. Under "Build and deployment", select "Deploy from a branch".
4. Choose `main` (or `master`) and `/ (root)`.
5. Save. After a minute, Pages will give you a public URL.

- The landing page (`index.html`) becomes the homepage.
- Project folders are accessible under the same domain, e.g., `https://<user>.github.io/<repo>/Coffee%20Store/`.

### Netlify / Vercel (drag-and-drop)
- Drag the whole folder into Netlify / Vercel.
- Set the site root to the repository root (so `index.html` at root is used).

---

## 7) Troubleshooting

- Blank styles or icons:
  - Check internet connection (CDN-based Tailwind + Font Awesome)
  - Ensure the script/link tags in `<head>` are intact
- Mobile menu not opening:
  - Verify the JS at the bottom of the file is present and no console errors
- Links not working:
  - Confirm the path (respect folder names and capitalization)
- GitHub Pages 404 on subpages:
  - Refresh the main page then navigate again; ensure folder names match the card links

---

## 8) Contributing & Learning Tips

- Practice Tailwind by tweaking spacing (`p-6`, `mt-4`), colors (`bg-…`), and typography (`text-…`).
- Replace emoji icons with Font Awesome where needed.
- Keep sections modular so you can reuse across projects.
- Commit frequently with messages describing your changes.

---

## 9) Credits & Contact

- Brand: Connect Shiksha – Coding Class Balaghat
- Website: https://connectshiksha.com
- Email: connectshikshaofficial@gmail.com
- Phone: 9131782103 , 7748893097
- Address: In Front of Sindhu Bhavan, Gondia Road, Balaghat (M.P)
- Repository: https://github.com/kuldeepkaware123/Projects-By-ConnectShiksha.git

Happy building!
