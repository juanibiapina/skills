---
name: refactoring
description: Use when refactoring code, identifying refactor candidates, or improving design after tests are green.
---

# Refactoring

- **Duplication** → Extract function/class
- **Long methods** → Break into private helpers (keep tests on public interface)
- **Shallow modules** → Combine or deepen
- **Feature envy** → Move logic to where data lives
- **Primitive obsession** → Introduce value objects
- **Existing code** the new code reveals as problematic
