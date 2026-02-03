# GitHub Trends – Page Format (MUST KEEP CONSISTENT)

All daily pages (`YYYY-MM-DD.html`) must match the **same layout, sections, and styling** as `2026-02-02.html`.

## Required structure

- `<head>` includes:
  - Umami script (website id: `3a86a96f-bb46-460c-bca8-3291603672f1`)
  - Inline CSS identical (or functionally identical) to `2026-02-02.html`
  - Meta description
- Body layout:
  - Container wrapper `.container`
  - Back link: `← Back to Archives`
  - Header with:
    - Title `🔥 GitHub Trends`
    - `.issue-info` as: `Issue #N · <Weekday>, <Month> <D>, <YYYY>`
  - **Featured Repo** block (class `featured`, badge `🏆 #1 TRENDING`) with stats
  - **Trend Analysis** box (class `analysis`) with a short paragraph
  - **Category sections** (multiple `h2.section-title`) containing repo cards (`.repo-card`), grouped by theme
  - **Quote** section (`blockquote.quote` with `p` + `cite`)
  - Footer matches `2026-02-02.html`.

## Content rules

- Each repo card includes:
  - rank badge
  - repo name link (opens in new tab)
  - description
  - optional short `repo-insight` line (💡)
  - meta: language + total stars + stars today
- Issue number increments daily starting from `2026-02-01` as Issue #1.

If the format drifts, **fix the generator/prompt before publishing**.
