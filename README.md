# daily-ai-podcast-feed

Public-facing site for the Daily AI Briefing podcast. Deployed by Netlify.

Auto-updated nightly by the [daily-ai-podcast](../daily-ai-podcast) pipeline, which prepends a new `<item>` to `feed.xml` and adds an HTML page to `episodes/`.

## Contents
- `feed.xml` — the podcast RSS feed (this is the URL submitted to Apple Podcasts)
- `cover.png` — show cover art (1500x1500)
- `index.html` — landing page
- `episodes/<date>.html` — per-episode show-notes pages

No build step. Netlify serves the repo root as a static site.
