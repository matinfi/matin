# Matin AI — Cafe Discovery & Reservation Platform

Matin AI is a WordPress theme and core plugin for discovering cafes, live-music events, football screenings, and making reservations.

## Release status

- Latest locally packaged build: **1.8.0** (theme + core plugin + development bundle).
- Release notes: [Matin AI 1.8.0](docs/RELEASE-NOTES-fa-1.8.0.md)
- QA report and known limitations: [QA and release report](docs/QA-AND-RELEASE-fa.md)

## 1.8.0 scope

- Turkish-only public-facing theme.
- Optional browser geolocation, enabled only after visitor permission.
- Cafe latitude/longitude and discount percentage fields.
- Discount display on event cards and downloadable event reservation tickets.
- AI recommendation-count and priority-cafe settings.
- Concise assistant instructions emphasizing event times, cafe opening hours, and location relevance.
- Glassmorphism event cards.

## Important release limitations

The 1.8.0 ZIPs were built and syntax-checked in the development workspace. This GitHub repository has historically contained documentation rather than the full source tree; the installable source files are **not yet synced into this repository**. Do not treat the repository itself as a complete deployable release until the theme and plugin source directories are committed.

Cafe opening hours are currently free-text metadata, not a fully structured schedule engine. Independent reservations for cafes without a listed event and complete Persian/Turkish localization of every admin screen remain unfinished. Live WordPress installation and real OpenRouter/Gemini API tests are still required.

Never commit API keys, tokens, or real customer data.
