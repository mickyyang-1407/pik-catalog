# Pik Catalog

Public plugin-version data consumed by **Pik Manager** (macOS audio plugin manager).

- `versions.json` — latest known versions per vendor/product. Regenerated daily by an
  automated pipeline (scrapers against official vendor pages) plus a hand-curated
  overrides layer. Every entry carries its official source URL and a `source` grade
  (`scrape` = automated, `manual` = human-verified, `updater` = vendor updater API).
- `report.md` — the latest generation report (per-vendor status).

**Privacy**: this repository contains only public version numbers collected from
vendors' official pages. Pik Manager fetches this file with a bare GET — it never
sends anything about you or your library. Update checking can be turned off entirely
in the app's Settings.

Found a wrong or stale version? Open an issue with the official source link.
