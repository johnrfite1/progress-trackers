# Progress Tracker

A single-page, static 8-week reset tracker with a timeline, milestone phases, and live progress stats. Designed to run locally or on GitHub Pages with no build step.

## What's Inside

- `index.html`: Self-contained HTML/CSS/JS file.
- Dynamic progress stats (current day, days left, weeks complete).
- Animated progress bar, milestone timeline, and phase callouts.
- Completion banner when the reset period ends.

## Usage

1. Open `index.html` in a browser.
2. The tracker auto-updates every minute based on the configured dates.

## Customize Dates

Edit these constants near the top of the `<script>` block:

```js
const START_DATE = new Date('2026-01-12T00:00:00');
const END_DATE = new Date('2026-03-09T23:59:59');
const TOTAL_DAYS = 56;
```

## Customize Milestones

Update the `MILESTONES` array in `index.html` to change phase names, day ranges, or bullet points.

## Deploy

This is a static page. Host it anywhere:

- GitHub Pages
- Netlify
- Vercel
- Any static file server

