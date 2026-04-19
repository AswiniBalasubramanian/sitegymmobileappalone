# SITE2GYM Mobile App (Standalone)

Interactive high-fidelity prototype of the SITE2GYM fitness app.

## Run

Open `app.html` directly in a browser, or serve it:

```bash
npx serve -l 5199 .
```

Then open http://localhost:5199/app.html.

## What's inside

A 1360×768 dark stage with a single iPhone frame (scaled 0.82) running the full interactive React app.

- **6 screens** — Onboarding · Home · Booking · Gym Access · Membership · Profile (stats/badges/leaderboard)
- **Gamification** — streak · XP (`+10` enter, `+50` book, `+40–80` quick-book) · HSR leaderboard
- **Design** — dark theme + neon lime (`#D0FF00`) + cyan (`#00F0FF`) accents, Inter Tight + JetBrains Mono
- **Motion** — page-fade 280ms, scan loop 1.5s, tap scale 0.97, toast drop-in 300ms

Single HTML file. React 18 via UMD + Babel-standalone. Zero dependencies to install.
