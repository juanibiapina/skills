---
name: design
description: Use when planning, building or designing solutions. Applies to interfaces, data models, algorithms, control flow, architectures, processes, etc.
---

# Design

Explore several options before committing to one. Based on "Design It Twice" (Ousterhout). Your first idea is rarely the best, and sketching alternatives costs far less than building the wrong one.

Works for any design problem: an interface, a data model, an algorithm, a control flow, a system architecture, a process.

## Process

### 1. Frame the problem space

Write a user-facing explanation of what's being designed:

- The constraints any solution must satisfy
- The dependencies it relies on
- A rough illustrative sketch to ground the constraints. This is not a proposal, just a way to make the constraints concrete.

Check for any available skills relevant to what's being designed, and load them for domain-specific vocabulary, angles, and constraints.

Show this to the user, then proceed to Step 2.

### 2. Produce options

Produce 2 radically different options. Push them apart deliberately: if two differ only in detail, replace one. Vary the axis that matters for this problem, such as what's optimized, what's hidden, where complexity sits, or which case is made trivial.

The output for each option is:

1. The approach — what it is and how it works
2. A concrete sketch or example showing it in use
3. What it commits to and what it hides
4. Trade-offs — where it's strong, where it's thin

### 3. Present and compare

Present options so the user can compare. Contrast them on the axes that matter for this kind of solution.

After comparing, give your own recommendation: which option is strongest and why. If elements from different options would combine well, propose a hybrid. Be opinionated. The user wants a strong read rather than a menu of equally weighted choices.
