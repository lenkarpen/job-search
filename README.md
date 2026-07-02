# Olena · Job Search App

A personal LinkedIn job search tool — pulls fresh Dublin IT jobs, scores them by fit, and generates tailored cover letters as PDFs.

## Live

**https://lenkarpen.github.io/job-search/**

## Features

- 🔍 Real-time LinkedIn job search via JSearch API
- 🟢 **Good match** — Dublin 1–8, likely €35k+, strong skills overlap
- 🟡 **Loose match** — worth a look but outside ideal criteria
- ⏱️ Timeframe filter: 24h / 3 days / 7 days
- ✉️ One-click cover letter generator, tailored to role type
- ⬇️ Download cover letter as PDF (with references)
- 🔐 API key stored in your browser only — never sent anywhere else

## Setup

1. Go to [rapidapi.com/jsearch](https://rapidapi.com/letscrape-6bRBa3QguO5/api/jsearch)
2. Sign up free → subscribe to the Basic (free) plan → copy your API key
3. Open the app, paste the key in the **RapidAPI Key** field at the top
4. Hit Search — key is saved in `localStorage`, no re-entry needed

Free tier: ~200 searches/month.

## GitHub Pages

To enable the live URL above:
1. Go to repo **Settings → Pages**
2. Source: **Deploy from a branch** → branch `main` → folder `/` (root)
3. Save — live in ~60 seconds
