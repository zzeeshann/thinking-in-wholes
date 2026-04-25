# Thinking in Wholes — Progress

> **Updated each session via `/end-session`.** The most volatile file in the project. When in doubt, this file tells you where we are and what to do next.

---

## Current phase

**PREFACE READY FOR DIRECTOR REVIEW · BATCH 2 VERIFIED · CH 1 UNBLOCKED**

The preface is voice-checked and reviewed (2,336 body / 2,577 with footnotes; six footnotes; zero unresolved `[SOURCE NEEDED]` flags). Batch 2 verification complete: Descartes, Newton, Smith, Taylor, Kanigel, Capra all ✓ VERIFIED, with standard modern editions specified for the three historical primaries (Cottingham/Stoothoff/Murdoch for Descartes; Cohen/Whitman for Newton; Glasgow Edition for Smith). Newton publisher discrepancy (Royal Society → Joseph Streater for the Royal Society) corrected. Chapter 1 — The Cartesian Wound is now drafting-ready. Two open editorial decisions still pending the director (Senge 1990 vs 2006; Whitehead 1929 vs 1978) but neither blocks Ch 1.

---

## Last session

**Date:** 2026-04-25
**Did:**
- Bootstrapped the working git repository (`main` branch, initial import commit `bf32866`).
- Ran Batch 1 citation verification (18 sources): web-verified each entry against publisher catalogs, Open Library, Internet Archive, HathiTrust, PhilPapers, Penn Archives, Wikipedia, Google Books, Cambridge Core. Result: **17 ✓ VERIFIED, 1 ⏳ PARTIAL, 0 ✗ UNVERIFIED.**
- Discrepancies caught and corrected:
  - *A Pattern Language* author list was incomplete in `06_SOURCES.md` — Jacobson, Fiksdahl-King, and Angel were missing as credited co-authors. Fixed.
  - Singer *Experience and Reflection* posthumous editor confirmed as C. West Churchman; Singer's death year corrected from 1955 → **1954** in `00_PROJECT_BRIEF.md`.
  - Beer *Brain of the Firm* 1972 has separate UK (Allen Lane the Penguin Press) and US (Herder and Herder) first editions — UK confirmed as primary citation, US noted.
- Open editorial decisions surfaced for resolution before drafting Ch 5–6 (Senge edition) and Ch 11 (Whitehead edition).
- Logged verification batch in `06_SOURCES.md` under a new "Verification log" section.
- Drafted the preface ("Letter to the 2040 Reader") at 2,301 body words (2,542 with footnotes). Six footnotes; zero unresolved `[SOURCE NEEDED]` flags. Forbidden-vocab sweep clean; 2040-frame check clean (no specific 2026 company / political-figure / platform / controversy references; AI named only as a class of technology); both rhetorical questions are answered with substance per style guide.

**Where we left off:** Preface first draft complete. Ready for `/voice-check preface` calibration against Robinson/Berger/Meadows, and director review. The two open edition decisions still need resolution before Ch 5/6 (Senge) and Ch 11 (Whitehead) can begin.

---

## Next session — what to do first

1. Run `/start` — Claude Code reads the project state.
2. Director review of the preface ([drafts/preface.md](../drafts/preface.md)) — voice, argument, anything to cut or sharpen.
3. Resolve the two open edition decisions (Senge 1990 vs 2006; Whitehead 1929 vs 1978) — log in `03_DECISIONS.md`. Neither blocks Ch 1, but both block subsequent chapters.
4. Run `/draft chapter 1` — *The Cartesian Wound*. All sources are verified. The ~4,500-word target opens the book's real argument; the chapter must do three things: (a) establish the full lineage of parts-thinking (Descartes → Newton → Smith → Taylor → Ford), (b) honour what analysis got right for 350 years, (c) name where the method's success became its trap. Use only ✓ VERIFIED sources from `06_SOURCES.md`.
5. Run `/voice-check ch01` and `/review ch01` after the first draft lands.

---

## Drafting status

| Section | Status | Word count | Last touched |
|---|---|---|---|
| Preface | voice-checked + reviewed | 2,336 body / 2,577 with footnotes | 2026-04-25 |
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

**Total drafted:** 2,301 / ~70,000 words (preface body; 2,542 with footnotes)

---

## Citation verification status

| Batch | Description | Status |
|---|---|---|
| Batch 1 | Foundational systems-thinking canon (18 sources) | **complete — 17 ✓ / 1 ⏳ / 0 ✗** (2026-04-25) |
| Batch 2 | Chapter 1 sources (Cartesian lineage, 6 sources) | **complete — 6 ✓ / 0 ⏳ / 0 ✗** (2026-04-25) |
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
