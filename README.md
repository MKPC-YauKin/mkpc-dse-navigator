# MKPC DSE Navigator

A standalone HKDSE guidance web app for mainland students and parents. The whole app is one self-contained `index.html` — no build step, no dependencies, no tracking.

## What it covers

- HKDSE structure and grading, including **332A / 332A33** and Citizenship and Social Development
- Elective combinations and cross-disciplinary directions
- Official links to **12 Hong Kong institutions**
- A rules-based direction matcher using electives, abilities, learning style and region
- Role-model profiles (Hong Kong and mainland)
- Mainland-student practical notes and a Non-JUPAS timeline
- A **best-5 grade calculator** with a 332A33 check
- Sources, update date and disclaimer

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deploy

Enable GitHub Pages under **Settings → Pages → Deploy from a branch → `main` / `/ (root)`**.

The app will be served at <https://mkpc-yaukin.github.io/mkpc-dse-navigator/>.

## Data

Compiled from HKEAA, JUPAS, EDB and institutional websites; links checked on 29 October 2026. The "2,100+ institutions" figure is as of March 2026.

Requirements, fees and deadlines change every year. Always confirm with the official HKEAA and university websites.

## Disclaimer

This is an exploration tool, not an official admissions guide, and it does not predict admission outcomes.
