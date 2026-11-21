# LLM agent evaluations

Alongside my backend work, I've worked independently on evaluation environments and graders for LLM agents.

Much of this work involves reading agent transcripts to understand how a task is being solved. Sometimes an agent finds a shortcut that satisfies a grader without fixing the underlying problem. I use those observations to update the environment or grading logic.

## Examples of this work

- Analyzed batches of 10 rollouts to find shortcuts and adjust task difficulty. In those evaluation batches, mean scores went from 0.98 to below 0.60 across five grading criteria.
- Built graders that trigger reconciliation during a run to check whether a fix holds after the system processes it again.
- Added similar-looking data pipelines as distractors so agents have to identify the correct target.
- Reviewed proposed task changes against earlier agent traces and rejected changes that did not improve the evaluation.
- Fixed a privilege-escalation weakness in a sandboxed environment through RBAC and admission-control changes.

The scores above refer to the specific evaluation batches I worked on, not a general comparison of models.

**Tools:** Python, evaluation harnesses, grading systems, behavioral trace analysis, RBAC.

[Back to profile](../README.md)
