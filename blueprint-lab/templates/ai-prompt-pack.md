# AI Prompt Pack Template

Use this after the blueprint is clear. Do not start with one giant prompt.

## Prompt 1 — Clarify the product

```text
You are helping me turn this idea into a beginner-friendly build plan.
Project type:
Target user:
Main problem:
MVP goal:
Constraints:

Ask only the most important missing questions, then produce a short build plan.
```

## Prompt 2 — Cut the MVP scope

```text
Review this product/game idea and reduce it to the smallest useful MVP.
Return:
1. Must-have
2. Nice-to-have later
3. Do not build yet
4. Biggest scope risks
5. First 3 build steps
```

## Prompt 3 — Generate implementation tasks

```text
Convert this MVP into small implementation tasks.
Each task must include:
- objective
- files/screens involved
- expected output
- verification step
Keep tasks beginner-friendly and sequential.
```

## Prompt 4 — Build the first slice

```text
Build only the first vertical slice described below.
Do not add extra features.
After coding, explain:
- what changed
- how to run it
- how to verify it
- what remains unfinished
```

## Prompt 5 — Debug and review

```text
Review this project for bugs, missing states, privacy risks, and scope creep.
Return:
1. Critical fixes
2. Nice improvements
3. What to avoid
4. Next safe action
```

## Prompt 6 — Resume after pause

```text
Create a resume brief for this project.
Include:
- what this project is
- last completed step
- current status
- blockers
- next 3 actions
- do not do yet
- definition of done for the next step
```
