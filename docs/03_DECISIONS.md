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

### 2026-04-25 — No direct primary-source quotation until page numbers are verified
**Decision:** Drafts paraphrase the canonical primary texts rather than quoting from them, until specific page numbers can be verified against physical or scanned copies of the cited editions.
**Reasoning:** The style guide is unambiguous: every direct quotation requires a page number in the footnote, and no exception is allowed. Web verification has confirmed the works' bibliographic data and the cited editions, but page numbers for specific passages have not been independently checked. Paraphrase is therefore the disciplined choice. A future pass — once physical or scanned access to the cited editions is available — can convert specific paraphrases into quotations where the prose would benefit. The preface, Ch 1, and Ch 14 were all drafted under this discipline.

### 2026-04-25 — Length floor over length target
**Decision:** When a chapter completes its argument under the 4,500-word target, the call defaults to "stop and don't pad." The style guide's "honest short" floor (3,800) is a guide, not a hard line — Ch 14 was committed at 3,278 body words because the chapter is the book's most exposed (it puts predictions on the record), and padding the most exposed chapter to hit a target would weaken the discipline the chapter is trying to model.
**Reasoning:** Length discipline is a quality discipline, not a productivity discipline. A chapter that says everything it needs to say is finished, regardless of whether its body word count crosses an arbitrary threshold. Director may override on a per-chapter basis where the chapter is genuinely thin rather than dense.

### 2026-04-25 — Two open edition decisions deferred to director
**Decision:** Two editorial decisions surfaced during Batch 1 verification remain explicitly unresolved: (a) Senge, *The Fifth Discipline*, 1990 first edition vs 2006 revised edition; (b) Whitehead, *Process and Reality*, 1929 Macmillan first vs 1978 Griffin/Sherburne corrected edition. The writer can draft preface, Ch 1, and Ch 14 without resolving either, but Ch 5/6 (Senge) and Ch 11 (Whitehead) cannot be drafted until they are resolved.
**Reasoning:** The decisions are editorial judgments about scholarly convention that belong to the director, not the writer. Both editions are real and citable; the question is which is canonical for this book.
**Resolved 2026-04-25 (delegated to AI by director):** See the two entries immediately following.

### 2026-04-25 — Senge canonical edition
**Decision:** Cite *The Fifth Discipline*, 1990 first edition (New York: Doubleday/Currency) as the canonical primary throughout the book. The 2006 revised edition (New York: Currency / Doubleday Business) is admissible when the point being made is Senge's later self-correction or his updated examples; in those cases, cite both editions explicitly.
**Reasoning:** The brief commits to engaging thinkers as primary texts. The 1990 first edition is the work that shaped the field of organisational learning over the following sixteen years; it is what Senge's interlocutors and critics responded to; it is the historical primary. The 2006 revision is Senge's response to that reception — valuable, but a second-order text. Citing the 1990 is the conservative scholarly convention.

### 2026-04-25 — Whitehead canonical edition
**Decision:** Cite *Process and Reality*, 1978 corrected edition, ed. David Ray Griffin and Donald W. Sherburne (New York: Free Press), as the cited edition for all quotations and page references. The 1929 Macmillan first edition is preserved in the bibliography as the original publication, with a note pointing to the 1978 corrected edition as the citing text.
**Reasoning:** The 1929 first edition contains documented textual inaccuracies; the 1978 Griffin/Sherburne corrected edition exists to fix them and is the scholarly standard for process philosophy. Citing the 1929 first edition would mean reproducing known errors when the corrected text is widely available. *Science and the Modern World* (1925) — Whitehead's other work cited in the foundational pool — has no comparable corrected edition issue and is cited from the 1925 Macmillan as before.

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

### 2026-04-25 — Working production session 1 (initial bootstrap → three drafts banked)
- Local git repository initialised on `main`; nine commits made in working order.
- Bibliographic corrections during Batch 1 verification:
  - *A Pattern Language* author list expanded to include Jacobson, Fiksdahl-King, and Angel (were missing as credited co-authors).
  - Singer death year corrected in `00_PROJECT_BRIEF.md` from 1955 to 1954.
  - Beer *Brain of the Firm* 1972 noted to have separate UK (Allen Lane the Penguin Press) and US (Herder and Herder) first editions; UK retained as primary citation.
- Bibliographic corrections during Batch 2 verification:
  - Newton *Principia* publisher corrected from "Royal Society" to "Joseph Streater, for the Royal Society of London"; Streater was the printer.
- Standard modern scholarly editions specified for the three Ch 1 historical primaries:
  Descartes via Cottingham/Stoothoff/Murdoch (Cambridge UP, 1985);
  Newton via Cohen/Whitman (UC Press, 1999);
  Smith via the Glasgow Edition (Oxford/Clarendon, 1976).
- Batch 1 (foundational systems-thinking canon, 18 entries): 17 ✓ / 1 ⏳.
- Batch 2 (Cartesian lineage, 6 entries): 6 ✓.
- Batch 8 (predictions and futures, 3 entries): 3 ✓.
- Three first drafts banked: preface (2,336 body), Ch 1 (3,824 body), Ch 14 (3,278 body); 9,438 body words total. The preface received a voice-check + review pass.
