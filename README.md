# Modular Agent Skills

Agent skills that I use every day for software development.

## General Principles

- Description contains only triggers for agents to select the skill. No extra information.
- Invoking a skill is not an anti-pattern.
- Not specific to one harness (no subagents or custom tools)
- Don't include code
- No duplication. Just like functions don't duplicate code, skills don't duplicate knowledge.

## Types of Skills

### Concepts

Concepts define vocabulary, language, mental models, and reusable methods. They help agents think, talk, and work with a subject consistently.

Concepts don't prescribe end-to-end workflows. Pick a workflow skill when you want an end-to-end task. Concepts shouldn't write files or produce outputs.

### Workflows

Workflows define end-to-end tasks. They set the process and output shape. They can reference Concepts and shouldn't duplicate knowledge from them. They can define specific required inputs and should define their outputs.

### References

References document tools, APIs, or CLIs. Commands, endpoints, flags, query patterns, and gotchas.

## Skills

| Skill | Type | Purpose |
| --- | --- | --- |
| `code-design` | Concept | Shared vocabulary for modules, interfaces, implementation, depth, seams, adapters, leverage, and locality. |
| `deep-modules` | Concept | How to turn shallow modules into deep modules safely, choose seams, classify dependencies, and plan tests around a refactor. |
| `testing` | Concept | Testing principles, mocking guidance, and interface testing. |
| `refactoring` | Concept | Refactor candidates to look for after tests are green. |
| `levels-of-abstraction` | Concept | Single level of abstraction per function, composed method, stepdown rule, and smells that signal mixed levels. |
| `ai-writing-signs` | Concept | Patterns in vocabulary, structure, formatting, tone, and citations that are characteristic of LLM-generated text. |
| `gh-notifications` | Reference | GitHub notifications API: listing, thread actions (read vs done vs unsubscribe), PR enrichment, and dependency-bot PR merging. |
| `review-architecture` | Workflow | Review a whole codebase for deep-module opportunities and present candidates. |
| `design-interface` | Workflow | Explore alternative interfaces for a chosen deep-module candidate. |
| `explore-design-space` | Workflow | Explore a plan or design through questions until decisions are resolved. |
| `tdd` | Workflow | Test-driven development with a red-green-refactor loop. |
