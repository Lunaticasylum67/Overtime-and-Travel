# Overtime & Travel

Standalone, English-language HTML tool for extra hours worked (EHW) and travel time compensation.

## Download

Download the HTML and one-page PDF guide from [the latest stable release](https://github.com/Lunaticasylum67/Overtime-and-Travel/releases/latest). Open the HTML locally in your browser.

## Use

1. Complete your profile; a signature image is optional.
2. Add missions, or select Skip.
3. Save a travel declaration for each applicable mission.
4. Enter extra hours and click Save.
5. Check Declaration date and generate your PDF.

The header provides a version button, Changelog and Quick Guide. The version button checks for updates; stable versions follow stable releases, while Alpha versions may also follow Alpha releases. Updates are checked silently at startup. Modal dialogs close outside, with Escape or with the close button.

## Features

- Profile, preferences and optional signature are stored in the browser.
- Sections appear progressively; profiles and missions can be collapsed without clearing data.
- EHW supports multiple months, Session STR, lunch work and quarter-hour interval rounding before coefficients.
- PDFs contain monthly EHW pages and one page per saved travel declaration, with independent fillable approval fields.
- Fixed HH:MM inputs accept every minute; the picker offers quarter-hours.
- Save filled HTML retains declarations for later use.

## Privacy and offline operation

The form works offline. An anonymous request reads the public release manifest at startup and when the version button is clicked. Profile, signature and declaration data are never sent to GitHub.

Only blank distribution files belong in this repository. Never commit filled HTML declarations, profile data or signatures. Browser storage may vary between local filenames, browsers and devices.

## History and publication

See [CHANGELOG.md](CHANGELOG.md) for the history from v1.0; Alpha changes are grouped by their target stable version. Versioned distribution files are under `releases/`. A temporary publication workflow verifies SHA-256 hashes and tags the exact release commit. `manifest.json` is updated only after the release assets and Drive delivery have been verified.
