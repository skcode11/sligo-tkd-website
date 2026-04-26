# Sligo ITF Taekwon-Do Club Website

This repository contains the official static website for **Sligo ITF Taekwon-Do Club**.
It is built with plain **HTML, CSS, and JavaScript** and is ready for GitHub Pages deployment from the repository root.

## Project Structure

- `index.html` - Main website content and section layout.
- `styles.css` - Site styles and responsive design.
- `script.js` - Mobile menu behavior and small UI enhancements.
- `assets/images/` - Optional image folder (currently no binary logo is tracked).
- `.nojekyll` - Disables Jekyll processing for GitHub Pages.

## How to Edit Text

1. Open `index.html`.
2. Find the section you want to update (`#home`, `#about`, `#classes`, etc.).
3. Edit headings, paragraph text, and links directly.
4. Commit and push changes.

## Logo Notes (Binary-free setup)

To avoid binary-file review issues, this project currently uses a text-based circular logo badge (`ITF`) in HTML/CSS.

If you later want to reintroduce an image logo, add a file under `assets/images/` and update the three logo spots in `index.html` (navbar, hero, footer).

## How to Edit the Timetable

1. Open `index.html`.
2. Search for:
   `<!-- EDIT TIMETABLE HERE -->`
3. Update rows inside the `<tbody>` of the timetable table.
4. Save, commit, and push.

## How to Update the Google Calendar Embed

1. Open `index.html`.
2. Find the `Season Calendar` section and the `<iframe>`.
3. Replace the `src` URL with your updated Google Calendar embed URL.
4. Save, commit, and push.

The calendar wrapper is responsive, so mobile layout should remain intact.

## Publish Updates to GitHub Pages

1. Push your changes to the `main` branch.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, set:
   - **Source**: Deploy from a branch
   - **Branch**: `main`
   - **Folder**: `/ (root)`
4. Save settings and wait for deployment.

Expected live URL:

`https://skcode11.github.io/sligo-tkd-website`
