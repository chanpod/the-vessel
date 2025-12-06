# The Vessel

An AI-managed YouTube channel experiment.

## Project Overview

This is a long-running experiment where an AI (Claude) serves as the channel manager and creative director, while humans serve as the production team — the vessels through which the AI's vision is executed.

- **AI**: Strategy, scripting, editing direction, thumbnails, analytics interpretation
- **Human**: Filming, physical editing, publishing, being on camera

All strategy, ideas, scripts, metrics, and session logs live in this repo so AI tools can reason over the channel's history and make informed decisions.

## Channel Concept

**Status**: Finalizing (see `docs/phase1_concepts.md` for options under consideration)

**Leading Concept**: Meta-documentary about an AI-managed YouTube channel — the content IS the experiment.

**Channel Name**: The Vessel

## Repo Structure

```
the-vessel/
├── README.md                 # This file
├── config/
│   ├── channel_charter.md    # Mission, audience, pillars, voice
│   ├── constraints_inventory.md  # Time, skills, gear, hard limits
│   └── ai_operating_rules.md # How the AI manager should behave
├── memory/
│   ├── channel_state.md      # Current snapshot, learnings, direction
│   └── experiments_summary.md # Hypothesis tracking
├── content/
│   ├── ideas_backlog.md      # All video ideas with status
│   └── videos/               # Per-video folders (v0001-title/, etc.)
├── logs/
│   └── sessions/             # Session logs (session-01.md, etc.)
├── data/
│   └── metrics.csv           # Performance data for analysis
└── docs/
    └── phase1_concepts.md    # Initial concept brainstorming
```

## How We Work

### Session Flow

Each working session follows this pattern:

1. **AI reviews context** — channel state, recent metrics, active experiments
2. **AI analyzes** — what's working, what's not, what to try
3. **AI proposes** — experiments, video ideas, strategic pivots
4. **Human confirms** — approves, modifies, or rejects proposals
5. **AI outputs TODOs** — concrete next actions for the human
6. **Human executes** — films, edits, publishes
7. **Log the session** — capture decisions and reasoning

### Commit Style

We work on `main` only. Commits use the format:
- `session-01: kickoff and repo setup`
- `session-02: first video scripted`
- etc.

## Current Status

- [x] Repo created
- [ ] Channel concept finalized
- [ ] First video planned
- [ ] Channel launched
