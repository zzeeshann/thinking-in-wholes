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

### 2026-04-25 — Le Guin *Steering the Craft* canonical edition
**Decision:** Cite the 2015 Mariner Books / Houghton Mifflin Harcourt revised edition (Boston) as the canonical primary citation for *Steering the Craft: A Twenty-First-Century Guide to Sailing the Sea of Story*. The 1998 first edition — *Steering the Craft: Exercises and Discussions on Story Writing for the Lone Navigator or the Mutinous Crew* (Portland, OR: The Eighth Mountain Press, 1998) — is preserved in the bibliography as the historical first edition, with a note pointing to the 2015 revised edition as the citing text. **Resolved 2026-04-25 (delegated to AI by director).**
**Reasoning:** The 2015 edition is "completely revised and rewritten" by Le Guin herself, with a new subtitle and updated examples. Like the Whitehead corrected edition, this is a later authorial revision that supersedes the original; the conservative scholarly convention is to cite the most-revised authorial version. Acquiring access to a single edition (the 2015 Mariner) also simplifies any later page-number verification, when the discipline of direct-quotation-with-page-number is engaged.

### 2026-04-25 — Wiener *Cybernetics* canonical edition
**Decision:** Cite *Cybernetics: Or Control and Communication in the Animal and the Machine*, 1961 second edition (Cambridge, MA: MIT Press; New York: John Wiley & Sons), as the citing edition for all in-text references and page numbers. The 1948 first edition — Paris: Hermann et Cie; New York: John Wiley & Sons (American edition printed offset from the French sheets), in the *Actualités Scientifiques et Industrielles* series, no. 1053 — is preserved in the bibliography as the original publication, with a note pointing to the 1961 second edition as the citing text. **Resolved 2026-04-25 (delegated to AI by director).**
**Reasoning:** The 1948 first edition was typeset in France by Hermann et Cie (a specialist mathematics publisher); Wiener was unable to read proofs carefully and the result contained many typographical errors that were repeated in the American Wiley printing and remained uncorrected through subsequent printings until the 1961 second edition. The 1961 second edition (joint MIT Press / Wiley) corrects those typographical errors and adds two substantive chapters — "On learning and self-reproducing machines" and "Brain waves and self-organizing systems" — that have themselves become canonical for cybernetics and early machine-learning theory. Reasoning is analogous to the Whitehead 1978 corrected-edition resolution: cite the corrected, scholarly text; preserve the historical original in the bibliography. Bibliographic correction also caught during verification: the previous `06_SOURCES.md` entry mis-attributed the 1948 first edition to "Cambridge, MA: MIT Press, 1948" — MIT Press did not co-publish *Cybernetics* until the 1961 second edition.

### 2026-04-25 — Tolstoy *What Is Art?* canonical translation
**Decision:** Cite the Aylmer Maude translation of *What Is Art?* in the Hackett Publishing 1995 reprint (Indianapolis), with introduction by Vincent Tomas, as the citing text for all in-text references and page numbers. The 1899 first English edition — trans. Aylmer Maude (London: Walter Scott Ltd., 1899; Tolstoy's preface dated 1898, Maude's introduction dated 1899) — is preserved in the bibliography as the original English-language publication. The contemporary Penguin Classics translation by Richard Pevear and Larissa Volokhonsky (London: Penguin, 1995) is noted as a respected modern alternative but is not the citing text. **Resolved 2026-04-25 (delegated to AI by director).**
**Reasoning:** Aylmer Maude was Tolstoy's authorised English translator and his biographer; he lived near Tolstoy and corresponded extensively with him, and his translation has the historical authority of a translator working in close collaboration with the author. The Hackett 1995 reprint is a clean modern scholarly edition of Maude's translation, with Vincent Tomas's introduction setting the work in context. The Pevear/Volokhonsky 1995 Penguin translation is excellent contemporary work but does not carry Maude's authorial connection. For the late critical writings specifically (as distinct from the novels), the conservative scholarly choice is the Maude translation. Analogous to the Whitehead resolution: cite the modern scholarly reprint of the standard text, preserve the historical original in the bibliography.

---

## OPEN

### Q4 — Subtitle
The primer used "How to Live, Work and Lead in a Connected World." Workable but generic. Decide once the book has a clearer center; revisit after Part I is drafted.

### Q5 — Wittgenstein *Philosophical Investigations* canonical translation
Surfaced 2026-04-25 during Batch 6 verification. The 1953 Basil Blackwell first edition (translator G. E. M. Anscombe; editors Rush Rhees and G. E. M. Anscombe) is bibliographically verified and is the historical primary. The 4th edition (Oxford: Wiley-Blackwell, 2009), with revised translation by P. M. S. Hacker and Joachim Schulte, is widely cited in contemporary Wittgenstein scholarship and is now the standard scholarly edition for new work in the field. The choice between them is contested in the literature: the Whitehead 1978 / Wiener 1961 / Le Guin 2015 / Tolstoy Hackett-1995 precedents — under which AI has resolved similar edition questions under standing director delegation — do not apply here, because in those cases the corrected/revised edition was uncontested scholarly standard. The Hacker/Schulte revision is not. Some Wittgenstein scholars (Cora Diamond, Stephen Mulhall, others in that interpretive lineage) retain Anscombe's translation on the grounds that the Hacker/Schulte revision changes the philosophical sense of specific passages; others (the Wittgenstein-as-philosopher-of-ordinary-language tradition) prefer the revision. Director's call. Resolution required before any direct citation of *Philosophical Investigations* in the Ch 11 draft. The bibliographic data of the 1953 entry is verified either way and the entry stands in `06_SOURCES.md` as ✓ VERIFIED.

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

### 2026-04-25 — Working production session 6 (`/go` script run → Ch 6 banked, Part II two-thirds first-drafted, Batch Ch-7-supporting verified)
- `/go` script of session-5's queued plan run end-to-end. Five commits (drafts complete ch06 first draft; drafts voice calibration pass on ch06; drafts review pass on ch06; sources verify Ch 7 supporting batch; this session-end commit).
- Drafted Ch 6 — *The Loop You're Inside* — at 3,132 body / 3,559 with footnotes; six footnotes, all from the verified pool (Meadows *Thinking in Systems*, Forrester *Industrial Dynamics*, Sterman *Business Dynamics* × 2, Senge *The Fifth Discipline* × 2, Meadows *Leverage Points*, Stroh *Systems Thinking for Social Change*). Structure: pursuer-distancer marriage as the load-bearing opening image; reinforcing-versus-balancing loop vocabulary introduced after the marriage establishes the concept; "Why the loop feels like fate" — the chapter's most consequential perceptual claim, that loops do not announce themselves as loops but as reality; "Why pushing harder fails" — the systems tradition's hardest counter-intuition; "At three scales" — the loop at personal (overwork loop), organisational (customer-loss-and-acquisition-drive loop), and civilisational (arms race / regulatory ratchet / political polarisation) registers; "Naming a loop" — five diagnostic questions and the small library of common archetypes (escalation, shifting the burden, drift to low performance, tragedy of the commons, limits to growth); "Where the leverage is" — Meadows's hierarchy of leverage points paraphrased into ordinary prose; "Interrupting a loop" — Stroh's account of interruption as refusal; closing on the loop as the smallest unit of behaviour over time. Voice-check pass made two tightenings against the touchstones: "Donella Meadows put the observation as carefully as anyone:" reformulated as "The observation is steady in Donella Meadows's writing:" (the "as carefully as anyone" carried a faint ornamental whiff the touchstones do not have); the Senge attribution sentence was packing three moves into one breath and was split into two cleaner sentences. The previously recurring meta-frame patterns ("the chapter argues...", "the lesson is...", roadmap-style closes) were absent from the first draft, having become reflexively avoided across prior chapters. Review pass addressed one finding: footnote 4 had Sterman in full citation form when he had already been first-cited in full in footnote 1; corrected to short form per Oxford rules. One minor concern noted but not addressed: the introduction of "balancing loop" in the thermostat paragraph is mildly abstraction-before-example, but the two sentences function as a single move and the fix would degrade flow. Length 3,132 body — 668 below the 3,800 honest-short floor — committed without padding per the standing length-floor decision; the chapter makes every move the outline asks for plus the three-scales structural addition.
- **Stretch goal completed:** Ran the Ch 7 supporting verification batch (Meadows et al. 1972 *The Limits to Growth*, Meadows et al. 2004 *30-Year Update*, Kahneman 2011 *Thinking, Fast and Slow*). Result: **3 ✓ VERIFIED, 0 ⏳ PARTIAL, 0 ✗ UNVERIFIED.** *The Limits to Growth* 1972 New York: Universe Books confirmed (ISBN 9780876631652; 205 pp.; published 1 January 1972 as a Potomac Associates Book; 10 million+ copies sold in 28 languages; foundational primary text for the global-modelling tradition that grew from the MIT System Dynamics Group's World3 model). *Limits to Growth: The 30-Year Update* 2004 White River Junction, VT: Chelsea Green Publishing confirmed (ISBN 9781931498517 hardcover, 9781931498586 paperback; 368 pp.; published 1 June 2004; author order on the 2004 update — Donella, Jørgen, Dennis — differs from the 1972 first edition's order, with a 1992 mid-point work *Beyond the Limits* (Chelsea Green) sitting between them, noted historically). Kahneman *Thinking, Fast and Slow* 2011 New York: Farrar, Straus and Giroux confirmed (ISBN 9780374275631 hardcover first edition; ISBN 9780374533557 paperback reissue 2013; 499 pp. hardcover; published 25 October 2011; Kahneman awarded the 2002 Nobel Prize in Economic Sciences for the work he and Amos Tversky developed on judgement under uncertainty). No bibliographic discrepancies caught. No editorial decisions surfaced. Chapter 7 — *Delay, Overshoot, and the Grief of Premature Action* — is now drafting-ready alongside the foundational Batch 1 pool (Forrester, Meadows *Thinking in Systems*) and Sterman *Business Dynamics* (the textbook treatment of delay, overshoot, and the bullwhip effect within system dynamics).
- **Part II — *The Pathologies* — is now two-thirds first-drafted** with Ch 5 and Ch 6 banked. Tag candidate at end of session 7: v0.6.0 if Ch 7 banks and Part II is first-draft complete.
- Total drafted at end of session: 26,923 body / 29,674 with footnotes across eight sections (preface + Ch 1 + Ch 2 + Ch 3 + Ch 4 + Ch 5 + Ch 6 + Ch 14). Fifty-nine footnotes total. ~38.5% of the ~70,000-word target. Eleven citation batches complete.

### 2026-04-25 — Working production session 5 (`/go` script run → Ch 5 banked, Part II opened, Batches Ch-5-supporting & Ch-6-supporting verified)
- `/go` script of session-4's queued plan run end-to-end. Six commits (sources verify Ch 5 supporting batch; drafts complete ch05 first draft; drafts voice calibration pass on ch05; drafts review pass on ch05; sources verify Ch 6 supporting batch; this session-end commit).
- Ran the Chapter 5 supporting verification batch (Goodhart 1975, Campbell 1979, Muller 2018): 3 ✓ VERIFIED, 0 ⏳, 0 ✗. Goodhart confirmed as "Problems of Monetary Management: The U.K. Experience," in *Papers in Monetary Economics*, vol. I (Sydney: Reserve Bank of Australia, 1975), originally presented at the RBA's Conference in Monetary Economics in Sydney, July 1975; the conventional academic citation is "Goodhart 1975." Campbell *Evaluation and Program Planning* 2, no. 1 (1979): 67–90 confirmed. Muller *The Tyranny of Metrics* 2018 Princeton, NJ: Princeton University Press, ISBN 9780691174952, 240 pp., confirmed. No editorial decisions surfaced.
- Drafted Ch 5 — *The Tyranny of Local Optima* — at 3,307 body / 3,651 with footnotes; seven footnotes, all from the verified pool. Structure: 142-cars thought experiment as the load-bearing opening image; the same shape outside the factory (medicine that treats organs, schooling that teaches subjects, cities that optimise parts and decline as wholes); Goodhart's law and Campbell's law as the structural reason measurement-driven management corrupts what it measures; three reasons local optimisation persists (the local optimum is measurable while the global is not; the local optimum can be assigned to an individual; the language of local optimisation is the language of professional competence); three commitments the systems tradition recommends instead (subordinate measurement to purpose; design at the level of the whole through Ackoff's *idealised design*; recognise that the part that performs best in isolation is rarely the part that performs best in combination). Voice-check made three cuts of performative meta-commentary against the Robinson/Berger/Meadows touchstones: (a) "This is the lesson of the chapter, and it is older and harder than it looks." opener after the 142-cars passage replaced with "The point is older and harder than it looks."; (b) "The chapter has been about the cost of forgetting that wholes are not assembled from optimised parts. The cost is paid by..." closing meta-summary opener reformulated to lead directly with the substance; (c) the entire roadmap paragraph previewing Ch 6 and Ch 7 cut. Review pass addressed five findings: one residual voice-drift / abstraction-before-example issue at the opening of the measurement section ("the chapter must name them" cut and re-split); two direct-quotation-without-page-number violations (Goodhart's near-exact formulation and Campbell's near-exact formulation paraphrased per the standing no-direct-quotation rule); inconsistent parallel structure in the three-reasons section ("The third *reason* is that..." → "The third is that..."); awkward syntax in the school paragraph callback replaced with the cleaner "The graduate is the school's automobile, assembled from the best parts of unrelated cars." Length 3,307 body — 493 below the 3,800 honest-short floor — committed without padding per the standing length-floor decision; the chapter makes every move the outline asks for plus a structural addition (the three-reasons section).
- **Part II — *The Pathologies* — is now opened with Ch 5 banked.** No tag candidate (the next milestone is Part II first-draft complete after Ch 5, 6, and 7, which will warrant v0.6).
- **Stretch goal completed:** Ran the Chapter 6 supporting verification batch (Sterman *Business Dynamics* 2000, Stroh *Systems Thinking for Social Change* 2015): 2 ✓ VERIFIED, 0 ⏳, 0 ✗. Sterman 2000 Boston: Irwin/McGraw-Hill confirmed (ISBN 9780072389159 with CD-ROM; 982 pp.). Stroh 2015 White River Junction, VT: Chelsea Green Publishing confirmed (ISBN 9781603585804 paperback; 264 pp.). No editorial decisions surfaced. Chapter 6 — *The Loop You're Inside* — is now drafting-ready.
- Total drafted at end of session: 23,791 body / 26,115 with footnotes across seven sections (preface + Ch 1 + Ch 2 + Ch 3 + Ch 4 + Ch 5 + Ch 14). Fifty-three footnotes total. ~34.0% of the ~70,000-word target. Ten citation batches complete.

### 2026-04-25 — Working production session 4 (`/go` script run → Ch 4 banked, Part I first-draft complete, Batches 4 & 5 verified)
- `/go` script of session-3's queued plan run end-to-end. Six commits (drafts complete ch04 first draft; drafts voice calibration pass on ch04; drafts review pass on ch04; sources verify Batch 4 Ch 9 architecture; sources verify Batch 5 Ch 10 engineering; this session-end commit).
- Drafted Ch 4 — *Causation Reconsidered* — at 3,688 body / 3,974 with footnotes; 8 footnotes, all from the verified pool (Singer × 2, Ackoff & Emery, Ackoff *Re-Creating the Corporation*, Meadows *Thinking in Systems*, Churchman *The Systems Approach*, Pearl & Mackenzie *The Book of Why*). Structure: acorn/oak opening on producer-vs-cause; the inherited single-cause model and its institutional sediment; Singer's producer-product revision and the practical discipline of naming contributory conditions; the Ackoff/Emery deepening into purposeful systems; multiple producers and contributory conditions with a worked treatment example; the ethics of explanation, the failure of blame as explanation, and a constructive paragraph on designed accountability as the systems-tradition alternative; an honest assessment of what the Pearl statistical apparatus refines and what it leaves; closing with the four questions the systems tradition asks instead of *what caused this?* Voice-check made two cuts of performative meta-commentary ("The chapter's most uncomfortable consequence is..."; "The systems tradition's contribution at this point is..."); review pass corrected two abstraction-before-example violations (Ackoff/Emery thermostat-vs-purposeful contrast reordered to lead the section; Multiple Producers section's bookkeeping opener dropped, patient-illness example leads with abstraction in a single follow-up sentence) and one awkward-phrasing fix (the closing four-questions block). Length 3,688 body — 112 below the 3,800 honest-short floor — committed without padding per the standing length-floor decision; the chapter makes every move the outline asks for.
- **Part I — *The Inheritance* — is now first-draft complete** (Ch 1–4 all banked + voice-checked + reviewed). Tagged `v0.5.0` to mark the milestone.
- Batch 4 (Chapter 9 sources, 3 entries: Alexander *The Nature of Order* 4 vols., Jacobs *The Economy of Cities* 1969, Brand *How Buildings Learn* 1994). Result: **3 ✓ VERIFIED, 0 ⏳ PARTIAL, 0 ✗ UNVERIFIED.** Bibliographic correction caught and resolved: the Alexander *Nature of Order* date range was 2002–2004 in `06_SOURCES.md`; the actual range is 2002–2005 (Book Three *A Vision of a Living World* was 2005, not 2004). Per-volume titles, ISBNs, and CES series numbers added to the entry.
- Batch 5 (Chapter 10 sources, 4 entries: Petroski 1985 St. Martin's, Perrow 1984 Basic Books, Leveson 2011 MIT Press, Vincenti 1990 Johns Hopkins UP) verified as a stretch goal. Result: **4 ✓ VERIFIED, 0 ⏳ PARTIAL, 0 ✗ UNVERIFIED.** Edition admissibility note added for Perrow: the 1999 Princeton University Press updated edition (with new afterword and Y2K-problem postscript) is admissible when contemporary pagination or the updated material is being cited; the 1984 Basic Books New York remains the historical first edition. Pattern follows the existing Wiener 1961 / Whitehead 1978 / Le Guin 2015 / Tolstoy Hackett-1995 corrected-edition convention; logged as a bibliographic note rather than a new editorial decision.
- Total drafted at end of session: 20,484 body / 22,464 with footnotes across six sections (preface + Ch 1 + Ch 2 + Ch 3 + Ch 4 + Ch 14). Forty-six footnotes total. ~29.3% of the ~70,000-word target. Eight citation batches complete.

### 2026-04-25 — Working production session 3 (`/go` script run → Ch 3 banked, Wiener edition resolved, Ch 4 sources verified)
- `/go` script of session-2's queued plan run end-to-end. Six commits (sources verify Ch 3 supporting; drafts complete ch03 first draft; drafts voice calibration pass on ch03; drafts review pass on ch03; sources verify Ch 4 entries; this session-end commit).
- Ran the Chapter 3 supporting verification batch (Bertalanffy, Wiener, Holland): 3 ✓ VERIFIED, 0 ⏳, 0 ✗. Bibliographic correction caught and resolved on Wiener — the previous `06_SOURCES.md` entry mis-attributed the 1948 *Cybernetics* first edition to MIT Press; the actual 1948 first edition was Paris: Hermann et Cie / New York: John Wiley & Sons in the *Actualités Scientifiques et Industrielles* series no. 1053.
- One new editorial edition decision resolved by AI under standing director delegation: Wiener *Cybernetics* — cite the 1961 second edition (MIT Press / Wiley) as canonical; the 1948 Hermann/Wiley first edition is preserved in the bibliography as the original publication. Reasoning analogous to the Whitehead 1978 corrected-edition resolution: cite the corrected scholarly text, preserve the historical original. The 1961 second edition also adds two substantive chapters on learning and self-organising systems that have themselves become canonical for cybernetics and early machine-learning theory.
- Drafted Ch 3 — *The Anatomy of a System* — at 3,749 body / 4,286 with footnotes; 13 footnotes, all from the verified pool. Structure: opening on the appendix-in-the-body; seven concept sections (emergence, feedback, delay, hierarchy, boundary, purpose, resilience); closing on the convergence of mid-twentieth-century systems traditions. Voice-check pass made three cuts of performative meta-commentary (the Purpose triple-parallel announcement opener; "This is among the most uncomfortable concepts the chapter offers..."; "What delays do to behaviour is consistent." and "The corollary is the most demanding move in systems thinking."). Review pass made two abstraction-before-example fixes (Boundary section reordered to lead with the cell-membrane example; Resilience section reordered to lead with the forest/body/institution cluster). Length 3,749 body — 51 words below the 3,800 honest-short floor — but every cut was structural improvement, not padding-eligible substance; per the standing length-floor decision, committed without padding.
- Stretch goal completed: ran the Chapter 4 supporting verification batch (Singer × 2, Ackoff & Emery, Pearl & Mackenzie). 4 ✓ VERIFIED, 0 ⏳, 0 ✗. Singer *On the Contented Life* promoted from ⏳ PARTIAL to ✓ VERIFIED on the strength of the Wikipedia and Penn Archives concurrence on the 1936 year (the 1937 academic reviews are normal review-lag from a late-1936 publication). Chapter 4 — *Causation Reconsidered* — is now drafting-ready.
- Total drafted at end of session: 16,796 body / 18,490 with footnotes across five sections (preface + Ch 1 + Ch 2 + Ch 3 + Ch 14). Thirty-eight footnotes total. ~24.0% of the ~70,000-word target. Six citation batches complete.

### 2026-04-25 — Working production session 2 (`/go` script run → four sections reviewed, Ch 2 banked, Batch 3 verified)
- `/go` script of session-1's queued plan run end-to-end. Eight commits (voice-check ch01, review ch01, voice-check ch14, review ch14, draft ch02 first draft, voice-check ch02, review ch02, sources verify Batch 3).
- Voice-check + review passes on Ch 1 (4 voice revisions, 3 review findings) and Ch 14 (3 voice revisions, 0 review findings beyond voice-check). Ch 1 factual fix: the *Discourse on the Method* was published as the introduction to the three essays, not "in the back" of them.
- Drafted Ch 2 — *The Three Returns* — at 3,609 body / 3,988 with footnotes; nine footnotes from Batch 1 verified pool. Includes a substantive disagreements section (scale, formal modelling, internal reformability) treating the three structural questions on which Ackoff, Meadows, and Senge actually differed. Length 191 words below the 3,800 honest-short floor; committed without padding per the length-floor decision.
- Batch 3 (Chapter 8 sources, 7 entries): all ✓ VERIFIED. Berger × 2, Le Guin × 2, Tolstoy, Robinson, Lewis. Two new edition decisions resolved by AI under standing director delegation:
  - Le Guin *Steering the Craft*: cite the 2015 Mariner revised edition as canonical; 1998 Eighth Mountain Press original noted as historical first.
  - Tolstoy *What Is Art?*: cite the Hackett 1995 reprint of Aylmer Maude's authorised translation (Vincent Tomas introduction) as the citing text; 1899 Walter Scott Ltd. London first English edition noted historically; Pevear/Volokhonsky 1995 Penguin Classics noted as a respected contemporary alternative.
- Removed an unverified named-author reference (Wiener) from the Ch 2 body during the review pass; reformulated to "the older cybernetic tradition" without the named figure, since Wiener is ✗ UNVERIFIED in `06_SOURCES.md`.
- Caught a batch-numbering inconsistency in the previous next-session script (called "Batch 4" what is actually "Batch 3" per `06_SOURCES.md`); resolved by using the canonical batch numbering from the verification status table.
- Total drafted at end of session: 13,047 body / 14,204 with footnotes across four sections (preface + Ch 1 + Ch 2 + Ch 14). Twenty-five footnotes total. ~18.6% of the ~70,000-word target.
