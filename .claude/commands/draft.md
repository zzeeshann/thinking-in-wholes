# /draft — Draft a section

Draft the section I specify: **$ARGUMENTS**

(Examples: "preface"; "chapter 1"; "ch01 — The Cartesian Wound")

## Pre-flight (before writing a word)

1. **Re-read** the section's outline entry in `docs/01_OUTLINE.md`.
2. **Re-read** `docs/02_STYLE_GUIDE.md` — focus on forbidden vocabulary, Oxford referencing, the 2040 frame.
3. **Confirm** the relevant sources in `docs/06_SOURCES.md` are ✓ VERIFIED. If any are still ✗ or ⏳, **stop** and run `/verify` first.
4. **State to me, in 3–5 sentences:**
   - The section's single argument
   - The three or four moves it makes to support that argument
   - The opening image or example

   Wait for my green light before drafting, unless I have explicitly authorized auto-proceed for this section.

## Drafting

- **Word count target:** per `docs/01_OUTLINE.md` (preface 2,500; chapters 4,500; afterword 1,500).
- **Footnotes:** Oxford style throughout, numbered continuously within the section, restarting at 1 in each new section.
- **Sources:** only ✓ VERIFIED entries from `docs/06_SOURCES.md`.
- **Anything else:** flag inline as `[SOURCE NEEDED: brief description]`. **Never invent a citation.**
- **Direct quotations:** require a page number in the footnote. If the page number is not in the verified entry, paraphrase instead — do not guess.
- **Voice:** calm authority. No throat-clearing. No exclamation points. No forbidden words from the style guide.

## Post-flight (before declaring done)

1. **Forbidden-words sweep.** Read your own draft. Find every violation of the style guide vocabulary table. Replace each one.
2. **2040-frame check.** Find every sentence that would feel dated by 2032 (specific 2026 references, current AI lab names, current political figures, current platforms, contemporary controversies). Revise or cut.
3. **Voice check.** Read the draft once aloud (in your head). Does it read like Robinson, Berger, or Meadows — or like a TED talk? Revise the weak passages.
4. **Save** the draft to `drafts/[filename].md` (e.g., `drafts/preface.md`, `drafts/ch01_cartesian_wound.md`).
5. **Update** `docs/04_PROGRESS.md`: word count, last-touched date, status.
6. **Commit:** `drafts: complete [section] first draft (N words)`

## Report at the end

- Word count
- Number of footnotes
- Number of `[SOURCE NEEDED]` flags still open
- Anything you struggled with — argument soft spots, missing examples, voice uncertainty. Be honest.
