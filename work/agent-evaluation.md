# Adversarial evaluation for LLM agents

**Independent applied AI work · Python · Evaluation harnesses · Grader design · Behavioral analysis · Access control**

I design evaluation environments that test whether an LLM agent can identify a problem, fix its cause, and leave the system in a durable, correct state.

## Calibrating difficulty from behavior

I analyzed behavioral traces across 10-run rollout batches to identify shortcuts and recalibrate tasks. In that work, agent mean scores moved from a saturated **0.98 to below 0.60**, while preserving variance across **five independently graded criteria**.

These figures describe the evaluation batches I worked on, rather than a general ranking of models.

## Testing durable fixes

I built process-based graders that trigger reconciliation cycles during evaluation. This helps distinguish root-cause fixes from changes that temporarily satisfy an observable snapshot.

## Adversarial environment design

- Used multiple semantically similar distractor pipelines to test discrimination across simultaneous dimensions.
- Reviewed agent transcripts to identify failure modes before shipping evaluation changes.
- Rejected difficulty changes that added friction without improving discrimination.
- Closed a privilege-escalation weakness in a sandboxed evaluation environment through RBAC and admission-control changes.

## What I care about

A benchmark is useful when its reward aligns with the behavior it intends to measure. I focus on making that alignment harder to exploit and easier to inspect.

[← Back to profile](../README.md)
