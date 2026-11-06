# Overtime & Travel

Standalone, English-language HTML tool for extra hours worked (EHW) and travel time compensation.

## Download

Use the [Releases](https://github.com/Lunaticasylum67/Overtime-and-Travel/releases) page to download the HTML and one-page PDF guide. Alpha versions are marked as pre-releases. Open the HTML locally in your browser.

## Features

- Shared profile and optional signature stored in the browser.
- Separate EHW and travel modules; multiple missions and monthly EHW PDF pages.
- Manual minute entry, quarter-hour interval rounding before EHW coefficients.
- Generated PDFs with fillable approval fields.
- Silent anonymous update check at startup; GitHub icon indicates a successful manifest check.
- The form works offline. Profile and declaration data are never sent to GitHub.

## Publication

Versioned source HTML and PDF assets are stored under `releases/`. The publishing workflow verifies SHA-256 hashes before creating a tagged pre-release. `manifest.json` is updated only after the release and downloads have been verified.

Only blank distribution files belong in this repository. Filled HTML declarations, profile data and signatures must not be committed.
