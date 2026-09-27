# Schengen 90/180 tracker

Tracks his days in Schengen. Trips are saved on each device separately: what he adds stays on his phone, what you add stays on yours.

## Files
- `index.html`: the tracker
- `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `favicon.png`: the app icon
- `manifest.webmanifest`: lets phones open it like an app

## Setup (once)
1. On github.com, create a new **Public** repository (for example `schengen-tracker`).
2. Upload all the files above. Commit.
3. **Settings > Pages**: Source **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. After a minute or two the link appears at the top of that page, in the form `https://yourusername.github.io/schengen-tracker/`.
5. Send him the link.

## Adding it to the home screen (iPhone)
1. Open the link in **Safari**.
2. Tap Share > **Add to Home Screen** > Add.
3. Always open it from the home-screen icon. Trips added in the icon version and in normal Safari are stored separately.

The first time it opens, his two summer trips are already loaded.

## Backups
Trips live only on the phone. Clearing Safari data, resetting or replacing the phone, or deleting the home-screen icon wipes them. Tap **Download backup** at the bottom now and then, and save the file to email or iCloud Drive. **Restore from backup** brings them back on any device.

## Updating the app
Replace `index.html` in the repo. Saved trips on each phone are not affected.
