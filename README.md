# Schengen 90/180 tracker

The page (`index.html`) reads every trip from `trips.json`. To update the tracker, edit `trips.json` and commit. Anyone opening the page sees the change.

## Adding a trip

Open `trips.json` on GitHub, click the pencil icon, and add a line inside `"trips"`:

```json
{ "entry": "2026-12-20", "exit": "2027-03-10", "note": "Wedding trip", "planned": true }
```

- Dates are `YYYY-MM-DD`. Arrival and departure days both count.
- `"planned": true` for a future trip, `false` once it has happened.
- Put a comma between trips, and none after the last one.
- Count every Schengen country, not just Portugal.

Click **Commit changes**. The page updates within a minute or two. If it hasn't, hard-refresh (Cmd+Shift+R).

If the page shows "Could not read trips.json", the file has a typo, usually a missing or extra comma.

## Setup (once)

1. Create a repository and upload `index.html`, `trips.json` and this README.
2. Settings > Pages > Source: deploy from branch `main`, folder `/ (root)`.
3. Settings > Collaborators: invite your partner so he can edit too.
