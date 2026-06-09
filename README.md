# Cozygames Privacy Policies

Static GitHub Pages site that hosts privacy policies for Cozygames indie games.

Live at: https://khizerarshad.github.io/cozygames-policies/

## Pages

- [Top Bins privacy policy](./top-bins/privacy.html) — `https://khizerarshad.github.io/cozygames-policies/top-bins/privacy.html`

## Updating a policy

1. Edit the relevant `<game>/privacy.html` file
2. Bump the "Last updated" date
3. Commit + push to `main` — GitHub Pages redeploys in ~1 minute
4. If material changes: re-link the URL in the Play Store / App Store listings (only required if the URL changes)

## Adding a new game

1. `mkdir <game-slug> && cp top-bins/privacy.html <game-slug>/privacy.html`
2. Edit to reflect the new game's data practices
3. Add entry to `index.html`
4. Commit + push

## Why a separate repo

Game source repos are private (commercial). GitHub Pages on the free tier requires the serving repo to be public. This repo hosts ONLY the static HTML policies — no game code.
