# /source-needed — Resolve open `[SOURCE NEEDED]` flags

Resolve the open `[SOURCE NEEDED]` flags in: **$ARGUMENTS**

(Example: "drafts/ch01_cartesian_wound.md")

## For each flag

1. **Read** the surrounding context to understand exactly what claim needs supporting.

2. **Web-search** for an authoritative primary source that supports the claim. Prefer:
   - The original work where the idea or argument was first made
   - Peer-reviewed scholarship over popular books
   - Primary sources over secondary ones
   - Works by named experts in the relevant field

3. **If you find a suitable source:**
   - Verify it (author, full title with subtitle, publisher, city, year, edition, page if possible).
   - Add it to `docs/06_SOURCES.md` as **✓ VERIFIED** under the appropriate chapter.
   - Replace the `[SOURCE NEEDED]` flag in the draft with a real Oxford-format footnote.

4. **If you cannot find a suitable source:**
   - Recommend one of:
     - **(a) Soften the claim** so it doesn't need a citation (state it as a general observation rather than a sourced argument).
     - **(b) Cut the claim entirely** if it's not load-bearing.
     - **(c) Replace with a different but related claim** that we can source.
   - Wait for my decision before making any of these changes.

## After processing all flags

1. Save the updated draft.
2. Save the updated `docs/06_SOURCES.md`.
3. Commit: `sources: resolve [N] source-needed flags in [section]`

## Report at the end

- How many flags resolved with new verified sources
- How many softened
- How many cut
- How many awaiting my decision
- Any sources you tried hard to find but couldn't, with notes on what you searched
