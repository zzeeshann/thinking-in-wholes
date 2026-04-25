# Thinking in Wholes — Progress

> **Updated each session via `/end-session`.** The most volatile file in the project. When in doubt, this file tells you where we are and what to do next.

---

## Current phase

**SETUP COMPLETE → READY FOR CITATION VERIFICATION**

All open questions are resolved. Repository is structured for Claude Code. Standing instructions are in `../CLAUDE.md`. The next session begins citation verification, which gates the start of drafting.

---

## Last session

**Date:** 2026-04-25
**Did:**
- Converted source primer from `.docx` to `.md` (now in `source/`)
- Designed the architecture: 14 chapters in 4 parts + preface + afterword + glossary + references
- Wrote the project documentation suite (`docs/00`–`06`)
- Decided authorship model: AI writes, human directs
- Decided citation method: Oxford referencing
- Established citation hallucination protocol: pre-verification of every source
- Resolved primary audience (creators), preface voice (meditative essay), author voice (third person with rare "I")
- Decided license: CC BY 4.0
- Built Claude Code-ready repository structure
- Created `CLAUDE.md`, `README.md`, `LICENSE`, `.gitignore`
- Created seven slash commands in `.claude/commands/`

**Where we left off:** Setup complete. All standards locked. Ready to begin citation verification batch 1 (foundational sources).

---

## Next session — what to do first

1. Run `/start` — Claude Code reads the project state.
2. Run `/verify Batch 1 — foundational systems-thinking canon` — this verifies the ~15 most-used sources (Ackoff, Meadows, Senge, Forrester, Singer, Alexander, Jacobs, Churchman, Beer, Whitehead, Bergson, plus a few others). All are currently ✗ UNVERIFIED.
3. Once Batch 1 has produced a real verified pool, run `/draft preface` to begin the book.

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
| Batch 1 | Foundational systems-thinking canon (~15 sources) | not started |
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
