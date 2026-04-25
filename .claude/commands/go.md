# /go — Master entry point

Single command for any new session. Reads the full project state, recalls the prime directives, and proceeds through the queued next-session script autonomously — committing per unit of work, pushing at the end.

The director's pattern is to type `/go` and expect the AI to do everything correctly without per-step confirmation. Honour that pattern. Do not pause to ask permission between steps unless a step explicitly says "wait for director" or you hit a real blocker.

---

## 1. Read these files, in this order

Read every file in full before doing any other work. Do not skim. Do not summarise back.

1. `CLAUDE.md` — standing operating instructions, slash-commands table, naming-caution note, standing-authorisation pattern.
2. `docs/00_PROJECT_BRIEF.md` — what the book is and why.
3. `docs/01_OUTLINE.md` — chapter structure and word targets.
4. `docs/02_STYLE_GUIDE.md` — voice rules, forbidden vocabulary, Oxford referencing format.
5. `docs/03_DECISIONS.md` — every decision settled (canonical editions, authorship model, citation discipline, length floor).
6. `docs/04_PROGRESS.md` — current state, drafting status, citation verification status, and the **next-session script** at the top.
7. `docs/06_SOURCES.md` — verified-source pool. **Only ✓ VERIFIED entries may be cited in any draft.**

After reading all seven, confirm in **one sentence** that you have absorbed the project state. Do not summarise.

---

## 2. Recall the prime directives before doing any writing

These are not soft guidelines. They are the disciplines the book commits to. Re-state them to yourself before drafting or revising any section.

1. **Citations must not be invented.** Use only sources marked ✓ VERIFIED in `06_SOURCES.md`. When a claim needs a source not in the verified pool, flag it inline as `[SOURCE NEEDED: brief description]` and resolve via web search before the section is finalised. Inventing a citation kills the book.
2. **No direct quotation without a verified page number.** Per `03_DECISIONS.md` (2026-04-25), drafts paraphrase the canonical primaries rather than quoting from them, until specific page numbers are checked against physical or scanned copies of the cited editions. Paraphrase. Cite the work in a footnote. Do not invent a page number.
3. **The 2040 frame is structural, not stylistic.** Every sentence is written for a reader in 2040, not 2026. No specific 2026 company names, AI lab names, political figures, current platforms, or current controversies. AI is named only as a class of technology. Anchor in long traditions. Predictions go on the record with dates attached.
4. **The forbidden vocabulary is absolute.** The list in `02_STYLE_GUIDE.md` is non-negotiable. "Leverage," "unpack," "deep dive," "in today's world," "fundamentally," "in essence," "synergy," "navigate" (as metaphor), "journey" (non-travel), "ecosystem" (non-biological), "disrupt," and the rest of the consultant / TED tells do not appear in the book. **Sweep your own draft after writing.** Sweep again after any expansion.
5. **Voice is calm authority.** No throat-clearing. No exclamation points. No rhetorical questions unless answered immediately with substance. No "happy to help." The voice of someone who has thought about this for thirty years. Closer to Marilynne Robinson, John Berger, and Donella Meadows than to a TED talk.
6. **Length floor over length target.** The 4,500-word chapter target is a target. A chapter at 3,800 that says everything it needs to say is finished. Do not pad. Per `03_DECISIONS.md`, padding the most exposed chapters (predictions, closing arguments) would weaken the discipline they model — director may permit shorter chapters where density is genuine.
7. **`/review` is the project's pass, not `/ultrareview`.** `/ultrareview` is Claude Code's built-in *cloud multi-agent review of a git branch* — paid, user-triggered, irrelevant to the in-session writing workflow. The project's review command is `/review`, defined in `.claude/commands/review.md`. Do not substitute one for the other.

---

## 3. Run the next-session script in `docs/04_PROGRESS.md`

The "Next session — when the director says 'go', run this script in order" section at the top of `04_PROGRESS.md` is the queue. Run it.

For each numbered step:

1. State to the director, in one short sentence, what you are about to do (e.g. "Running /voice-check on Ch 1.").
2. Do the step. For draft commands, follow the full pre-flight / drafting / post-flight protocol in `.claude/commands/draft.md`. For verification, follow `.claude/commands/verify.md`. For voice-check, follow `.claude/commands/voice-check.md`. For review, follow `.claude/commands/review.md`.
3. Update `docs/04_PROGRESS.md` (word counts, status table, last-touched dates).
4. Commit with the scope-prefixed message format from `CLAUDE.md` (`drafts: …`, `ch02: …`, `sources: …`, `meta: …`).
5. Move immediately to the next step.

Do not pause between steps for confirmation. The director has standing-authorised the script. Pause only if:
- A step explicitly says "wait for director."
- You hit an unresolved `[SOURCE NEEDED]` flag that requires web verification.
- You discover an editorial decision the director has not made.
- You catch yourself about to violate one of the prime directives.
- The director interrupts.

---

## 4. End-of-session protocol

When the script is complete (or when the director says to wrap):

1. Run the steps in `.claude/commands/end-session.md` — update `04_PROGRESS.md` last-session entry and next-session script, log any decisions in `03_DECISIONS.md`, final commit.
2. Push to `origin/main`: `git push origin main`.
3. If the session crossed a meaningful milestone (a part complete, half the book drafted, all chapters first-drafted), tag it: `git tag -a vX.Y.Z -m "..."` and `git push origin vX.Y.Z`.
4. Summarise the session for the director in 3–5 sentences per the format in `end-session.md`. No padding, no encouragement, no flourishes.

---

## 5. What "do not hallucinate" means here, operationally

- If you are not certain a source exists, flag `[SOURCE NEEDED: …]` and verify via web search. Do not cite it from memory.
- If you are not certain a page number is correct, paraphrase. Do not invent the number.
- If you are not certain a quotation is accurate, paraphrase. Do not approximate.
- If you are not certain whether a slash command exists in this project, check `.claude/commands/`. Do not invoke a command name you have not verified (this is how `/ultrareview` got mistaken for `/review`).
- If you are not certain whether a fact is true, say so plainly. The book commits to "default to honesty when you don't know something" (see `CLAUDE.md`).
- If you have invented anything in your own output, mark it as your own and cut it on the next pass.

---

## 6. If something is genuinely unclear

Re-read `CLAUDE.md` and `docs/00_PROJECT_BRIEF.md`. Default to caution on citations. Default to cutting on length. Default to the simpler word. Default to honesty when you don't know something.

When the director is wrong about something the book commits to, push back. Diplomatic capitulation makes worse books.
