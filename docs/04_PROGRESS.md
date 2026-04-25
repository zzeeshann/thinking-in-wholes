# Thinking in Wholes — Progress

> **Updated each session via `/end-session`.** The most volatile file in the project. When in doubt, this file tells you where we are and what to do next.

---

## Current phase

**PREFACE + CH 1 + CH 14 FIRST DRAFTS BANKED · BATCHES 1, 2, 8 VERIFIED · DESTINATION SET · ALL OPEN DECISIONS RESOLVED**

Three sections committed, opening through closing: preface (voice-checked + reviewed), Ch 1 — *The Cartesian Wound*, and Ch 14 — *What 2040 Will Have Learned*. Total drafted body: 9,438 words (preface 2,336 + Ch 1 3,824 + Ch 14 3,278); 10,216 with footnotes. Sixteen footnotes total, all from the verified pool (Batches 1, 2, 8). Zero unresolved `[SOURCE NEEDED]` flags. Ch 14 is intentionally under the 4,500 target (3,278 body) — the chapter puts nine predictions on the record and made the book's central closing argument; padding it would weaken the discipline it models. Two previously-open editorial decisions resolved 2026-04-25 by AI under director delegation: Senge 1990 first edition is canonical primary; Whitehead 1978 Griffin/Sherburne corrected edition is the citing text (1929 retained as historical original). Both logged in `03_DECISIONS.md` and locked in `06_SOURCES.md`. No open decisions remain.

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
- Drafted the preface ("Letter to the 2040 Reader") at 2,301 body words; ran voice-check + review pass with three substantive revisions (concrete grounding in the closing, broken parallel structure on the climate paragraph, tightened predictions sentence). Final 2,336 body / 2,577 with footnotes; six footnotes; zero unresolved `[SOURCE NEEDED]` flags.
- Ran Batch 2 verification (6 Chapter 1 sources): all ✓ VERIFIED. Standard modern editions specified for Descartes (Cottingham/Stoothoff/Murdoch, Cambridge UP, 1985), Newton (Cohen/Whitman, UC Press, 1999), and Smith (Glasgow Edition, Oxford, 1976). Newton publisher discrepancy corrected (printer Joseph Streater, for the Royal Society).
- Drafted Chapter 1 — *The Cartesian Wound* — first draft at 3,824 body words / 4,159 with footnotes. Six footnotes (Descartes, Newton, Smith, Taylor, Kanigel, Capra), all from the Batch 2 verified pool. Forbidden-vocab sweep clean. No direct quotations from primaries (no verified page numbers in the source pool yet). Length ~700 words under the 4,500 target but crosses the style guide's "honest short" threshold (≥3,800); resisted padding.
- Ran Batch 8 verification (3 Ch 14 sources): Brand, Tetlock & Gardner, Davies — all ✓ VERIFIED, no discrepancies.
- Drafted Chapter 14 — *What 2040 Will Have Learned* — first draft at 3,278 body words / 3,480 with footnotes. Four footnotes (Tetlock & Gardner, Davies, Ackoff, Brand). Nine predictions on the record across three groups (AI, climate, institutional), with reasoning shown for each; five hopes named openly; closing argument for the developed person as the unit on which the systems response runs. Two forbidden-vocab violations caught in my own expansions ("fundamentally" and "in essentials") and fixed before commit. Length ~1,200 under the 4,500 target and ~500 below the "honest short" floor — but the chapter is the most exposed in the book, putting predictions on the record, and padding it would weaken the discipline it models.

**Where we left off:** Three first drafts banked (preface, Ch 1, Ch 14 — beginning, beginning-of-argument, end-of-argument). The destination is set; the middle can now be written into a known shape. Both previously-open edition decisions (Senge, Whitehead) resolved by AI under director delegation. Repository pushed public to GitHub at `zzeeshann/thinking-in-wholes`. Ready for director review of all three drafts and voice-check + review passes on Ch 1 and Ch 14.

---

## Next session — single command, then autonomous

**Director types `/go` (defined in `.claude/commands/go.md`). Nothing else needed.**

The `/go` command reads the full project state, recalls every prime directive (citation discipline, 2040 frame, voice rules, forbidden vocabulary, no-direct-quotation rule, length floor, `/review` ≠ `/ultrareview`), then runs the script below autonomously — committing per unit, pushing at the end. No per-step confirmation required. Director may interrupt at any time; an interruption overrides the script.

If the director prefers manual control, type `/start` instead — it does only the file-reading and waits for direction.

### The script `/go` runs

1. **`/voice-check ch01`** — calibrate [drafts/ch01_cartesian_wound.md](../drafts/ch01_cartesian_wound.md) against Robinson / Berger / Meadows. Identify the gap. Make 2–4 substantive revisions in place. Commit: `drafts: voice calibration pass on ch01`.

2. **`/review ch01`** — full pass against the style guide and the 2040 frame on [drafts/ch01_cartesian_wound.md](../drafts/ch01_cartesian_wound.md). Apply every fix. Commit: `drafts: review pass on ch01 (N findings addressed)`.

3. **`/voice-check ch14`** — same as step 1, on [drafts/ch14_what_2040_learned.md](../drafts/ch14_what_2040_learned.md). Pay particular attention to whether the nine predictions read as calm and specific (good) rather than breathless or hedged (bad).

4. **`/review ch14`** — same as step 2, on [drafts/ch14_what_2040_learned.md](../drafts/ch14_what_2040_learned.md). Ch 14 is the most exposed chapter; be hard on it.

5. **`/draft ch02`** — *The Three Returns*. Foundational pool (Batch 1) already covers all primary sources. Single argument per the outline: Ackoff, Meadows, Senge — what each saw that the others missed, what each got wrong, and the lineage continued (Forrester, Churchman, Beer, Gharajedaghi). Target 4,500 body words (3,800 honest-short floor). Use only ✓ VERIFIED sources. Per `03_DECISIONS.md`, Senge's 1990 first edition is canonical; Whitehead's 1978 corrected edition is the citing text where Whitehead is engaged. **Wait for director** before drafting if there is any ambiguity about scope; otherwise auto-proceed.

6. **`/voice-check ch02`** and **`/review ch02`** — same passes on the new draft.

7. **`/verify Batch 4 — Chapter 8 sources`** (Berger, Le Guin, Tolstoy, Robinson, Lewis). This unblocks Ch 8 — *The Maker's Dilemma*, the core craft chapter for the primary audience (creators).

8. End of script. Run `/end-session`, push to `origin/main`, tag the milestone if appropriate, summarise to director.

### Standing notes for next session

- **`/review` is the project's pass, not `/ultrareview`.** `/ultrareview` is Claude Code's built-in *cloud multi-agent review of a git branch* — paid, user-triggered, irrelevant to the in-session writing workflow. The project's review command is defined in [.claude/commands/review.md](../.claude/commands/review.md). Do not confuse them.
- All editorial decisions are resolved; no open questions block any of the steps above.
- Commits use scope prefixes (`drafts:`, `ch02:`, `sources:`, `meta:`, `session:`) and follow the conventions in `CLAUDE.md`.
- The director may interrupt the script at any point; treat any interruption as override.

---

## Drafting status

| Section | Status | Word count | Last touched |
|---|---|---|---|
| Preface | voice-checked + reviewed | 2,336 body / 2,577 with footnotes | 2026-04-25 |
| Ch 1 — The Cartesian Wound | voice-checked + reviewed | 3,824 body / 4,159 with footnotes | 2026-04-25 |
| Ch 2 — The Three Returns | voice-checked + reviewed | 3,609 body / 3,988 with footnotes | 2026-04-25 |
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
| Ch 14 — What 2040 Will Have Learned | voice-checked + reviewed | 3,278 body / 3,480 with footnotes | 2026-04-25 |
| Afterword | not started | 0 / 1,500 | — |
| Glossary | not started | 0 / 1,500 | — |
| References | not started | — | — |

**Total drafted:** 13,047 / ~70,000 words (preface 2,336 + Ch 1 3,824 + Ch 2 3,609 + Ch 14 3,278, body counts; 14,204 with footnotes)

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
| Batch 8 | Chapter 14 sources (predictions, futures, 3 sources) | **complete — 3 ✓ / 0 ⏳ / 0 ✗** (2026-04-25) |

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
