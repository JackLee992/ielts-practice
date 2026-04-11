# IELTS Practice Workspace

Personal IELTS General Training practice repo for JackLee.

## Exam Info

- Type: IELTS General Training (机考)
- Date: 2026-06-14
- Writing target: Band 7.0
- Overall target: Band 7.5

## Latest Assessment

- Source of truth: `.ielts/ASSESSMENT-2026-04-11.md`
- This snapshot merges the local repo with a full Feishu wiki review completed on 2026-04-11.
- Future planning should start from that file instead of older baseline notes.

## Current Baselines (2026-04-11)

| Module | Level |
|---|---|
| Writing Task 1 | ~6.0-6.5 |
| Writing Task 2 | ~5.5-6.0 untimed |
| Listening | ~6.0, with some Part 3 work near 6.0-6.5 |
| Reading | ~6.5, with upside toward 7.0 |
| Speaking | ~5.5-6.0 |
| Overall | ~6.0-6.5 |

## Repo Structure

```
.ielts/
├── ASSESSMENT-2026-04-11.md   # Current cross-module snapshot and risk logic
├── profile.md          # Exam goals, current level, bottlenecks
├── ROADMAP.md          # 10-week full study plan
├── WEEK-01-PLAN.md     # Current week plan
├── ERRORS.md           # Repeated error log
├── RULES.md            # Working rules that have helped
├── WEEKLY_REVIEW.md    # Weekly progress review
├── essays/             # All writing outputs (Task 1 & Task 2)
└── sessions/           # Session notes

imports/
└── feishu-writing/     # Historical practice records imported from Feishu

docs/
└── superpowers/        # System design and plans
```

## How This Repo Works

- `.ielts/ASSESSMENT-2026-04-11.md` is the current source of truth for calibrated level estimates and risk checks
- Every practice session produces a file in `.ielts/essays/` or `.ielts/sessions/`
- Repeated mistakes go into `.ielts/ERRORS.md`
- Rules that work get promoted to `.ielts/RULES.md`
- Weekly plan lives in `.ielts/WEEK-XX-PLAN.md`
- Session notes capture the revision chain, not just the final answer
- All outputs are committed and pushed to GitHub after each session
- Sessions are also archived to Feishu Wiki (openclaw_wiki)

## Recent Activity

| Date | Focus | Key Progress |
|---|---|---|
| 2026-04-11 | Cross-module assessment sync | Rebuilt the baseline from local notes plus a full Feishu wiki review; corrected Speaking downward, Reading upward, and Listening into a real trend line. |
| 2026-04-02 | Task 1 Request Letter | Reworked an Android course inquiry into a clean formal letter; logged the revision chain and collocations. |
| 2026-04-02 | Task 2 Logic Drill | Mastered "Change vs. Stability" logic chain; Fixed gerund S-V agreement. |
| 2026-04-01 | Robots & Unemployment | Practiced Body 2; Refined "lose vs loose" and article usage. |
| 2026-03-31 | Task 1 Openers | Mastered formal openers for complaint and inquiry letters. |
| 2026-03-30 | Baseline Setup | Initial diagnostic and Week 01 plan synchronization. |

## Mock Test Schedule

| Date | Purpose |
|---|---|
| 2026-04-17 to 2026-04-18 | Checkpoint 1 — delayed baseline reset after the practice gap |
| 2026-04-19 to 2026-04-20 | Delay decision window |
| 2026-05-10 | Mock Test 2 — verify timed stability |
| 2026-06-07 | Mock Test 3 — final dress rehearsal |
| 2026-06-14 | IELTS Exam |
