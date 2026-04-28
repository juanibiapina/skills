# Modular Agent Skills

Agent skills that I use every day for software development.

## General Principles

- Description contains only triggers for agents to select the skill. No extra information.
- Invoking a skill is not an anti-pattern.
- Not specific to one harness (no subagents or custom tools)
- Don't include code

## Types of Skills

### Concepts

Concepts define vocabulary, language, mental models, and reusable methods. They help agents think, talk, and work with a subject consistently.

Concepts don't prescribe end-to-end workflows. Pick a workflow skill when you want an end-to-end task. Concepts shouldn't write files or produce outputs.

### Workflows

Workflows define end-to-end tasks. They set the process and output shape.

- Can reference concepts.
- Should not duplicate knowledge from concepts.
- Can reference other workflows.
- Can define its inputs. (can also just get inputs from context)
- Defines what to produce as output.

## Skills

| Skill | Type | Purpose |
| --- | --- | --- |
| `code-design` | Concept | Shared vocabulary for modules, interfaces, implementation, depth, seams, adapters, leverage, and locality. |
| `deepening` | Concept | How to deepen shallow modules safely, choose seams, classify dependencies, and plan tests around a refactor. |
| `review-architecture` | Workflow | Review a whole codebase for deepening opportunities and present candidates. |
| `design-interface` | Workflow | Explore alternative interfaces for a chosen deepening candidate. |
| `explore-design-space` | Workflow | Explore a plan or design through questions until decisions are resolved. |
