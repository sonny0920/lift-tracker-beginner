# Lift Tracker (Beginner) — The Logbook

A self-contained workout and nutrition tracker for a beginner-friendly 4-day split, with a 26-week progressive plan. Installable as an offline PWA.

**Live app:** https://sonny0920.github.io/lift-tracker-beginner/

- **Train** — log weight/reps per set, 26-week periodized plan (Base → Volume → Strength → Intensity → Peak, deloads every 6th week), editable exercises, rest timer, plate calculator, auto-progression, PR tracking.
- **Progress** — monthly charts per lift (top weight / est. 1RM / volume), bodyweight trend, personal-records list.
- **Fuel** — bodyweight-driven protein & calorie targets, food source lists, and eating tips.
- **Storage** — device `localStorage` with file-based backup/restore and backup reminders.

Main app is one file: [`index.html`](index.html), plus PWA assets (`manifest.json`, `sw.js`, icons). No build step, no dependencies.

## Run locally

Serve the folder (a plain file:// open works too, but the service worker needs a server):

```sh
python -m http.server 8000
# then visit http://localhost:8000
```
