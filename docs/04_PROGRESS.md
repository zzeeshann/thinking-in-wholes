# Thinking in Wholes — Progress

> **Updated each session via `/end-session`.** The most volatile file in the project. When in doubt, this file tells you where we are and what to do next.

---

## Current phase

**FIVE SECTIONS BANKED + REVIEWED · CH 3 ADDED · BATCHES 1, 2, 3, 8, CH-3, CH-4 VERIFIED · CH 4 AND CH 8 NOW DRAFTING-READY · ALL OPEN DECISIONS RESOLVED**

Five sections committed, opening through closing: preface, Ch 1 — *The Cartesian Wound*, Ch 2 — *The Three Returns*, Ch 3 — *The Anatomy of a System*, and Ch 14 — *What 2040 Will Have Learned*. All five are voice-checked and reviewed against `02_STYLE_GUIDE.md` and the 2040 frame. Total drafted body: 16,796 words (preface 2,336 + Ch 1 3,824 + Ch 2 3,609 + Ch 3 3,749 + Ch 14 3,278); 18,490 with footnotes. Thirty-eight footnotes total, all from the verified pool. Zero unresolved `[SOURCE NEEDED]` flags. One further editorial decision resolved by AI under director delegation this session: Wiener *Cybernetics* — cite the 1961 second edition (Cambridge, MA: MIT Press; New York: John Wiley & Sons) as canonical (1948 Hermann/Wiley first edition noted as historical original; reasoning analogous to the Whitehead 1978 corrected-edition resolution). Logged in `03_DECISIONS.md` and locked in `06_SOURCES.md`. No open decisions remain. Ch 4 — *Causation Reconsidered* — is now drafting-ready (its supporting batch was verified as a stretch goal at the end of this session, with Singer *On the Contented Life* promoted from ⏳ PARTIAL to ✓ VERIFIED). Ch 8 remains drafting-ready. Ch 5–7, 9–13 still need their respective citation batches before they can be drafted.

---

## Last session

**Date:** 2026-04-25 (working session 3 — `/go` script run)
**Did:**
- Ran the Chapter 3 supporting verification batch (Bertalanffy *General System Theory* 1968, Wiener *Cybernetics*, Holland *Emergence* 1998). Result: **3 ✓ VERIFIED, 0 ⏳ PARTIAL, 0 ✗ UNVERIFIED.** Bibliographic correction caught and resolved: the previous `06_SOURCES.md` entry for Wiener mis-attributed the 1948 first edition to "Cambridge, MA: MIT Press, 1948" — the actual 1948 first edition was Paris: Hermann et Cie / New York: John Wiley & Sons (American printing offset from the French sheets), in the *Actualités Scientifiques et Industrielles* series no. 1053; MIT Press did not co-publish *Cybernetics* until the 1961 second edition. One editorial edition decision resolved by AI under standing director delegation: Wiener *Cybernetics* — cite the 1961 second edition (MIT Press / Wiley) as canonical, with the 1948 Hermann/Wiley first edition preserved in the bibliography as the original publication. Reasoning analogous to the Whitehead 1978 corrected-edition resolution: the 1961 second edition corrects the documented typographical errors of the 1948 first and adds two substantive chapters on learning and self-organising systems that have themselves become canonical.
- Drafted Chapter 3 — *The Anatomy of a System* — at 3,749 body words / 4,286 with footnotes. Thirteen footnotes, all from the verified pool (Bertalanffy, Holland, Wiener 2nd ed., Meadows, Forrester, Gharajedaghi, Beer, Ackoff). Structure: opening on the appendix-in-the-body as the model of part-in-whole; seven concepts in sequence (emergence, feedback (reinforcing and balancing, with a body-level treatment of Forrester's stocks/flows formalism), delay, hierarchy, boundary, purpose (with an Ackoff-design constructive sequel), resilience); closing on the convergence of mid-twentieth-century systems traditions and what the vocabulary makes visible. Each definition earns its place by appearing after a concrete example, per the abstraction-after-example rule in `02_STYLE_GUIDE.md`. The maker's-emergence paragraph ties the chapter to the primary audience without breaking the reference register.
- `/voice-check` pass on Ch 3: three voice-calibration cuts to bring the chapter closer to Robinson/Berger/Meadows (cut the Purpose section's triple-parallel announcement opener; cut "This is among the most uncomfortable concepts the chapter offers, because it strips a particular kind of cover from a particular kind of failure."; cut "What delays do to behaviour is consistent." and "The corollary is the most demanding move in systems thinking." — all performative meta-commentary the touchstones would not allow).
- `/review` pass on Ch 3: two abstraction-before-example violations corrected. Boundary section reordered so the cell-membrane example leads, then *boundary* is named; Resilience section reordered so the forest/body/institution/language cluster leads, then *resilience* is named (also cut the bookkeeping opener "The last term in this chapter's working vocabulary is..."). All other categories swept clean (forbidden vocabulary, period-piece references, rhetorical-questions-not-answered, open SOURCE NEEDED flags, Oxford footnote format).
- **Stretch goal completed:** Ran the Chapter 4 supporting verification batch (Singer *On the Contented Life* 1936 re-verify, Singer *Experience and Reflection* 1959, Ackoff & Emery *On Purposeful Systems* 1972, Pearl & Mackenzie *The Book of Why* 2018). Result: **4 ✓ VERIFIED, 0 ⏳ PARTIAL, 0 ✗ UNVERIFIED.** Singer *On the Contented Life* promoted from ⏳ PARTIAL to ✓ VERIFIED on the strength of the Wikipedia and Penn Archives concurrence on the 1936 year (the 1937 academic reviews are normal review-lag from a late-1936 publication). Chapter 4 — *Causation Reconsidered* — is now drafting-ready.

**Where we left off:** Five sections banked and reviewed (preface, Ch 1, Ch 2, Ch 3, Ch 14); 16,796 body words drafted, ~24.0% of the ~70,000-word target. Six citation batches complete (Batch 1 foundational, Batch 2 Ch 1, Batch 3 Ch 8, Batch 8 Ch 14, Ch-3-supporting, Ch-4-supporting). Ch 4 and Ch 8 are both drafting-ready. The most natural next move is Ch 4 — *Causation Reconsidered* — which has its full source pool verified and which advances the Inheritance arc of Part I in numerical sequence.

---

## Next session — single command, then autonomous

**Director types `/go` (defined in `.claude/commands/go.md`). Nothing else needed.**

The `/go` command reads the full project state, recalls every prime directive (citation discipline, 2040 frame, voice rules, forbidden vocabulary, no-direct-quotation rule, length floor, `/review` ≠ `/ultrareview`), then runs the script below autonomously — committing per unit, pushing at the end. No per-step confirmation required. Director may interrupt at any time; an interruption overrides the script.

If the director prefers manual control, type `/start` instead — it does only the file-reading and waits for direction.

### The script `/go` runs

1. **`/draft ch04`** — *Causation Reconsidered*. The Singer chapter — Singer's producer-product relationship as the philosophical inheritance behind Ackoff's purposes, the limits of "what caused this?" as a question for connected systems, the acorn and the oak, multiple causation, contributory conditions, the ethics of explanation, and the way blame (even when accurate) fails to change what produced the harm. The chapter draws on the foundational Batch 1 pool (Ackoff for the producer-product line, the cybernetic tradition for the formal apparatus) plus the Ch 4 supporting batch verified at the end of session 3 (Singer *On the Contented Life* 1936, Singer *Experience and Reflection* 1959, Ackoff & Emery *On Purposeful Systems* 1972, Pearl & Mackenzie *The Book of Why* 2018). Target 4,500 body words (3,800 honest-short floor). Use only ✓ VERIFIED sources. The no-direct-quotation discipline applies. Forbidden-vocab sweep on completion.

2. **`/voice-check ch04`** — calibrate against Robinson / Berger / Meadows. The risk in this chapter is academic-philosophy register; the touchstones write about philosophy without becoming philosophical-prose dry. Commit: `drafts: voice calibration pass on ch04`.

3. **`/review ch04`** — full pass against the style guide and the 2040 frame. Be especially hard on the abstraction-before-example rule and on any tendency to treat Singer as a name-drop rather than as a primary text. Commit: `drafts: review pass on ch04 (N findings addressed)`.

4. **`/verify Batch 4` — Chapter 9 sources (architecture)** to unblock Ch 9. The Ch 9 source list in `06_SOURCES.md` shows three ✗ UNVERIFIED entries (Alexander *The Nature of Order* 4 vols. 2002–2004; Jacobs *The Economy of Cities* 1969; Brand *How Buildings Learn* 1994). Alexander *A Pattern Language* 1977 and *The Timeless Way of Building* 1979 are already ✓ VERIFIED in the foundational Batch 1 pool. The 4-volume *Nature of Order* will need careful per-volume verification. Update `06_SOURCES.md` markers and add a verification log entry. Commit: `sources: verify Batch 4 — Chapter 9 sources (architecture) (N verified, M partial, K unverified)`.

5. **(Stretch goal — only if time and energy permit)** Begin **`/verify Batch 5` — Chapter 10 sources (engineering)** (Petroski *To Engineer Is Human* 1985, Perrow *Normal Accidents* 1984, Leveson *Engineering a Safer World* 2011, Vincenti *What Engineers Know* 1990) to unblock Ch 10. Do not draft Ch 10 unless explicitly directed.

6. End of script. Run `/end-session`, push to `origin/main`, tag the milestone if appropriate (a v0.5 tag would suit completion of Part I — Ch 4 closes Part I, *The Inheritance*), summarise to director.

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
| Ch 3 — The Anatomy of a System | voice-checked + reviewed | 3,749 body / 4,286 with footnotes | 2026-04-25 |
| Ch 4 — Causation Reconsidered | voice-checked + reviewed | 3,688 body / 3,974 with footnotes | 2026-04-25 |
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

**Total drafted:** 20,484 / ~70,000 words (preface 2,336 + Ch 1 3,824 + Ch 2 3,609 + Ch 3 3,749 + Ch 4 3,688 + Ch 14 3,278, body counts; 22,464 with footnotes)

---

## Citation verification status

| Batch | Description | Status |
|---|---|---|
| Batch 1 | Foundational systems-thinking canon (18 sources) | **complete — 17 ✓ / 1 ⏳ / 0 ✗** (2026-04-25) |
| Batch 2 | Chapter 1 sources (Cartesian lineage, 6 sources) | **complete — 6 ✓ / 0 ⏳ / 0 ✗** (2026-04-25) |
| Batch 3 | Chapter 8 sources (creators, 7 sources) | **complete — 7 ✓ / 0 ⏳ / 0 ✗** (2026-04-25) |
| Ch 3 supporting | Chapter 3 sources (Bertalanffy, Wiener, Holland — 3 sources) | **complete — 3 ✓ / 0 ⏳ / 0 ✗** (2026-04-25) |
| Ch 4 supporting | Chapter 4 sources (Singer × 2, Ackoff & Emery, Pearl & Mackenzie — 4 sources) | **complete — 4 ✓ / 0 ⏳ / 0 ✗** (2026-04-25) |
| Batch 4 | Chapter 9 sources (architecture, 3 sources) | **complete — 3 ✓ / 0 ⏳ / 0 ✗** (2026-04-25) |
| Batch 5 | Chapter 10 sources (engineering, 4 sources) | **complete — 4 ✓ / 0 ⏳ / 0 ✗** (2026-04-25) |
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
