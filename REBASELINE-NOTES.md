# Tracker update — 25 November 2026 (Asia/Calcutta)

Delivery kickoff re-baselined to 25 November 2026 because setup calls and credentials slipped after the 4 November agreement. Kickoff is short (25–27 Nov) because the SoW was already approved, the tracker has been live since 11 Nov, 11 of 12 kickoff questions were answered on 18 Nov, and Claude was purchased on 23 Nov.

## New dates

| Phase | Dates |
| --- | --- |
| Kickoff and access | 25–27 November 2026 |
| Week 1: connect everything | 28 November–4 December 2026 |
| Week 2: outbound engines on | 5–11 December 2026 |
| Week 3: inbound and social on | 12–18 December 2026 |
| **All core automations live** | **18 December 2026** (was 3 December) |
| Optimise and repeat | 19 December 2026–15 January 2027 |
| First monthly report | 27 December 2026 |
| KPI targets agreed | 15 January 2027 |
| Month 2+: scale | 16 January–15 February 2027 |

Open later-phase tasks were shifted **+15 days** (not +21), because remaining kickoff was compressed from nine days to three.

## Status marked done

- K5: 11 of 12 kickoff questions answered (18 Nov). Q5 social handles still open, due 27 Nov.
- C1 / Claude access item: purchase completed 23 Nov. Invite/login on the setup call may still be needed.
- K4 (setup Google Meet) remains waiting, now due 27 Nov.
- K7 (agree ICPs) is now a live “For approval” document, due 27 Nov.

`pageVersion` was left as `4903296169d3` so a drop-in replacement of `board.enc.json` does not trigger an index.html reload loop.

## How to publish

Replace `board.enc.json` in `github.com/rsq-code12/gtm-tracker` (same AES-256-GCM key already in the private `#k=` link). Preferred: commit on branch `icp-rebaseline` and review before merging to `main`. This box had no `gh` login and no git credentials, so the files were left here instead of being pushed.

## This branch

`board.enc.json` is the re-baselined board, encrypted with the same AES-256-GCM key. A "What we've done so far" page was added after that file was prepared, so the ciphertext was regenerated (same key, `pageVersion` unchanged). `board.json` is the readable copy for review.

Documents with HTML or with sections/blocks open as full pages in the tracker. The page renderer is the Alurei tracker's library-block reader (headings, paragraphs, lists, callout boxes, tables and a button that opens another document), plus the Hot right now sidebar.
