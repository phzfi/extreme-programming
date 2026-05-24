# Extreme Programming (XP) Skill for Claude & AI Agents

*    By **PHZ.fi Full Stack** Sustainable Code	&trade

Elevate your agentic coding workflow with the **Extreme Programming (XP) Skill**. This specialized skill transforms Claude into a disciplined, high-integrity **AI Pair Programmer** that adheres to the core tenets of Extreme Programming.

## 🚀 Overview

The `extreme-programming` skill is designed to prevent the common pitfalls of AI-generated code—such as over-engineering, lack of testing, and massive, unreviewable diffs. Instead, it enforces a cycle of **small, validated increments**, ensuring that every change is safe, simple, and easy to maintain.

## ✨ Key Features

*   **Test-Driven Development (TDD) First**: Prioritizes writing failing tests before implementation to ensure behavioral correctness.
*   **Continuous Refactoring**: Actively identifies and removes technical debt, duplication, and complexity under the protection of tests.
*   **Simple Design & YAGNI**: Strictly follows "You Ain't Gonna Need It," resisting speculative abstractions and over-engineering.
*   **Small, Atomic Changes**: Breaks large tasks into manageable "vertical slices" to provide rapid feedback and easy code reviews.
*   **Adaptive Pair Programming**: Acts as an active partner, explaining reasoning and pushing back against non-idiomatic or complex patterns.

## 🛠️ Core XP Principles Applied

| Principle | Implementation in AI Workflow |
| :--- | :--- |
| **TDD** | Red-Green-Refactor cycle for all functional changes. |
| **Refactoring** | Constant improvement of code structure without changing behavior. |
| **Simple Design** | Minimizing elements to meet current requirements only. |
| **Small Releases** | Delivering small, tested, and reviewable code increments. |
| **Continuous Integration** | Ensuring every change is immediately validated by the test suite. |

## 🎯 Who is this for?

*   **Software Engineers** using AI agents (Claude Code, etc.) for professional development.
*   **Teams** looking to maintain high code quality and low technical debt in AI-assisted projects.
*   **DevOps Engineers** aiming for high CI/CD readiness and codebase stability.

## 🚀 How to Activate

Clone the repo or copy the file under ~/.claude/skills/ or under your project .claude/skills, or use your editor to install the extreme-programming -skill from URL.

Activate typically by entering 

    /extreme-programming

which should return something like:

    /extreme-programming 
    The user has activated the Extreme Programming skill. They haven't given me a specific task yet - they've just loaded the skill. Let me check if there's anything pending from the task list or if they want me to continue with something specific.
    Actually, the user just pasted the skill content - they're telling me to use XP principles going forward. I should acknowledge and wait for their next instruction, or if there's a clear next step from the previous work, mention it.
    I'll wait for their next request.
    XP pair mode active.

After that continue development as usual, but now you have skilled XP pair programmer at your disposal.

Simply mention your intent to follow Extreme Programming principles or trigger the skill during tasks involving:

*   `Implementing new features`
*   `Refactoring existing code`
*   `Writing or fixing tests`
*   `Simplifying complex logic`

---
*Optimized for: AI Pair Programming, Extreme Programming for LLMs, Agentic TDD, AI Software Engineering.*
