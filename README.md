# Sakshi Dudani — Eleventy + Netlify CMS

This repository contains a small Eleventy (11ty) static site scaffold with Netlify CMS (git-backed) for editing content.

Quick start

1. Install dependencies
   npm install

2. Build locally
   npm run start

3. Connect this repository to Netlify
   - Create a new site from Git -> select this repo -> deploy
   - In Site settings -> Identity -> Enable Identity
   - In Identity settings -> Services -> Git Gateway -> enable
   - In Netlify CMS admin go to https://<your-site>.netlify.app/admin to login and edit content

Notes
- Netlify Identity + Git Gateway are required for CMS login that commits directly to the repo.
- Collections are stored under content/ and assets in src/assets/uploads.
