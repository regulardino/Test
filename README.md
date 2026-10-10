# NHL Yesterday

A spoiler-free NHL tracker: open `index.html` in a browser to see which games
were played the day before. Only matchups (teams and venue) are shown, never
scores or results.

- Defaults to yesterday (in your local time zone); use the arrows or date
  picker to browse other days.
- Only finished games are listed; postponed or cancelled games are skipped.
- A "Coming up" section lists the next 7 days of games with start times in
  your local time zone. Today's games show only their start time, even once
  they've been played.
- Data comes from ESPN's public NHL scoreboard endpoint. Score and result
  fields are never read.

## Using it on an iPhone

The page is hosted with GitHub Pages. Open the Pages URL in Safari, tap
Share, then **Add to Home Screen**. It then opens full screen like an app
and jumps to the new "yesterday" each time you come back to it.

To turn hosting on: repo **Settings → Pages → Build and deployment →
Source: Deploy from a branch**, then pick this branch and `/ (root)`.
GitHub Pages on a private repo needs a paid GitHub plan; on a free plan
the repo has to be public first.
