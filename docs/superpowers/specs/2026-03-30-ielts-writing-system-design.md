# IELTS Writing System Design

## Goal

Build a lightweight General Training IELTS writing practice workspace that helps the user move from avoidance and low-confidence writing to stable Band 7-level habits through short feedback loops.

## Users And Constraints

- Primary user: the repo owner
- Study mode: repeated practice across multiple sessions
- Main bottleneck: Task 2 structure, body expansion, grammar stability, typo control, and fear of writing
- Constraint: keep the system small enough that daily use feels easy

## Chosen Approach

Use a lightweight training system instead of a large material archive.

The workspace will focus on:

- profile and phase goals
- error tracking
- rules that have already worked
- weekly review
- per-session practice records
- essay storage

Imported Feishu writing materials remain available as background evidence, but they are not the main working area.

## Structure

- `.ielts/profile.md`
  - current level, target, bottlenecks, phase goals
- `.ielts/ERRORS.md`
  - repeated or high-value mistakes only
- `.ielts/RULES.md`
  - stable writing rules that should be reused in future tasks
- `.ielts/WEEKLY_REVIEW.md`
  - short weekly reset and next-step review
- `.ielts/sessions/`
  - one record per practice session
- `.ielts/essays/`
  - timed and untimed writing outputs
- `imports/feishu-writing/`
  - imported historical evidence from the existing Feishu mirror

## Coaching Loop In Repo

Each substantial writing cycle should follow:

1. Diagnose the bottleneck
2. Name the mistake type
3. Reduce it to one or two rules
4. Turn the rule into a small drill
5. Re-test quickly

## Phase 1 Scope

Phase 1 is not trying to maximize vocabulary range or produce polished full essays every day.

Phase 1 only aims to:

- reduce fear of starting
- stop Body paragraphs from collapsing
- stop obvious mixed-answer drift in Task 2
- reduce repeated basic sentence errors
- bring Task 2 back toward 40 minutes

## Non-Goals For Now

- building a full question bank
- organizing every imported study note
- creating advanced dashboards or automation
- pushing fresh content back to Feishu

## Success Signals

- the user can complete short writing drills without freezing
- body paragraphs follow one clear center and a fixed expansion pattern
- common grammar and typo issues are tracked instead of rediscovered
- the repo becomes the default place for new writing practice
