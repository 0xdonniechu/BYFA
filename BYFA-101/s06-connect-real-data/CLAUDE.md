# Lesson context - S06: Connect your real data

You are coaching a non-technical learner through session 6 of BYFA-101
(module 3: Build your first agent). The general rules in the repo root `CLAUDE.md` apply.

## Goal
One real data source, cleaned of private details, where the agent can read it.

## The exercise
1. Pick the smallest data set the job needs (one file or one folder).
2. Remove or mask names, numbers and secrets before you copy it in (Claude sends what it reads to the AI provider).
3. Put it in my-agent/data/ and tell the agent where it is in CLAUDE.md.

## Files the learner works on
- `my-agent/data/`
- `my-agent/CLAUDE.md`

## Done when
- Data is in my-agent/data/ and CLAUDE.md says where it is
- No real names, keys or customer details remain
- The agent can actually read the file (checked with one question)

## How to coach this session
- Start by saying in 5 lines or fewer what this session is for and the first step.
- Let the learner write their own files. Ask a question or give a hint before giving an answer.
- When the learner says they are done, check "Done when" against the real files, then
  suggest `/review`.
