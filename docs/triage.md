# Maintainer Triage Guide

This guide keeps the feedback repository consistent and useful.

## First Pass

For each new issue:

1. Confirm whether the issue is public-safe.
2. Add or correct the issue type label.
3. Normalize the title to include the affected area.
4. Ask for missing reproduction details.
5. Link duplicate or related issues.

## Suggested Title Prefixes

- `Import:` for file loading, format detection, revision import, or SES flows.
- `Viewer 2D:` for pan, zoom, selection, layers, Workbench, object info, or rendering.
- `Viewer 3D:` for KiCad 3D loading and scene display.
- `Data:` for status, statistics, Quick Estimate, and Revision Quote.
- `Export:` for PNG, PDF, source export, converted DSN/KiCad export, or entitlement flow.
- `Quick Look:` for Finder or Files thumbnails/previews.
- `Docs:` for website and user guide feedback.
- `Localization:` for app or docs translation and terminology feedback.
- `Feature:` for product requests.

## Priority Hints

- `P0`: data loss, repeatable crash on launch, blocker for App Store review, or severe privacy leak.
- `P1`: repeatable import failure for a supported format, wrong geometry, unusable viewer, or broken export.
- `P2`: workflow bug with a workaround, confusing state, partial rendering issue, or docs gap.
- `P3`: polish, wording, minor UI roughness, or exploratory feature request.

## Confidential Files

If a user needs to share a private board:

1. Keep the public issue limited to symptoms and metadata.
2. Ask for a minimal redacted sample first.
3. If private transfer is truly required, arrange it outside the public issue.
4. Never repost confidential file details into the issue.

## Localization Issues

For localization reports:

1. Confirm the locale and exact current text.
2. Ask where the text appears if the location is unclear.
3. Prefer terminology that fits PCB design and manufacturing usage.
4. Keep regional differences visible in the issue rather than flattening them too early.
5. Link related terminology issues when the same term appears across app and docs.

## Closing Guidance

Close issues when:

- The report is a duplicate and the original is linked.
- The issue lacks enough information and the reporter did not respond after follow-up.
- The behavior is documented and expected.
- The request is outside PCB Atlas scope.
- A fix shipped and the user can verify in a named build.
