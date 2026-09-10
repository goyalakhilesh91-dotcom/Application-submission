# Glean — Proactive Coworker

Concept design for a proactive AI coworker inside Glean's enterprise app, for an IT & Ops service-desk lead.

`index.html` is a standalone build — open it in any browser, no server or install needed.

## What's in it

A guided tour (11 steps) walks the whole experience:

1. **Rail** — the coworker waits in Glean's left rail with a badge for what needs you.
2. **Your context (first run)** — the agent's read on you: role, how it interprets your work, the goals it works toward with their origins and sources, your projects/systems/rhythms, people it would work through, and every tool it can reach with read/write scopes.
3. **Your day** — a coverage band showing the agent has already touched all 13 items, split into finished / running / drafted / yours to judge; *Your calls* (drafted, waiting on your word, irreversible actions flagged); *The agent has this* (running or done, nothing needed from you); a *Coming in* feed of signals turning into tasks; and live goal progress.
4. **Task detail** — click any task for the reasoning, sources, confidence and reversibility.

## Source

`src/` holds the authoring files. `index.html` is the self-contained build and is the one to open.
