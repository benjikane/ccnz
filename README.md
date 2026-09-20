# Turntable

Turntable is an original, lightweight competition workspace for speedcubing leagues. It is intentionally independently branded and designed, while covering the operational workflows needed to run competitions.

## Included in this starter

- Dashboard with active competition and activity summaries
- Competition creation flow
- Workspace member and role overview
- Live results leaderboard
- Judge scorecard entry workflow
- Scramble generation and locking view
- Workspace settings with role preferences
- Responsive layout for desktop and mobile

## Run locally

This is a dependency-free static app. Open `index.html` directly in a browser, or serve the folder with any static server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Next production steps

The UI currently uses seeded demo data and local interactions. A production implementation should add authentication, a persistent database, server-side role enforcement, WCA-compliant scramble generation, audit logs, and real-time result updates.
