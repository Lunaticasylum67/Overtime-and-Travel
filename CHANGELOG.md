# Changelog

Alpha changes are consolidated under their target stable version.

## v1.5.2 — 2026-11-07

- Fix Session STR to the Standard day category.
- Recall the latest saved justification for each activity.
- Keep different activities on the same day on separate saved and PDF rows.
- Align the Quick Guide version with v1.5.2.

## v1.5 — 2026-11-06

- Add Session STR with automatic Strasbourg prefilling and no duplicate activity.
- Apply the Session STR timetable and restrict this activity to Monday–Thursday.
- Add optional lunch work with editable From and To times.
- Support entries across multiple months and missions spanning month boundaries.
- Generate monthly EHW pages with automatic continuation after 21 lines.
- Support multiple travel declarations with one PDF page per mission.
- Select PDF content automatically and display the actual page count.
- Offer only export options matching the saved declarations.
- Add explicit travel saving with a recap and Edit, Update, Cancel and Remove actions.
- Standardise Save and Update buttons with clear enabled and disabled states.
- Highlight invalid fields and suppress misleading credit previews.
- Separate entry forms visually from saved entries.
- Restore fixed HH:MM entry with independent hours and minutes.
- Offer quarter-hour selections while allowing manual minute entry.
- Round interval starts down and ends up before applying coefficients.
- Preserve entered times and show the intervals used for calculations.
- Reveal sections progressively as the profile and declarations are completed.
- Collapse completed profiles while keeping them editable.
- Move Declaration date to Declaration summary.
- Show the signature thumbnail or SIGNATURE MISSING in collapsed profiles.
- Add Skip, Collapse and Edit missions controls without clearing data.
- Check for updates silently at startup and preserve offline operation.
- Use the version button for update checks and display the update status on hover.
- Show newer versions in a download dialog and dismiss up-to-date confirmations after three seconds.
- Label update notes with Changes and close the dialog when downloading.
- Add equally sized version, Changelog and Quick Guide buttons in a right-hand stack.
- Open Changelog and Quick Guide in dialogs that close outside, with Escape or with the close button.
- Include a direct PDF link in Quick Guide and present travel before EHW in its instructions.
- Publish versioned HTML and PDF downloads on GitHub and Drive.
- Maintain a release manifest and a changelog grouped by stable version.

## v1.4

- Simplify Activities and missions into a mission-only section.
- Keep Regular work directly available in EHW.
- Add an explanatory confirmation before forgetting saved browser data.
- Start PDF content at NONE and select it automatically as declarations are entered.
- Preserve manual PDF content choices while applicable.
- Keep Standard as the default Friday category.
- Update the one-page Quick Guide.

## v1.3

- Remember all profile fields, declaration date, preferences and signature in the browser.
- Show excluded normal hours with a smaller working-time and lunch breakdown.
- Leave zero-value Type 1, Type 2 and Type 3 PDF cells blank.

## v1.2

- Merge same-date EHW entries using the earliest start and latest end.
- Preserve activities and justifications when merging entries.
- Recalculate totals and PDF output after merging.

## v1.1

- Exclude normal working hours automatically from entered shifts.
- Support Standard Friday and manually selected Long Friday schedules.
- Apply EHW coefficients according to time and day category.
- Distinguish public holidays from office closing days.
- Add live extra-hours and compensated-credit totals.
- Highlight missing or invalid EHW input.

## v1.0

- Combine EHW and travel time compensation in one offline HTML file.
- Keep EHW and travel calculations in independent modules.
- Share staff identity and an optional signature image between declarations.
- Support multiple activities and missions within an EHW statement.
- Generate EHW, travel or combined PDFs with fillable approval fields.
- Save filled HTML copies to resume declarations later.
