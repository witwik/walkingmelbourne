# Walking Melbourne

A lightweight, mobile-friendly guide to exploring Melbourne on foot, with a Camino Companion journal.

## What is included

- Curated walking ideas across Melbourne and regional Victoria
- Search, themes, regions, favourite walks and random discovery
- Links to maps and public transport planning
- Camino Companion with cumulative distance entries, progress and CSV export
- Saved walks, visited walks and Camino entries stored in the current browser via localStorage

## Run locally

Open `index.html` in a browser, or serve this directory with a simple static server:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Publish with Netlify

1. Create a GitHub repository and upload these files to its root.
2. In Netlify, choose **Add new project → Import an existing project → GitHub**.
3. Select the GitHub repository. No build command is required. Publish directory is `.`.
4. Deploy. Netlify will publish `index.html` at the root of the site.

The `netlify.toml` already defines the publish directory and basic HTTP security headers.

## Current limitations

- Data is stored **only in the browser you use**. It does not sync across devices, Netlify, GitHub or ChatGPT. Export Camino CSV entries regularly.
- Weather, transport availability and local route conditions are not live-checked.
- Distance ranges are suggestions rather than surveyed GPS tracks.
- Camino progress starts with the source app's initial entry for 30 October 2026 (9 km) and uses a 774 km target. Adjust these in the app if your current journey differs.
- This is the preserved 30 October 2026 app version; no new backend or screenshot integration was added during packaging.