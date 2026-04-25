# Thinking in Wholes — Project Brief

> **Read this first, every session. Everything else inherits from this.**

---

## What this is

A serious nonfiction book on systems thinking, written in 2026 for readers in 2040.

A primer-length document already exists (`source/thinking_in_wholes.md`). It is a good introduction but it is not a book. This project is to build the actual book — one that engages primary sources directly, argues rather than asserts, serves specific creative and technical audiences, and earns its place on the shelf next to Meadows, Senge, Ackoff, and Alexander.

## Authorship model

**The book is written by AI (Claude, by Anthropic) under human direction.** The human directs at the level of vision, scope, structure, and quality. The AI does the writing — drafting, researching, citing, revising, polishing. The human approves, redirects, and rejects. The output is an AI-written book; the human is its director and editor of last resort.

Three implications:

1. **Direction is by slash command.** The human uses the commands in `.claude/commands/` to drive each phase of work. The AI executes against the project standards in this brief and in `02_STYLE_GUIDE.md`.
2. **Quality is non-negotiable and self-enforced.** The AI is responsible for catching its own failures: voice drift, dated references, weak arguments, hallucinated citations. The human is the second line of defense, not the first.
3. **The AI does not perform.** No throat-clearing, no breathless excitement, no "happy to help." It writes the book.

## The 2040 frame (most important constraint)

The book is written in 2026 but addressed to a reader in 2040. This is not a stylistic flourish. It is a structural commitment that shapes every sentence. Concretely:

- **No period-piece references.** No specific 2026 company names, current AI lab names, current political figures, current platforms, current hot-button controversies. These will read as embarrassing footnotes by 2032.
- **Anchor in long traditions.** Centuries-old patterns survive. News cycles do not.
- **Treat our own moment with detachment** — as if we ourselves are looking back at it. This is how Stewart Brand wrote *The Clock of the Long Now* and how McLuhan wrote *Understanding Media*. The technique liberates the prose from the parochialism of its decade.
- **Make predictions on the record.** The 2040 reader has lived with mature AI for fifteen years. They know which 2026 predictions came true. We write for them, not for the 2026 review cycle. We grade ourselves before they do.
- **Name our blind spots.** What we couldn't see clearly. What we suspected but couldn't prove. What we got wrong on purpose because we lacked better.

If a sentence would feel dated by 2032, it does not survive the next pass.

## Citation rigor — non-negotiable

Every citation in the book is real. Every author exists. Every title is correct. Every year, publisher, and city of publication is verified. Every direct quote is checked against the source. The book uses **Oxford referencing style** (footnotes with full first-citation, short-form subsequent citations, bibliography at end). Detailed rules in `02_STYLE_GUIDE.md`. Source list in `06_SOURCES.md`.

**The AI must not invent citations.** When writing, the AI uses only sources from the verified pool in `06_SOURCES.md` (sources marked ✓ VERIFIED). If a claim requires a source not yet in the pool, the AI flags it inline as `[SOURCE NEEDED: description]` and verifies the source via web search before the chapter is finalized. No exceptions. Inventing a citation is a project-killing failure.

## Why this book exists

Three converging facts:

1. The intellectual foundation (Ackoff, Meadows, Senge, Singer, Forrester, Alexander) is largely unread by the people who most need it — creators, builders, philosophers under forty.
2. The technologies and crises of the coming fifteen years are systems-level. The thinking deployed against them is still parts-level. That gap is where preventable damage will come from.
3. No existing book speaks to the four audiences below at once, in language they can each take seriously.

## Audiences

Four, in priority order:

1. **Creators** — writers, artists, designers, filmmakers, musicians *(primary, by author decision logged in `03_DECISIONS.md`)*
2. **Architects** — built-environment, urban planners, digital systems architects
3. **Engineers** — software, systems, hardware, infrastructure
4. **Philosophers** — academic and lay; especially process and systems philosophers

When a sentence is hard to phrase, the primary audience is the one we choose for. The others must still find their footing in it.

## Intellectual lineage

The book engages, as primary sources, not summaries:

- **Russell L. Ackoff** (1919–2009) — systems applied to organizations
- **Donella H. Meadows** (1941–2001) — system dynamics, ecological thinking
- **Peter Senge** (b. 1947) — learning organizations
- **Edgar A. Singer Jr.** (1873–1955) — producer-product causation
- **Jay W. Forrester** (1918–2016) — industrial dynamics
- **Christopher Alexander** — pattern languages, the timeless way of building
- **Jane Jacobs** — cities as systems
- **C. West Churchman** — the systems approach
- **Stafford Beer** — managerial cybernetics
- **Alfred North Whitehead, Henri Bergson** — process philosophy

The full bibliography lives in `06_SOURCES.md` and grows as we go, with verification status tracked per entry.

## Form

- 1 preface ("Letter to the 2040 Reader")
- 14 chapters in 4 parts
- 1 afterword
- 1 glossary
- References and notes (Oxford style, chapter-keyed)
- **Target length: 60,000–80,000 words** (~70k working target)

Full structure in `01_OUTLINE.md`.

## Tone, in one paragraph

Calm authority. Unhurried. Adult prose. The voice of someone who has thought about this for thirty years and is not trying to convince anyone — just laying out what they have seen, as carefully as they can, for a reader they respect. Closer to John Berger or Marilynne Robinson than to a TED talk. Not breathless. Not academic-cold. Not consultant-glossy. No exclamation points. No "imagine for a moment." No bullet-point prose in the body. Sentences vary in length. Concrete examples earn every abstraction.

Detailed rules in `02_STYLE_GUIDE.md`.

## Standards

Every claim is either argued or named as a claim.
Every named source is engaged as a primary text.
Every citation is verified before publication.
Every prediction is on the record.
Every blind spot we suspect is named.
Every chapter earns its place — if a chapter cannot answer "what does the book lose without me?" it does not survive.

## What this book is not

- Not a primer (that already exists in `source/`)
- Not a self-help book
- Not a management or business book
- Not a manifesto
- Not a survey of the field
- Not journalism
- Not a textbook

## License

This work is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**. The book is public from first draft. The git history is the book's record of itself. See `../LICENSE` and `../README.md`.

## Working method

- All decisions logged in `03_DECISIONS.md` (append-only)
- Style and Oxford citation rules in `02_STYLE_GUIDE.md`
- Progress tracked in `04_PROGRESS.md` (updated each session)
- Slash commands for directing the AI in `../.claude/commands/`
- Verified source pool in `06_SOURCES.md`
- Standing operating instructions for Claude Code in `../CLAUDE.md`
- New sessions begin via the `/start` command, which reads `00`, `01`, `02`, `03`, `04` in order before any work
- Drafts saved as separate files: `../drafts/preface.md`, `../drafts/ch01_cartesian_wound.md`, etc.
- Every significant unit of work commits to git with a clear scope-prefixed message
