# Update Log (Changelog)

A concise, running log of significant changes to the WiFiAnalyzer app refactor. Times are local (PT).

- 2025-08-09 14:30 — Added `update.md` changelog file.
- 2025-08-09 14:05 — Fixed Logs screen crash (NPE) by lifecycle-safe binding access in `app/src/main/kotlin/com/vrem/wifianalyzer/logs/LogsFragment.kt`.
- 2025-08-09 03:02 — Verified and retained graph visibility after prior layout experiments; reverted risky height changes per user preference.
- 2025-08-09 03:00 — Reworded first-run Location permission rationale strings (`permission_msg`, `location_msg`) in `res/values/strings.xml`. Updated icon in `res/layout/info_location.xml` to launcher icon.
- 2025-08-08 — Enforced dark mode app-wide (palette and typography refresh), Phase 1 UI complete.
- 2025-08-08 — Implemented Logs menu: live scan logs view with Copy to Clipboard and Share actions.
- 2025-08-08 — Switched MaterialButton usage to standard Button in Logs UI for broader theme compatibility.
- 2025-08-08 — Updated launcher icons (foreground + monochrome) to new Wi‑Fi analyzer glyph; About menu reflects new icon.
- 2025-08-08 — Updated splash screen icon to match new branding.
- 2025-08-08 — Navigation polish: bottom nav tweaks and drawer header redesign; settings visual grouping via `PreferenceCategory` styles.
- 2025-08-06 — MaterialComponents theme overlay applied at layout scope to enable Chips/Slider without global theme change.
- 2025-08-06 — General UI modernization pass (Phase 1 planning + assets prep) with minimal-risk approach; no changes to scanning core.

Notes:
- Older entries (before 2025-08-09) are recorded by date only when specific times were not captured during work sessions.
- All changes prioritize stability and avoiding regressions in scanning functionality.
