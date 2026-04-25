# Thinking in Wholes — Progress

> **Updated each session via `/end-session`.** The most volatile file in the project. When in doubt, this file tells you where we are and what to do next.

---

## Current phase

**FOUR SECTIONS BANKED + REVIEWED · BATCHES 1, 2, 3, 8 VERIFIED · CH 8 NOW DRAFTING-READY · ALL OPEN DECISIONS RESOLVED**

Four sections committed, opening through closing: preface, Ch 1 — *The Cartesian Wound*, Ch 2 — *The Three Returns*, and Ch 14 — *What 2040 Will Have Learned*. All four are voice-checked and reviewed against `02_STYLE_GUIDE.md` and the 2040 frame. Total drafted body: 13,047 words (preface 2,336 + Ch 1 3,824 + Ch 2 3,609 + Ch 14 3,278); 14,204 with footnotes. Twenty-five footnotes total, all from the verified pool (Batches 1, 2, 3, 8). Zero unresolved `[SOURCE NEEDED]` flags. Two further editorial decisions resolved by AI under director delegation: Le Guin *Steering the Craft* — cite the 2015 Mariner revised edition as canonical (1998 Eighth Mountain Press original noted as historical first); Tolstoy *What Is Art?* — cite the Hackett 1995 reprint of Aylmer Maude's authorised translation (Vincent Tomas introduction) as the citing text (1899 Walter Scott London edition noted as historical first English publication). Both logged in `03_DECISIONS.md` and locked in `06_SOURCES.md`. No open decisions remain. Ch 8 — *The Maker's Dilemma* — is now drafting-ready alongside Ch 3–7 (which can draw on the foundational Batch 1 pool).

---

## Last session

**Date:** 2026-04-25 (working session 2 — `/go` script run)
**Did:**
- `/voice-check` and `/review` passes on Ch 1: four voice-calibration revisions (factual fix on the *Discourse* placement — published as the introduction to the three essays, not "in the back" of them; cut a bookkeeping sentence; cut an "it is hard to overstate" hedge; broke the strict parallelism in the schools/hospitals/companies/cities passage). Three review-pass findings addressed (dropped quote marks around "one best way" attributed to Taylor without verified page; restored grammatically clean syntax in the Companies clause; tightened a bookkeeping line near the chapter close). Ch 1 status moved from *first draft* to *voice-checked + reviewed*.
- `/voice-check` and `/review` passes on Ch 14: three voice-calibration revisions (fixed "unaccurate" → "inaccurate"; cut a bookkeeping micro-sentence "It also misses the point."; replaced an invented "Ackoff student once observed" attribution with "in Ackoff's framing"). Review pass found zero further substantive findings. Ch 14 status moved from *first draft* to *voice-checked + reviewed*.
- Drafted Chapter 2 — *The Three Returns* — at 3,609 body words / 3,988 with footnotes. Nine footnotes, all from the foundational Batch 1 verified pool. Structure: framing the three figures as returns of purpose / dynamics / practice; ~1,000 words on each (Ackoff, Meadows, Senge) including what each returned and what each got wrong; an explicit disagreements section on the three structural questions on which they differed (scale, formal modelling, internal reformability); the four-figure lineage continuation (Forrester / method, Churchman / ethics, Beer / cybernetic structure, Gharajedaghi / design practice); a closing triangulation paragraph. Voice-check pass made two small revisions (cleaner opener, tightened a clausy phrase). Review pass made one substantive revision (dropped an unverified Wiener mention from the body). Length 3,609 body — 191 words below the 3,800 honest-short floor — but covers every outline element at appropriate density; per `03_DECISIONS.md` length-floor decision, committed without padding.
- Ran Batch 3 citation verification (7 Chapter 8 sources for *The Maker's Dilemma*): web-verified Berger × 2, Le Guin × 2, Tolstoy, Robinson, Lewis against publisher catalogues, Open Library, Internet Archive, Wikipedia, PhilPapers, AbeBooks, and standard library and antiquarian records. Result: **7 ✓ VERIFIED, 0 ⏳ PARTIAL, 0 ✗ UNVERIFIED.** No bibliographic discrepancies needed correcting beyond the two edition decisions noted below.
- Two new editorial edition decisions resolved by AI under standing director delegation: (a) Le Guin *Steering the Craft* — cite the 2015 Mariner revised edition as canonical (the original 1998 *Steering the Craft: Exercises and Discussions on Story Writing for the Lone Navigator or the Mutinous Crew*, Eighth Mountain Press, noted as historical first edition); (b) Tolstoy *What Is Art?* — cite the Hackett 1995 reprint of Aylmer Maude's authorised translation, with Vincent Tomas's introduction, as the citing text (the 1899 Walter Scott Ltd. London first English edition noted as historical original; Pevear/Volokhonsky 1995 Penguin Classics noted as a respected contemporary alternative). Both decisions logged in `03_DECISIONS.md` and locked in `06_SOURCES.md`. Reasoning analogous to the Whitehead 1978 corrected-edition resolution: cite the modern scholarly text, preserve the historical original.
- Caught a batch-numbering inconsistency: the previous next-session script referred to the Chapter 8 verification as "Batch 4," but the verification status table in `06_SOURCES.md` numbers Chapter 8 sources as Batch 3 (Batch 4 covers Chapter 9 — architecture). The verification was logged correctly under Batch 3. The next-session script below uses the canonical batch numbering from the verification table.

**Where we left off:** Four sections banked and reviewed (preface, Ch 1, Ch 2, Ch 14); 13,047 body words drafted, ~18.6% of the ~70,000-word target. Four citation batches complete (1, 2, 3, 8). Ch 8 is now drafting-ready when its turn comes. The most natural next move is Ch 3 — *The Anatomy of a System* — which needs a citation batch first (Bertalanffy, Wiener, Holland are still ✗ UNVERIFIED in the Ch 3 source list).

---

## Next session — single command, then autonomous

**Director types `/go` (defined in `.claude/commands/go.md`). Nothing else needed.**

The `/go` command reads the full project state, recalls every prime directive (citation discipline, 2040 frame, voice rules, forbidden vocabulary, no-direct-quotation rule, length floor, `/review` ≠ `/ultrareview`), then runs the script below autonomously — committing per unit, pushing at the end. No per-step confirmation required. Director may interrupt at any time; an interruption overrides the script.

If the director prefers manual control, type `/start` instead — it does only the file-reading and waits for direction.

### The script `/go` runs

1. **`/verify Chapter 3 sources`** — verify Bertalanffy *General System Theory* (1968), Wiener *Cybernetics* (1948; verify edition — 1948 first vs 1961 revised), and Holland *Emergence* (1998). The foundational Batch 1 already covers Meadows, Forrester, Beer, and Gharajedaghi for Ch 3, so this is a small batch of three supporting entries. Wiener's edition decision should be resolved at verification: provisionally cite the 1961 revised edition (MIT Press) as canonical unless the historical-original case is stronger. Update `06_SOURCES.md` markers and add a verification log entry. Commit: `sources: verify Ch 3 supporting entries (N verified, M partial, K unverified)`.

2. **`/draft ch03`** — *The Anatomy of a System*. This is the reference chapter — vocabulary defined with examples that survive translation across domains: emergence, feedback (reinforcing and balancing), delay, hierarchy, boundary, purpose, resilience. Each definition earns its place by appearing after a concrete example, not before (per `02_STYLE_GUIDE.md`). The chapter is largely Meadows-grounded; Bertalanffy, Wiener, and the older cybernetic tradition appear as the historical anchor. Target 4,500 body words (3,800 honest-short floor). Use only ✓ VERIFIED sources. Forbidden-vocab discipline applies as always; "leverage" remains permitted only as Meadows's noun.

3. **`/voice-check ch03`** — calibrate against Robinson / Berger / Meadows. The reference-chapter mode is at risk of becoming list-like; pay particular attention to whether the definitions are paragraphed as prose rather than bullets, and whether the examples are concrete and earned. Commit: `drafts: voice calibration pass on ch03`.

4. **`/review ch03`** — full pass against the style guide and the 2040 frame. Be especially hard on the abstraction-before-example rule, since this is the chapter most prone to it. Commit: `drafts: review pass on ch03 (N findings addressed)`.

5. **(Stretch goal — only if time and energy permit)** Begin **`/verify Chapter 4 sources`** (Singer *On the Contented Life* re-verification, Ackoff & Emery *On Purposeful Systems*, Pearl & Mackenzie *The Book of Why*) to unblock Ch 4 — *Causation Reconsidered* — for the next session after this. Do not draft Ch 4 in this session unless explicitly directed.

6. End of script. Run `/end-session`, push to `origin/main`, tag the milestone if appropriate (a v0.5 tag would suit completion of Ch 3 — half of Part I drafted), summarise to director.

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
| Batch 3 | Chapter 8 sources (creators, 7 sources) | **complete — 7 ✓ / 0 ⏳ / 0 ✗** (2026-04-25) |
| Ch 3 supporting | Chapter 3 sources (Bertalanffy, Wiener, Holland — 3 sources) | **complete — 3 ✓ / 0 ⏳ / 0 ✗** (2026-04-25) |
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
