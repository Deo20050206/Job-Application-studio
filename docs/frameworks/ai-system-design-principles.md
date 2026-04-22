# AI System Design Principles

## Principles I Follow

### 1. Constrain Before Generating

The more important the task, the more important it is to define:

- what AI can use
- what AI cannot infer
- what counts as acceptable output

### 2. Keep Truth Sources Separate

Inputs, templates, rules, outputs, and trackers should not be mixed together.

That separation makes the workflow:

- easier to inspect
- easier to debug
- safer to publish selectively

### 3. Make the Process Legible

If a workflow matters, the logic should live in files, not only in memory.

That is why I prefer:

- rule files
- skill files
- checklists
- templates
- repository structure that explains itself

### 4. Build for Reuse

AI becomes more useful when repeated work is converted into reusable process.

That usually means:

- stable folder structure
- reusable prompts or skills
- repeatable intake formats
- QA steps that can be run again

### 5. Preserve Human Judgment

AI speeds up structuring, drafting, and analysis.

Judgment is still required for:

- deciding what matters
- reviewing claims
- choosing tradeoffs
- defining what should be published
