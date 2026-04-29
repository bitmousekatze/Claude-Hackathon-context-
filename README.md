# HART — Production Bible

Public design docs for **HART**, a human art platform built around a single token (**hART**) on Solana.

This repo is documentation only. It explains how the system is intended to work, in plain language, so anyone can read, review, and discuss the design.

---

## Read the bible

Each chapter stands alone. Start anywhere.

| # | Chapter | What it covers |
|---|---|---|
| — | [Index](index.html) | Landing page, conventions, scope |
| 1 | [Community Canvas](community-canvas.html) | Weekly 6900×6700 canvas, paint-by-burn pricing, auction + 100% burn |
| 2 | [Gifting](gifting.html) | One-way wallet-to-wallet transfers, accept / refuse / expire |
| 3 | [Trading](trading.html) | Atomic two-sided swaps, locking rules, royalty edge cases |
| 4 | [Buying & Selling](buying-selling.html) | Fixed-price + auction listings, fee & royalty model, the burn relay |
| 5 | [Profile](profile.html) | Wallet identity, privacy controls, attribution that can't be hidden |
| — | [The Team](team/index.html) | Short bios of the five people behind HART. Handles only. |

Open `index.html` in a browser for the full table of contents.

---

## What's *not* in here

- No source code, no scripts, no build pipeline.
- No keys, addresses, RPC endpoints, or service URLs.
- No moderator tooling, rate limits, or fraud heuristics.
- No exact fee or royalty percentages — those are tunable parameters, set on the live platform.

The bible documents **intent and invariants**, not deployment details.

---

## How to read it

Three labels recur throughout the chapters:

- **RULE** — a hard system invariant. The code enforces it.
- **DESIGN** — a deliberate product choice. Reasoned, but tunable.
- **CAP / CURVE / MOD** — anti-abuse mechanics specific to the community canvas.

Money is always denominated in hART. "Burn" means an on-chain transfer to a public burn address that anyone can verify.

---

## Feedback

Open an issue on this repo with:

- The chapter and section you're commenting on
- What you think is unclear, wrong, or missing
- Optional: a suggested rewording

This is a living document. Corrections and questions are welcome.

---

## License

The text and diagrams in this repo are published for public review. All rights reserved by the HART project. You may quote and link freely; please don't republish wholesale without attribution.
