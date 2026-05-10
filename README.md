# PCB Atlas Feedback

Public feedback, bug reports, feature requests, and documentation issues for PCB Atlas.

PCB Atlas is a local-first PCB review workspace for importing board data, browsing `2D / 3D / Data`, inspecting objects, managing revisions, and exporting review artifacts. This repository is not the product source code repository. It exists so users, beta testers, and reviewers can report issues in a structured, searchable place.

## Quick Links

- Website: <https://www.astroformsoftware.com/>
- User guide: <https://www.astroformsoftware.com/docs/>
- Format coverage: <https://www.astroformsoftware.com/docs/qa/format-coverage/>
- First launch and import: <https://www.astroformsoftware.com/docs/quick-start/first-launch-and-import/>
- Five-minute tour: <https://www.astroformsoftware.com/docs/quick-start/five-minute-tour/>
- Redaction guide: [docs/redaction-guide.md](docs/redaction-guide.md)
- Localization feedback guide: [docs/localization-guide.md](docs/localization-guide.md)

## What To Report Here

Please open an issue for:

- Import failures or incorrect rendering for supported PCB formats.
- Crashes, hangs, slow loading, or viewer interaction problems.
- Incorrect object selection, layer visibility, Workbench search, or Data page results.
- Export, Quick Look, revision, or library-management issues.
- Documentation gaps, confusing wording, or missing troubleshooting steps.
- Localization issues, terminology corrections, or untranslated app/docs text.
- Feature requests that would make PCB review, communication, or handoff easier.

## What Not To Share Publicly

PCB files often contain confidential product, customer, supplier, routing, or manufacturing information.

Do not attach private board files, screenshots with sensitive text, full project archives, API keys, license details, customer names, or commercial BOM/pricing data to a public GitHub issue. If a private file is required, describe the issue publicly first and wait for a maintainer to provide a private transfer path.

For examples of safe public reports, see [docs/redaction-guide.md](docs/redaction-guide.md).

## Before Filing A Bug

Please try to collect:

- PCB Atlas version and build number.
- Platform and device: iPadOS, iOS, or macOS; device model; OS version.
- Input format: KiCad `.kicad_pcb`, KiCad project/schematic folder, DSN, SES, IPC-2581 XML, ODB++ zip/folder, Gerber/Drill package, or another format.
- Import path used: `Import File`, `Import Folder`, system file association, drag and drop, Quick Look, or revision/SES action.
- Expected result and actual result.
- Smallest non-confidential sample or clear reproduction steps.
- Screenshots, screen recordings, or copied error text with sensitive details removed.
- Support Bundle text if available from PCB Atlas and safe to share.

## Good Bug Report Shape

1. What were you trying to do?
2. What did you expect PCB Atlas to show or do?
3. What happened instead?
4. Can you reproduce it? If yes, list the exact steps.
5. Which file format and import path were involved?
6. Did it happen after an app update, OS update, or file change?

## Public Beta Notes

For a fast first pass through the app:

1. Open a built-in sample such as `h730duino` or `BluePhil`.
2. In `2D`, pan, zoom, select an object, and open `View Info`.
3. Open Workbench and try `Visibility`, `Selection Filter`, `Objects`, and `Board Problems`.
4. Open `Data` to review document status, statistics, import issues, and Quick Estimate / Revision Quote.
5. For KiCad `.kicad_pcb` documents, switch to `3D` and wait for staged loading to complete.
6. Use `Import File` for single files or zips, and `Import Folder` for KiCad projects, schematic folders, Gerber/Drill packages, or ODB++ directories.
7. Start export from `2D`. If a purchase screen appears first, export entitlement is locked for that device/account.
8. AI features are optional and require a configured provider/key in `Settings > AI`.

## Issue Triage

Maintainers may edit titles, labels, or templates to make issues easier to search. We may close duplicates, requests that cannot be reproduced, or reports that require confidential files but do not have a safe reproduction path yet.

For maintainer workflow details, see [docs/triage.md](docs/triage.md).

## Pull Requests

PCB Atlas is closed-source commercial software. This repository does not accept product source-code pull requests. Please use issues for bug reports, documentation corrections, localization feedback, and workflow-level feature requests.
