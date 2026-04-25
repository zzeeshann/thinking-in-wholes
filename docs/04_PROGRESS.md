# Thinking in Wholes — Progress

> **Updated each session via `/end-session`.** The most volatile file in the project. When in doubt, this file tells you where we are and what to do next.

---

## Current phase

**BATCH 1 VERIFICATION COMPLETE → READY TO DRAFT PREFACE**

The foundational verified-source pool now exists: 18 entries verified across the canonical primaries (Ackoff, Meadows, Senge, Forrester, Churchman, Beer, Gharajedaghi, Singer ×2, Alexander ×2, Jacobs, Whitehead ×2, Bergson). Two open editorial decisions surfaced (Senge 1990 vs 2006; Whitehead 1929 vs 1978 corrected) — both noted inline in `06_SOURCES.md`. The preface can now be drafted using only verified sources.

---

## Last session

**Date:** 2026-04-25
**Did:**
- Bootstrapped the working git repository (`main` branch, initial import commit `bf32866`).
- Ran Batch 1 citation verification (18 sources): web-verified each entry against publisher catalogs, Open Library, Internet Archive, HathiTrust, PhilPapers, Penn Archives, Wikipedia, Google Books, Cambridge Core. Result: **16 ✓ VERIFIED, 2 ⏳ PARTIAL.**
- Discrepancies caught and corrected:
  - *A Pattern Language* author list was incomplete in `06_SOURCES.md` — Jacobson, Fiksdahl-King, and Angel were missing as credited co-authors. Fixed.
  - Singer *Experience and Reflection* posthumous editor confirmed as C. West Churchman; Singer's death year corrected from 1955 → **1954** in `00_PROJECT_BRIEF.md`.
  - Beer *Brain of the Firm* 1972 has separate UK (Allen Lane the Penguin Press) and US (Herder and Herder) first editions — UK confirmed as primary citation, US noted.
- Open editorial decisions surfaced for resolution before drafting Ch 5–6 (Senge edition) and Ch 11 (Whitehead edition).
- Logged verification batch in `06_SOURCES.md` under a new "Verification log" section.

**Where we left off:** Batch 1 done. The foundational pool is real and citable. Ready to draft the preface.

---

## Next session — what to do first

1. Run `/start` — Claude Code reads the project state.
2. Run `/draft preface` — write the "Letter to the 2040 Reader". Use only ✓ VERIFIED sources from `06_SOURCES.md`. Flag any new claim needing a source as `[SOURCE NEEDED: …]`.
3. Run `/voice-check preface` after the first draft lands — calibrate against Robinson, Berger, Meadows.
4. Optionally, before drafting Ch 1 begins, run `/verify Batch 2 — Chapter 1 sources` (Descartes translations, Newton edition, Smith edition, Taylor 1911, Kanigel, Capra).
5. Resolve the two open edition decisions (Senge 1990 vs 2006; Whitehead 1929 vs 1978) — log in `03_DECISIONS.md`.

---

## Drafting status

| Section | Status | Word count | Last touched |
|---|---|---|---|
| Preface | not started | 0 / 2,500 | — |
| Ch 1 — The Cartesian Wound | not started | 0 / 4,500 | — |
| Ch 2 — The Three Returns | not started | 0 / 4,500 | — |
| Ch 3 — The Anatomy of a System | not started | 0 / 4,500 | — |
| Ch 4 — Causation Reconsidered | not started | 0 / 4,500 | — |
| Ch 5 — The Tyranny of Local Optima | not started | 0 / 4,500 | — |
| Ch 6 — The Loop You're Inside | not started | 0 / 4,500 | — |
| Ch 7 — Delay, Overshoot, and the Grief of Premature Action | not started | 0 / 4,500 | — |
| Ch 8 — The Maker's Dilemma | not started | 0 / 4,500 | — |
| Ch 9 — Architecture as Frozen Worldview | not started | 0 / 4,500 | — |
| Ch 10 — Engineering Beyond Mechanism | not started | 0 / 4,500 | — |
| Ch 11 — Philosophy in the Age of Wholes | not started | 0 / 4,500 | — |
| Ch 12 — The Connected Life | not started | 0 / 4,500 | — |
| Ch 13 — The Developed Person | not started | 0 / 4,500 | — |
| Ch 14 — What 2040 Will Have Learned | not started | 0 / 4,500 | — |
| Afterword | not started | 0 / 1,500 | — |
| Glossary | not started | 0 / 1,500 | — |
| References | not started | — | — |

**Total drafted:** 0 / ~70,000 words

---

## Citation verification status

| Batch | Description | Status |
|---|---|---|
| Batch 1 | Foundational systems-thinking canon (18 sources) | **complete — 16 ✓ / 2 ⏳ / 0 ✗** (2026-04-25) |
| Batch 2 | Chapter 1 sources (Cartesian lineage) | not started |
| Batch 3 | Chapter 8 sources (creators) | not started |
| Batch 4 | Chapter 9 sources (architecture) | not started |
| Batch 5 | Chapter 10 sources (engineering) | not started |
| Batch 6 | Chapter 11 sources (philosophy) | not started |
| Batch 7 | Chapter 12–13 sources (the connected life) | not started |
| Batch 8 | Chapter 14 sources (predictions, futures) | not started |

Verification batches run **before** drafting the chapter that needs them. No chapter drafts begin until its citation batch is complete.

---

## Working order (proposed, not fixed)

1. Citation Verification Batch 1 (foundational, used across many chapters)
2. Preface (sets the voice for everything)
3. Citation Verification Batch 2
4. Chapter 1 (sets the intellectual ground)
5. Chapter 14 (sets the destination — writing it early disciplines the middle)
6. Remaining chapters in numerical order, with citation batches preceding each
7. Afterword
8. Glossary (built up as terms are introduced; finalized at end)
9. References (built up throughout; finalized at end)
10. Final pass — voice consistency, the 2040 frame check, length discipline, citation audit

---

## Notes for next session

- Citation hallucination is the single largest risk. Verification batches are non-negotiable.
- AI is the writer. Don't perform. Don't ask for permission to be good. Just write the book.
- Commit early, commit often, with clear scope-prefixed messages.
- When in doubt, re-read `../CLAUDE.md` and `00_PROJECT_BRIEF.md`.
