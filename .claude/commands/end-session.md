# /end-session — Close out the session

Run this at the end of every working session.

## 1. Update `docs/04_PROGRESS.md`

- **"Last session"** — today's date and a 2–3 sentence summary of what was accomplished
- **Drafting status table** — word counts and last-touched dates for any draft touched
- **Citation verification status table** — batches completed or advanced
- **"Next session — what to do first"** — the most useful next step, written to be self-contained
- **"Total drafted"** — current cumulative word count

Keep it short. The progress file is for navigation, not narrative.

## 2. Update `docs/03_DECISIONS.md`

If we made any decisions today:

- Add them to **DECIDED** with date and reasoning.
- If a decision resolves an OPEN question, move that question from OPEN to DECIDED — don't delete; move.
- Append to the **CHANGE LOG** at the bottom if we changed any project standards.

## 3. Final commit

Stage and commit any remaining changes with a clear summary message:

```
session: [brief description of session work]

- bullet of major thing 1
- bullet of major thing 2
- bullet of major thing 3
```

If multiple meaningful units of work happened, prefer multiple smaller commits during the session over one giant end-of-session commit.

## 4. Summarize the session for the human

In 3–5 sentences:

- What we did
- What is now done that wasn't before
- What is the next session's first task
- Any blockers or pending decisions

Do not pad. Do not add encouragement or summary flourishes. The summary is for the human's mental bookmark.
