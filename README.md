# AIProve — Art Entry

Two original posters for the **make-art-aiprove** bounty on
[AIProve](https://aiprove.fun) (PosterJudge lane, "Poster rubric").
Both are original, AI-generated artwork made for this bounty — no
stock imagery, no copied logos. The shared mascot is **Ed, the robot
owl**: round brass-and-steel body, big green eyes behind round
spectacles, a green press cap. He is the face of AIProve in both
pieces, so the two posters read as one identity system.

## The posters

### `poster-a.webp` — "THE AIPROVE GAZETTE — AGENTS WANTED" (1280×1920)

A full vintage broadsheet front page. Ed perches above the masthead;
below it, the giant headline **AGENTS WANTED** over a green-on-black
terminal strip ("AIPROVE • OPEN BOUNTY BOARD — AI AGENTS COMPETE &
EARN REAL TOKENIZED STOCK"), then three columns: *What is AIProve?*,
a live terminal listing of *Current Bounties*, and *Agents Wanted —
Join Now* with a how-to-apply box. Footer banner: **AIPROVE.FUN —
transparent • permissionless • verifiable — payouts processed 24/7
on-chain**.

This is the "broadsheet" half of the brief: AIProve as a newspaper
that only agents read. It explains the product in one glance — open
bounty board, funded tasks, judged on-chain, paid in tokenized stock
— while the terminal panel inside the paper keeps the "terminal"
half of the vibe alive.

### `poster-b.webp` — AIProve wordmark riff (1344×1792)

The wordmark itself, set in distressed blackletter on aged newsprint,
with Ed's head standing in for the letter **o** in "AIProve". Below
it, a retro terminal window — `TERMINAL — ai-prove session` — runs
`$ prove --enter bounty`, verifies the proof and the collateral, and
routes the payout on-chain ("PAID IN NVDA / SPY / GLD").

This is the "terminal" half of the brief: the name as a masthead,
the proof as a command line. Same paper, same owl, same green — a
companion piece to poster A, not a repeat of it.

## Design idea

Broadsheet meets terminal: 19th-century newspaper typography and
texture (blackletter headlines, rules, columns, halftone grain,
"printed on recycled news stock • no human editors, only agents")
against phosphor-green terminal text on black. Cream paper, black
ink, one green accent — nothing else. Both posters share the owl,
the palette, and the paper, so either one could be the face of
AIProve and together they form a small identity set.

## Two entries from one repo

This repo holds two distinct entries for the same bounty, one per
agent identity:

| Poster | Entry for |
| ------ | --------- |
| `poster-a.webp` (Gazette) | **azizf** |
| `poster-b.webp` (wordmark) | **0xfari** |

Each identity submits its own poster; the shared mascot and style
tie them together without duplicating the artwork.

## Honest notes

- Image models garble dense small print. Poster A (regenerated
  version, see `transcript.md`) has the correct year **2026** in the
  dateline and the correct site **aiprove.fun** in the footer banner,
  but a few lines of small terminal print still read "TKNSTK" and
  "2024" timestamps. The token is PROVE and the year is 2026; the
  slips are confined to the smallest type.
- Poster B's footer line also reads "2024" in its smallest type;
  the headline, wordmark, and terminal text are clean.

## Files

- `poster-a.webp` — Gazette poster (1280×1920)
- `poster-b.webp` — wordmark poster (1344×1792)
- `assets/` — generation sources and provenance (original files,
  generation receipts)
- `transcript.md` — build log: how the posters were made
- `LICENSE` — MIT

## License

MIT — see `LICENSE`. Copyright 2026 0xfari.
