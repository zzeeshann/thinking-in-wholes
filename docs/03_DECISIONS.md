# Thinking in Wholes — Decisions Log

> **Append-only.** When a decision is made, add it with date and reasoning. When an open question is resolved, do not delete it — move it from OPEN to DECIDED, with the date and reasoning. This file is the project's memory.

---

## DECIDED

### 2026-04-25 — Title
**Decision:** *Thinking in Wholes* (carried from primer).
**Reasoning:** Clear, plain, available, accurate to the argument. Subtitle TBD.

### 2026-04-25 — Frame
**Decision:** Written in 2026, addressed to a reader in 2040.
**Reasoning:** Forces the prose out of the news cycle and into long-form patterns. Liberates from period-piece references. Creates a falsifiability discipline (predictions on the record).

### 2026-04-25 — Length
**Decision:** Target 60,000–80,000 words (~70k working).
**Reasoning:** Long enough to argue, short enough to read. Schumacher length, not Pinker length.

### 2026-04-25 — Structure
**Decision:** Preface + 14 chapters in 4 parts + afterword + glossary + references.
**Reasoning:** Four parts give the book a clear arc — inheritance, pathology, application, practice. Fourteen chapters give room without bloat.

### 2026-04-25 — Lineage
**Decision:** Primary engagement with Ackoff, Meadows, Senge, Singer, Forrester, Alexander, Jacobs, Churchman, Beer, Whitehead, Bergson.
**Reasoning:** This is the canon the book is built on. Each will be read as a primary text, not a summary.

### 2026-04-25 — Banned vocabulary
**Decision:** Specific list of forbidden words and phrases (see `02_STYLE_GUIDE.md`).
**Reasoning:** Each one is a tell — for consultant prose, TED-talk prose, or self-help prose. The book is none of these.

### 2026-04-25 — Authorship model
**Decision:** AI (Claude, Anthropic) writes the book; human directs at the level of vision, scope, structure, and quality.
**Reasoning:** Author's choice. Drives all command design. Shifts AI's role from collaborator to executor under standards. Quality control is self-enforced by AI; human is editor of last resort.

### 2026-04-25 — Citation method
**Decision:** Oxford referencing — footnotes (continuous within chapter) with full first-citation, short-form subsequent, bibliography at end.
**Reasoning:** Author's choice. Standard for serious nonfiction. Allows discursive notes when needed; signals the book takes evidence seriously without impeding the prose.

### 2026-04-25 — Citation hallucination protocol
**Decision:** AI must not invent citations. Only sources marked ✓ VERIFIED in `06_SOURCES.md` may be cited in drafts. Unverified claims are flagged inline as `[SOURCE NEEDED: description]` and resolved via web search before the chapter is finalized.
**Reasoning:** AI hallucination of citations is the single largest risk to the book's credibility. Pre-verification is slower but it is the only protocol that produces a publishable book.

### 2026-04-25 — Primary audience (resolves Q1)
**Decision:** Creators (writers, artists, designers, filmmakers, musicians) as primary audience. Architects, engineers, philosophers in priority order behind.
**Reasoning:** Gives the book the broadest reach. Allows the most permission for beautiful, image-rich prose without sacrificing rigor. Architects and engineers can read prose written for creators; the reverse is harder. Philosophers will read it regardless if the thinking is real.

### 2026-04-25 — Preface voice (resolves Q3)
**Decision:** Meditative essay (a quiet walk into the central problem, with the 2040 frame embedded but not announced).
**Reasoning:** A formal letter feels gimmicky over 2,500 words. A personal note doesn't fit the calm-authority tone the rest of the book commits to. A meditative essay sets the right voice and earns the reader's trust without performing.

### 2026-04-25 — Author voice (resolves Q5)
**Decision:** Third person throughout, with rare and earned use of "I" only in the preface and afterword.
**Reasoning:** Matches the calm-authority register. The rare first-person moments will land harder for being rare.

### 2026-04-25 — License
**Decision:** Creative Commons Attribution 4.0 International (CC BY 4.0).
**Reasoning:** Maximum openness. Anyone can share, adapt, and use the work commercially with attribution. CC BY-SA was considered but rejected — copyleft on a book restricts adaptation more than it helps. CC BY-NC was considered and rejected — non-commercial restrictions limit reach without serving the book's purpose. CC BY 4.0 is the standard "fair game" license for open knowledge work.

### 2026-04-25 — Required attribution wording
**Decision:** *"Thinking in Wholes. Written by Claude (Anthropic) under human direction, 2026. Licensed under CC BY 4.0."*
**Reasoning:** Honest about AI authorship. The 2040 reader will see how the book was made. Transparency is part of the book's integrity.

### 2026-04-25 — Production tooling
**Decision:** Claude Code, with version control via git. Slash commands in `.claude/commands/` define the workflow.
**Reasoning:** Claude Code can execute the workflow autonomously — read project state, run web searches for citation verification, edit files in place, commit to git. This is closer to the production process the book needs than copy-paste prompting in chat.

### 2026-04-25 — Repository transparency
**Decision:** All working files (drafts, decisions, sources, progress) are tracked in git from day one. Nothing hidden. Repo is public.
**Reasoning:** "Fair game" — author's stated principle. Aligns with the book's own argument about transparency in connected systems. The git history becomes the book's record of how it was made; the 2040 reader will be able to inspect every step.

---

## OPEN

### Q4 — Subtitle
The primer used "How to Live, Work and Lead in a Connected World." Workable but generic. Decide once the book has a clearer center; revisit after Part I is drafted.

---

## CHANGE LOG (for major revisions to brief, outline, or style)

### 2026-04-25 — Initial setup
- Project created from primer
- Architecture set: 14 chapters in 4 parts + preface, afterword, glossary, references
- Documentation suite written: `00`–`06`
- Style guide established with forbidden vocabulary and Oxford referencing
- Sources file initialized (all entries ✗ UNVERIFIED pending verification batches)

### 2026-04-25 — Authorship and licensing
- Authorship model added: AI writes, human directs
- Citation rigor section added to brief
- License chosen: CC BY 4.0
- Attribution wording set
- Sources file structure updated: verification status markers required (✓/⏳/✗)

### 2026-04-25 — Claude Code production
- Repository structure built for Claude Code workflow
- `CLAUDE.md` created at root with standing operating instructions
- `README.md` created for GitHub-facing transparency
- `LICENSE` file created (CC BY 4.0)
- `.gitignore` created
- Old `05_PROMPTS.md` removed; replaced by slash commands in `.claude/commands/`:
  `/start`, `/verify`, `/draft`, `/review`, `/source-needed`, `/voice-check`, `/end-session`
- Project files reorganized: `docs/` for project documentation, `source/` for the primer, `drafts/` for chapter drafts
