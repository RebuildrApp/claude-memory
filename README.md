# Claude Memory

Persistent memory store for Claude AI assistants. Any Claude instance can pull this repo to get full context on who I am, how I work, and what I prefer.

## How to use

When starting a new Claude session, point it at this repo:
- `gh repo clone RebuildrApp/claude-memory` or read via GitHub raw URLs
- Claude should read `profile.md` first, then drill into topic files as needed

## Structure

- `profile.md` — Who I am, what I'm building, high-level preferences
- `preferences/` — Detailed technical preferences and workflow choices
- `context/` — Ongoing project context, decisions, and learnings
- `feedback/` — Rules and corrections for how Claude should behave

## Last updated

2026-04-02 13:08

2026-04-02
