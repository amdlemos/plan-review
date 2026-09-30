# Plan Review

An agent skill for reviewing implementation plans before code is written. It
checks whether the plan solves the right problem, fits the project, and gives
each task enough instructions and acceptance criteria for execution.

## Installation

Requires Node.js and npm.

```sh
npx skills add amdlemos/plan-review --skill plan-review
```

The CLI lets you choose the agent and installation scope.

## Usage

Ask your agent to review a plan and provide its file path or text:

```text
Use plan-review to review plans/example/plan.md.
```

The review is read-only and provides findings, evidence, and a verdict.
See [SKILL.md](SKILL.md) for the complete instructions.
