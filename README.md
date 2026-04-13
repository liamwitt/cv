# CV Website (Vercel-ready)

This repository contains a simple, fast static CV website ready to deploy on Vercel.

## Files

- `index.html` – main CV content and structure
- `styles.css` – responsive styling
- `script.js` – sets footer year dynamically
- `vercel.json` – Vercel config

## Customize your CV

1. Edit `index.html`:
   - Replace **Your Name**, title, summary, and contact links.
   - Update experience, education, skills, and project sections.
2. Optionally adjust colors and spacing in `styles.css`.

## Run locally

You can preview locally with any static server.

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy to Vercel

### Option A: Vercel Dashboard

1. Push this repo to GitHub/GitLab/Bitbucket.
2. In Vercel, click **Add New... → Project**.
3. Import your repository.
4. Keep defaults (Framework Preset: **Other**).
5. Click **Deploy**.

### Option B: Vercel CLI

```bash
npm i -g vercel
vercel
```

Follow prompts to deploy.
