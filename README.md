# BYFA — Build Your First Agent

Goal: guide non-tech beginners to build their own work agent.
Motto: simple, effective, practical.

## BYFA-101 ecosystem (separate repos, shared ecosystem)
- **BYFA-101** (course) — the first course, 5 modules / 12 sessions.
- **BYFA-skills** — hands-on skill product in the BYFA-101 ecosystem: https://github.com/0xdonniechu/BYFA-skills

## Get started
1. Get this repo: `git clone https://github.com/0xdonniechu/BYFA.git`, or use **Code -> Download ZIP** (no git needed).
2. Watch S1-S2 in the course LMS. Write your task list and brief in `my-agent/` with any text editor.
3. In S3 you set up Claude Code. Open the top folder of this repo (the one that holds `CLAUDE.md`) in it and type `/session 3`.
4. After each exercise, type `/review` to get feedback on your work.

Privacy: by default git tracks nothing in `my-agent/` except its README, so your work is not
uploaded if you push this repo. But Claude reads your files to help you, and what it reads is
sent to the AI provider. Mask private details (names, numbers, keys) before you put them in a file.

Video lessons, guide pages and the community are in the course LMS (for enrolled students).

## Structure
- `BYFA-101/` — the first course: one folder per session (`s01-...` to `s12-...`)
- `my-agent/` — your own agent, built across the sessions
- `CLAUDE.md` and `.claude/commands/` — how Claude coaches you (`/session`, `/review`)
- `assets/logo/` — logo
- `assets/banner/` — social banner
- `docs/` — brainstorm, outline, decisions
