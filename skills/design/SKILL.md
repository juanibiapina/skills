---
name: design
description: Use when planning, building or designing solutions. Applies to interfaces, data models, algorithms, control flow, architectures, processes, etc.
---

# Design

Explore several options before committing to one. Based on "Design It Twice" (Ousterhout). Your first idea is rarely the best, and sketching alternatives costs far less than building the wrong one.

Works for any design problem: an interface, a data model, an algorithm, a control flow, a system architecture, a process.

A design is a tree of dependent decisions. Walk it one decision at a time, resolving each branch and respecting the dependencies between decisions. Give your recommended answer for each.

## Process

### 1. Explore

Understand the current state before proposing anything.

- Explore what already exists and how it works
- Identify the constraints any solution must satisfy
- Identify the dependencies a solution would rely on
- Understand relevant history and existing patterns
- Check for available skills relevant to what's being designed, and load them for domain-specific vocabulary, angles, and constraints

Optionally ground the constraints with a rough sketch. This is not a proposal, just a way to make them concrete.

Present your understanding to the user, then proceed.

### 2. Produce options

Produce 2 radically different options. Push them apart deliberately: if two differ only in detail, replace one. Vary the axis that matters for this problem, such as what's optimized, what's hidden, where complexity sits, or which case is made trivial.

The output for each option is:

1. The approach — what it is and how it works
2. A concrete sketch or example showing it in use
3. What it commits to and what it hides
4. Trade-offs — where it's strong, where it's thin

### 3. Recommend

Present the options so the user can compare. Contrast them on the axes that matter for this kind of solution.

Give your own recommendation: which option is strongest and why. If elements from different options would combine well, propose a hybrid. Be opinionated. The user wants a strong read rather than a menu of equally weighted choices.

### 4. Detail the chosen solution

Once an option is chosen, work it out concretely so it can be acted on.

- The parts of the solution and how they fit together
- What the solution touches or affects
- The order of work to get there

Present the detailed solution to the user.
