# Streak Tracker

Simple single-file streak tracker hosted from `streak.html`.

## Local usage

Open `streak.html` in your browser:

- Double-click `streak.html`, or
- Serve locally: `npx serve .` then open the shown URL

## Deploy

### GitHub

This repo is at `github.com/dheerajmantha/streaktracker`.

### Vercel

This project uses `vercel.json` to route `/` to `streak.html`.

Steps:

1. Import the repo in Vercel (New Project → GitHub → `dheerajmantha/streaktracker`).
2. Framework preset: “Other”.
3. Root directory: repository root.
4. No build command; Output directory: `.`
5. Deploy.

Alternatively via CLI:

```bash
npm i -g vercel
vercel login
vercel --prod
```

Vercel will deploy static files and rewrite `/` to `streak.html`.


