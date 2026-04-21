# Daily report public site

This folder is the static publish root for the A-share daily report.

## Expected file
- `index.html` — public daily report page

## Cloudflare Pages suggestion
- Project root / upload root: this `public/` folder
- Build command: none
- Output directory: `public`

Stable public URL:
- https://daily-a-share-report-public.jiang1008yan.workers.dev/

Reuse this public URL and let the daily cron send that URL to WeChat.
