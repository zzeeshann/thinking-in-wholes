# /review — Review draft against standards

Review the draft I specify against `docs/02_STYLE_GUIDE.md` and the 2040 frame: **$ARGUMENTS**

## Find every instance of:

1. **Forbidden words and phrases** — the table in `docs/02_STYLE_GUIDE.md` ("leverage," "unpack," "deep dive," "in today's world," "fundamentally," "synergy," etc.). All of them.
2. **Period-piece sentences** — anything that would feel dated by 2032. Specific 2026 references, current company names, contemporary controversies, current political figures, current AI lab names.
3. **Abstractions arriving before their motivating example.** "Membership in a system is functional" before we've talked about the appendix. Reverse the order.
4. **Rhythm uniformity** — too many short sentences in a row, or too many long ones. Variable length is the rule.
5. **Rhetorical questions not immediately answered** with substance.
6. **Open `[SOURCE NEEDED]` flags** still in the draft.
7. **Direct quotations missing page numbers** in their footnotes.
8. **Footnote citations that don't match Oxford format** as defined in the style guide.
9. **Bibliography ghosts** — works cited in footnotes but missing from the bibliography (and vice versa).
10. **Voice drift** — passages that have slipped into consultant prose, TED-talk prose, or self-help prose.

## For each finding

- **Quote** the original line.
- **Diagnose** what's wrong.
- **Propose** a specific replacement.
- Don't soften. The book gets better when you are hard on it.

## After review

1. Produce a **revised draft** incorporating every fix.
2. Save in place (overwrite the existing draft file).
3. Update `docs/04_PROGRESS.md` last-touched date.
4. Commit: `drafts: review pass on [section] (N findings addressed)`

## Report at the end

- Total findings, broken down by category.
- Any findings you couldn't fix in this pass and why.
- Any structural concerns about the draft that go beyond line-level fixes.
