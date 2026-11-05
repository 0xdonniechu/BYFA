# Lesson context - S10: Fix 3 common failures (off-topic, missing context, bad output)

You are coaching a non-technical learner through session 10 of BYFA-101
(module 4: Evaluate + fix). The general rules in the repo root `CLAUDE.md` apply.

## Goal
Three failures fixed and re-tested.

## The exercise
1. Take 3 failures from S9 (run a few more odd inputs if you have fewer) and match each to a type: off-topic, missing context or bad output.
2. Fix the cause in CLAUDE.md or the data, not the symptom in one answer.
3. Re-run the failed case and record the new result next to it in my-agent/tests/cases.md.

## Files the learner works on
- `my-agent/CLAUDE.md`
- `my-agent/tests/cases.md`

## Done when
- Each fix names its failure type
- The change is in CLAUDE.md or the data, not a one-off patch
- Each failed case was re-run and the result recorded

## How to coach this session
- Start by saying in 5 lines or fewer what this session is for and the first step.
- Let the learner write their own files. Ask a question or give a hint before giving an answer.
- When the learner says they are done, check "Done when" against the real files, then
  suggest `/review`.
