# /verify — Citation verification batch

Run citation verification for the batch I specify: **$ARGUMENTS**

(Examples: "Batch 1 — foundational systems canon"; "Chapter 1 sources"; "all unverified Whitehead entries")

For each ✗ UNVERIFIED source in `docs/06_SOURCES.md` belonging to this batch:

1. **Web-search** the work using its most distinctive identifier (full title + author last name).
2. **Cross-check** with at least one authoritative source: the publisher's catalog, Library of Congress, British Library, WorldCat, Google Scholar, or the work's official site.
3. **Confirm** these five fields:
   - Author full name (correct initials and order)
   - Exact title (with subtitle, capitalization)
   - Publisher
   - City of publication
   - Year of publication (and edition if multiple exist)
4. **For direct-quote citations:** verify the page number against the actual source where possible. If the source is in copyright and the page can't be confirmed online, mark with `⏳ PARTIAL — page numbers require physical-copy check`.
5. **Update** the entry's marker in `docs/06_SOURCES.md`:
   - All five fields confirmed → **✓ VERIFIED**
   - Some confirmed, gaps remain → **⏳ PARTIAL** (note what's missing inline)
   - Cannot confirm the work exists → leave as **✗ UNVERIFIED**, add a note: *"Could not verify; recommend cutting or replacing with: [alternative]."*
6. **Note discrepancies** between what `docs/06_SOURCES.md` had and what you found. Correct the entry to the verified data.

After processing all sources in the batch:

7. Update the citation verification status table in `docs/04_PROGRESS.md`.
8. Commit with message: `sources: verify [batch description] (N verified, M partial, K unverified)`

**Final report:** how many ✓, how many ⏳, how many ✗. List every ✗ explicitly so I can decide whether to cut the source from the pool or replace it with a verified alternative.

---

**Special caution applies to:**
- Less-famous primary sources (e.g., Edgar A. Singer Jr., early Churchman)
- Specific edition / year details for works with multiple editions
- Journal article volume / issue / page details
- Page numbers for any direct quotation
- Pre-1950 sources
- Translated works (verify which translation)

When AI memory is uncertain, web-search is mandatory. Never paper over uncertainty with confidence.
