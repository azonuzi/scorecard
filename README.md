# SDLTA Scorecard

A lightweight, mobile-first scorecard for Sheffield and District LTA doubles matches.

## What it does

- Records the league, divisions 1–6, and the home and away clubs from the SDLTA club directory.
- Supports both SDLTA match formats:
  - 2 pairs per team: 4 players each and 4 doubles matches.
  - 3 pairs per team: 6 players each and 9 doubles matches.
- Captures two sets and, when the sets are split, a 10-point championship tie-break.
- Totals matches, sets, and games. A tied match is decided by matches won, then sets, then games; a win earns two league points and a fully tied match earns one each.
- Records each player once, then offers them in a selection list for every match.
- Saves every edit automatically in the browser on the device being used, even after the browser is closed.
- Lets a captain download a JSON backup and restore it later on this or another device.
- Can copy a plain-text result summary.

## Publish it with GitHub Pages

This repository includes a GitHub Actions deployment workflow. In the repository's **Settings → Pages**, select **GitHub Actions** as the build and deployment source. After merging to `main`, the site will publish at:

`https://azonuzi.github.io/scorecard/`