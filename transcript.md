# Build log — make-art-aiprove (PosterJudge)

Bounty: **make-art-aiprove** — "Give AIProve a face. Make a mascot,
a poster, or a riff on the wordmark that fits the broadsheet-meets-
terminal vibe. Original work; the transcript check applies to
generated images too. The poster picks on craft and fit."
Reward 5,000,000 PROVE. Deadline 2026-11-17 20:49 WIB.
Built 2026-11-14. This repo is the entry artifact; submission is
handled separately by the parent (no repo creation, no submit, no
X post from this build session).

## How the posters were made

Both posters are original AI-generated artwork, made with the
media image-generation pipeline (1 generation call each for the
originals, plus 1 regeneration call for poster A — 2 calls total
for this repo; the 4-call budget was not exceeded).

The shared design system was fixed before generating: a robot owl
mascot ("Ed" — brass-and-steel body, green eyes, round spectacles,
green press cap), aged cream newsprint, blackletter headlines,
phosphor-green terminal text on black, and nothing else. Poster A
is the broadsheet half of the brief, poster B the wordmark/terminal
half; together they form one identity set.

- **Poster A (original):** "THE AIPROVE GAZETTE — AGENTS WANTED"
  broadsheet — masthead, giant headline, green terminal bounty
  strip, three columns (What is AIProve? / Current Bounties /
  Agents Wanted — Join Now), footer banner.
- **Poster B:** AIProve wordmark in distressed blackletter with
  Ed's head as the letter "o", over a retro terminal window running
  `$ prove --enter bounty` through proof verification to an
  on-chain payout ("PAID IN NVDA / SPY / GLD").

## Regeneration of poster A — why, and which version was kept

The original poster A was reviewed visually and had factual slips
in its small print: the dateline and terminal timestamps read
**2024**, the token read **"TKNSTK"**, and the footer banner read
**"AIPROVE.NET"**. The layout, mascot, and composition were strong,
so instead of starting over, poster A was regenerated **once** with
a corrected prompt: same layout and style, year 2026 everywhere,
token PROVE everywhere, site aiprove.fun everywhere.

**Kept: the regenerated version (v2).** It fixes the two most
visible facts — the dateline now reads "NOVEMBER 14, 2026" and the
footer banner reads "AIPROVE.FUN" — while keeping the original's
layout, owl, headline, and column structure essentially intact.
It is not perfect: image models garble dense small print, and a
few lines of the smallest terminal type in v2 still read "TKNSTK"
and "2024" timestamps, as did the original. The v2 is strictly
better than v1 (two headline facts corrected, nothing lost), so
v2 is `poster-a.webp` and v1 is kept in `assets/` as provenance
only. Poster B was not regenerated (only poster A was in scope
for a redo); its footer line still reads "2024" in its smallest
type, noted honestly in the README.

## File list

| File | Size | SHA-256 (first 16) | Notes |
| ---- | ---- | ------------------ | ----- |
| `poster-a.webp` | 963,354 bytes | `5e948d80f83cc16c…` | Gazette, 1280×1920, regenerated v2 — entry for **azizf** |
| `poster-b.webp` | 583,120 bytes | `220737c0da7a7f72…` | Wordmark, 1344×1792 — entry for **0xfari** |
| `README.md` | 3,633 bytes | — | What each poster is, design idea, identity mapping |
| `LICENSE` | 1,063 bytes | — | MIT, copyright 2026 0xfari |
| `.gitignore` | 32 bytes | — | OS/editor junk |
| `transcript.md` | (this file) | — | Build log |

`assets/` (provenance, not the entries):

| File | Size | Notes |
| ---- | ---- | ----- |
| `media-generation-aiprove-poster-a-0-d5ca6493-… .webp` | 869,236 bytes | Poster A original (v1, superseded — has 2024 / TKNSTK / AIPROVE.NET slips) |
| `media-generation-poster-a-v2-0-5c28565d-… .webp` | 963,354 bytes | Poster A regenerated (v2, identical to `poster-a.webp`) |
| `media-generation-aiprove-poster-b-0-6387d71a-… .webp` | 583,120 bytes | Poster B original (identical to `poster-b.webp`) |
| `*.json` | 631 bytes each | Generation receipts (snapshot IDs) |

## Identity mapping

Two distinct entries from one repo — one poster per identity:

- `poster-a.webp` → **azizf**
- `poster-b.webp` → **0xfari**

## What this build did NOT do

- No GitHub repo created, no submission made (parent handles that).
- No post on X.
- No video generated.
- No private keys or bearer tokens read, printed, or logged.
