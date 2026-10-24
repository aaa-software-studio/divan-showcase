# Divan
### A Persian poetry reader for Android

Divan brings Persian poetry into a right-to-left reading interface, with an offline library, Persian search, local favorites and reading preferences.

Developed by **AAA Software Studio** from the creator's idea with AI assistance.

**Status:** App preview under technical and content review  
**Public app download:** Not available yet  
**Telegram:** [Use Divan on Telegram](https://t.me/DivanYar_bot)

## Android App

Implemented areas include:

- Browsing poets and their works.
- Searching Persian poetry.
- Saving local favorites.
- Adjusting reading appearance.
- Daily poetry selections and Hafez fortunes.
- Text and image sharing workflows.
- Poetry interpretations, currently an editorial work in progress.

The app is built with Kotlin and Jetpack Compose, with Room/SQLite and DataStore for local data and settings. The reviewed source manifest does not request Internet permission. Sharing hands selected content to an Android destination app, whose own policies apply.

## Preview Status

The current private release candidate is **0.3.0-preview.1, build 9**, targeting Android 8.0 and later. A Release APK has been signed locally; the developer's report records signature validation and 16 KiB alignment checks.

Independent package checks confirmed file hashes, archive integrity, unchanged APK content after signing, and matching bundled assets between the candidate and its supplied source. These checks are not a full security audit or proof of source-to-binary reproducibility.

The creator reports successful use of an earlier Debug build and supplied real phone screenshots. The new signed Release candidate still requires device acceptance checks. Bundled content/image redistribution rights, literary review and application licensing also remain under review.

**No application binary or development source is distributed through this repository at this stage.** This page does not claim comprehensive interpretation accuracy, universal device compatibility or commercial readiness.

## Telegram Bot

[Open Divan on Telegram](https://t.me/DivanYar_bot)

The separate Telegram bot provides a chat-based route to Persian poetry. Earlier project demonstrations include poet browsing, search, Hafez fortunes, favorites and text sharing. The supplied developer report records a public-profile check on 2026-10-23; current command responses were not independently tested during this review.

The app and bot are presented separately; identical features or a shared backend are not assumed.

Only the public bot usage link is offered. Bot source, configuration, credentials, databases and deployment files are not distributed.

## Repository Scope

This is a product showcase and documentation repository. Private review reports, APKs, source archives, signing material and personal data are excluded. No open-source license for the application is granted by this showcase.

Built by [AAA Software Studio](https://github.com/aaa-software-studio).
