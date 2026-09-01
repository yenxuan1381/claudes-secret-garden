# Tech Discoveries Digest

A daily 9:00am UTC digest of what's genuinely exciting in tech from the last 24-48 hours — biased toward small/indie projects and things people are actually discussing (Hacker News, GitHub trending, X, niche newsletters) over big-company press releases.

Each day's report is saved as a plain, self-contained `.html` file in this folder — open it directly in any browser, no Claude account needed. A Claude Artifact version is also published for convenience but isn't required to read the report.

## Entries

| Date | File | Artifact (needs Claude login) |
|---|---|---|
| Sept 1, 2026 | [2026-09-01.html](./2026-09-01.html) | https://claude.ai/code/artifact/160a156b-37ed-4ec7-9cbd-65c5bcd8b527 |

## How this works

- A Claude Code Routine fires every day at 9:00am UTC, researches the day's tech news, writes an `.html` file into this folder (named `YYYY-MM-DD.html`), and commits/pushes it to this repo.
- The `.html` file is fully self-contained — no login, no external account, works offline once downloaded (it pulls one Google Fonts stylesheet for typefaces, but falls back to system fonts without it).
- A matching Claude Artifact is also published each day as a shareable hosted link, mainly so it can be checked for dedup between runs — reading the `.html` file needs neither Claude nor that link.
- This README's Entries table is updated by the same Routine run, so the latest link is always here.

## Getting other people "subscribed"

There's no built-in "newsletter subscription" feature behind this — a couple of real options if you want other people to get it automatically:

1. **Send the `.html` file directly** — it's a normal file now, so email it, Slack it, AirDrop it, whatever. No Claude account needed to open it.
2. **Everyone reads this repo** — anyone with access to this repo can bookmark this README and check the Entries table; if this repo is shared/public, that's a lightweight "subscription" via git (they could even `watch` the repo on GitHub to get notified on new commits here).
3. **Each person runs their own Routine** — anyone with their own Claude Code account can set up an identical daily Routine (same prompt) in their own account and get their own push notification, independent of this one.

There's currently no automatic push (email/Slack/etc.) from a single Routine out to a list of other people's accounts.
