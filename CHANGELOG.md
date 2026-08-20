# Changelog

All notable changes to the Linux Fedora Cheat Sheet. Newest first. Milestone versions marked ★ are preserved in `archive/`.

**Why does this start at v2.5?** Because Knox learns as he sprints. This project began as a study aid thrown together mid-course, and the notions of version control, changelogs, and folder structure had to be learned *while* the thing was being built — which is, fittingly, also how you learn Linux. Everything before v2.5 lives only in memory and a few chaotic filenames. From v2.5 onward, the history is real.

The project is not finished, by the way. It probably never will be — it's too much fun.

## v2.10.1 — 2026-08-20
- SSH handshake diagram remade: client/server boxes plus four numbered steps (connect → host key → secure channel → authenticate).
- Fixed PS status-code cards (letter/name/description now stack instead of running on one line).
- Removed leftover "1 owner group 4096 filename" fragment from the permissions visual.
- Example IPs changed to `203.0.113.7` — the RFC 5737 documentation range, the 555 number of IP addresses.
- Footer disclaimer now links to this repository.

## ★ v2.10 — 2026-08-20
- The root terminal grew up: tab completion, working `grep` (incl. `-r`/`-i`), `chmod`/`chown` with opinions, eight joke man pages, and exactly one working pipe.
- A six-flag hunt with a `score` command; progress survives reloads.
- The previous root finally has a name. His story is in the logs.

## v2.9.3 — 2026-08-20
- Exam section trimmed of two semi-true claims; checklist wording fixed.
- Three new rows in the Problem → Tool index (`less`, `scp`, `lscpu`/`lspci`/`lsusb`).
- Shorter username note. Footer disclaimer added.

## v2.9.2 — 2026-08-20
- How-to grid expanded to six points (incl. the click-to-copy + `Ctrl+Shift+V` paste lesson).
- Collapsible body sections (default expanded; jumping or searching auto-expands; print always expands).
- Module band labels promoted to header size. Sidebar defaults: Module 1 open, rest closed.
- Scrollspy fixed for h3-level sections (Exam group highlighting bug).

## v2.9.1 — 2026-08-19
- Fonts (Outfit + JetBrains Mono) embedded as base64 — the file is now truly self-contained and offline.
- Header pills, legend, and module bands share one right edge.
- Sidebar groups open on load; COURSE removed from the legend pill.

## ★ v2.9 — 2026-08-19
- Complete visual system rework: one job per color, one color per job.
- Color tokens renamed by function (`--code-cmd`, not `--cyan`); callouts unified to one neutral style with emoji labels; badges use one hue per module; the whole page reduced to an 8-token type scale.
- Print stylesheet remaps the same tokens. Google Fonts import removed (offline rule).

## v2.8.1 / v2.8.2 — 2026-08-15 → 18
- UI polish: legend moved above Module 1, username box rewritten, prompt section labels, sizing fixes.

## ★ v2.8 — 2026-08-15
- Full-page live filter (`/`), click-to-copy on commands, localStorage persistence, scrollspy sidebar.
- Print stylesheet, accessibility basics (skip-link, focus outlines, reduced-motion).
- Content accuracy pass: less/man key casing, `cp -r`, hard links, course-claim tagging ("course says X; in reality Y").
- Easter egg filesystem expanded; fineprint hints introduced.

## v2.7 / v2.7.1 — 2026-07
- Easter egg gained the construct in /opt and a certain multiplying process.
- Lesson learned this version: the terminal's voice belongs *in* the terminal. The main page stays calm.

## ★ v2.5 — 2026-07
- The base. Full course coverage 1.1–4.4 across 40 sections, module badges, the root terminal in its original form.
- Verified complete against all four module transcripts.
