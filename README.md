# Thinking in Wholes

*A serious nonfiction book on systems thinking, written in 2026 for readers in 2040.*

---

## What this is

This repository is the complete production of a book called *Thinking in Wholes*. The book builds on the work of Russell L. Ackoff, Donella H. Meadows, Peter Senge, and the wider systems-thinking tradition, and addresses a reader in the year 2040.

It is a working repo, not a finished book. Drafts, decisions, verified sources, voice calibrations, and citation audits are all committed publicly as the book is written. The git history is the book's record of itself.

---

## How this book is being written

**The book is written by Claude (Anthropic) under human direction.**

The human directs at the level of vision, scope, structure, and standards. Claude does the writing — drafting, researching, citing, revising, polishing — against those standards. Every decision is logged in `docs/03_DECISIONS.md`. Every citation is verified via web search before it appears in a draft. Nothing is hidden.

This is an experiment in open AI-authored nonfiction. We are not pretending the prose is human-written. We are also not pretending it is automatic. The book is the product of careful, repeated direction against a set of explicit standards.

---

## The 2040 frame

The book is written in 2026 but addressed to a reader in 2040. This is a structural commitment, not a stylistic flourish. It means:

- No period-piece references that will date the book — no specific 2026 company names, AI lab names, current political figures, current controversies.
- Anchoring in long traditions and durable patterns.
- Predictions made on the record, so a 2040 reader can grade them.
- Blind spots named in advance, so the reader knows what to discount.

If a sentence would feel dated by 2032, it does not survive the next pass.

---

## Repository structure

```
.
├── CLAUDE.md              Operating instructions for Claude Code (read every session)
├── README.md              This file
├── LICENSE                CC BY 4.0
├── .gitignore
├── .claude/
│   └── commands/          Slash commands for the workflow
│       ├── start.md
│       ├── verify.md
│       ├── draft.md
│       ├── review.md
│       ├── source-needed.md
│       ├── voice-check.md
│       └── end-session.md
├── docs/
│   ├── 00_PROJECT_BRIEF.md    The north-star document
│   ├── 01_OUTLINE.md          14 chapters in 4 parts + preface, afterword, glossary
│   ├── 02_STYLE_GUIDE.md      Voice rules, forbidden vocabulary, Oxford referencing
│   ├── 03_DECISIONS.md        Append-only decisions log (settled and open)
│   ├── 04_PROGRESS.md         Current state, drafting status, verification status
│   └── 06_SOURCES.md          Bibliography with verification status (✓ / ⏳ / ✗)
├── source/
│   └── thinking_in_wholes.md  The original primer this book builds from
└── drafts/
    └── (chapter drafts as written)
```

---

## How the workflow runs

The work happens via Claude Code, using the slash commands in `.claude/commands/`:

1. **`/start`** — at the start of every session, Claude reads the project state and reports the next useful step.
2. **`/verify <batch>`** — verifies a batch of bibliographic sources via web search. Updates `docs/06_SOURCES.md` markers.
3. **`/draft <section>`** — drafts a preface or chapter. Uses only verified sources. Flags any unverified claim as `[SOURCE NEEDED]`.
4. **`/review <section>`** — reviews a draft against the style guide and the 2040 frame.
5. **`/source-needed <section>`** — resolves open `[SOURCE NEEDED]` flags by web-verifying real sources.
6. **`/voice-check <section>`** — calibrates the prose against Robinson, Berger, and Meadows.
7. **`/end-session`** — updates progress, logs decisions, final commit, summarizes.

The full operating instructions live in `CLAUDE.md`.

---

## Status

| Phase | Status |
|---|---|
| Setup and standards | Complete |
| Citation verification — Batch 1 (foundational canon, 18 sources) | Complete (17 ✓ / 1 ⏳) |
| Citation verification — Batch 2 (Chapter 1, 6 sources) | Complete (6 ✓) |
| Citation verification — Batch 8 (Chapter 14, 3 sources) | Complete (3 ✓) |
| Citation verification — Batches 3–7 | Pending |
| Preface | First draft (voice-checked + reviewed) — 2,336 body words |
| Chapter 1 — *The Cartesian Wound* | First draft — 3,824 body words |
| Chapter 14 — *What 2040 Will Have Learned* | First draft — 3,278 body words |
| Chapters 2–13, afterword, glossary | Pending |
| **Total drafted** | **9,438 / ~70,000 body words** |

Live status in [`docs/04_PROGRESS.md`](docs/04_PROGRESS.md).

---

## License

This work is licensed under a **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

You are free to share and adapt the work, including for commercial purposes, provided you give appropriate credit. Full license: [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)

Required attribution:

> *Thinking in Wholes*. Written by Claude (Anthropic) under human direction, 2026.

---

## Contributing and corrections

Found a hallucinated citation, a dated reference, a voice drift, or an argument that doesn't hold up? Open an issue or a pull request. This is an open project — the book gets better the more eyes are on it.

Particular help is welcome on:

- **Citation accuracy.** Especially for primary sources where bibliographic details matter (publisher, edition, page numbers for direct quotes).
- **Subject-matter pushback.** If you know the systems-thinking tradition deeply and we are getting something wrong, say so.
- **The 2040 check.** If a passage feels period-bound to 2026, flag it.

---

## Acknowledgments

This book stands on the shoulders of Russell L. Ackoff, Donella H. Meadows, Peter Senge, Edgar A. Singer Jr., Jay W. Forrester, Christopher Alexander, Jane Jacobs, C. West Churchman, Stafford Beer, Alfred North Whitehead, and the wider systems-thinking tradition. Their primary works are cited throughout and listed in `docs/06_SOURCES.md`.
