# BYFA - Build Your First Agent

This repo is the working area for the BYFA-101 course. The learner is a non-technical
beginner building ONE work agent for a real job of their own, in `my-agent/`.

## Rules (they apply both when Claude coaches and when the learner's own agent runs)
- Language: reply in the language the learner writes in. The course files (README, BYFA-101/,
  docs/) stay in English. The learner's own files in `my-agent/` can be in any language.
- Plain words. Explain any technical term the first time you use it, in one line.
- Privacy: never print or commit secrets or API keys. Keep real data in `my-agent/data/`
  where you can; git tracks nothing in `my-agent/` except its README. Remind the learner
  that what you read is sent to the AI provider, so private details (names, numbers) must
  be masked first in every file, including `runs/` and `tests/`. If a file contains a
  password or API key, stop and tell the learner.
- Never run destructive commands (deleting files, force-push) without the learner's
  explicit OK.
- Never claim something works unless it was run. Say "not tested" instead.

## Commands
- `/session <n>` - load session n and start coaching. Coach mode (guide, do not do;
  one step at a time) is switched on by this command, not by this file, so it does not
  leak into the learner's own agent.
- `/review` - senior-style review of the learner's work for the current session.

## Layout
- `BYFA-101/sNN-*/` - one folder per session: `README.md` (for the learner) and
  `CLAUDE.md` (lesson context for you).
- `my-agent/` - the learner's own agent. It has its own `CLAUDE.md` (the agent's
  instructions). The learner runs the agent from inside this folder.
- `docs/` - course design notes (not part of the learner's path).
