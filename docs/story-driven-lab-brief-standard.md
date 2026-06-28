# Story-Driven Lab Brief Standard

## Purpose

Every PythonLabs lab must be story-driven and requirements-led.

The learner should understand why they are doing the work before they run commands or write code. The lab should feel like a realistic engineering task, not a command-copying exercise.

## Core Rule

Before any implementation tasks, every lab must explain:

* the situation
* the role the learner is playing
* the operational problem
* why the work matters
* what good completion looks like
* what risks or constraints apply

Commands, code, and tests should come after the story and requirements.

## Required Lab Opening Structure

Every lab brief should begin with:

1. Lab Summary
2. Scenario
3. Manager or stakeholder requirement
4. Reference material
5. Requirements table
6. Constraints
7. Assumptions
8. Expected work or expected project structure
9. Deliverables
10. Implementation tasks

## Scenario Requirement

The scenario must explain the reason for the lab.

A good scenario should answer:

* Who are you in this situation?
* What system, tool, customer, or team are you supporting?
* What problem needs to be solved?
* Why does it matter operationally?
* What could go wrong if the work is done badly?

## Manager or Stakeholder Requirement

Each lab should include a short quoted requirement from a manager, customer, team lead, or stakeholder.

The quote should set the practical expectation for the lab.

Example style:

```text
Your manager gives you this requirement:

> Do not treat this as a toy script. Build a small tool that produces useful evidence, handles bad input, and can be explained to another engineer.
```

## Requirements-Led Design

The lab should use a requirements table before tasks.

The table should show what must be achieved, not just what commands to run.

Suggested format:

| ID | Requirement | Status |
| --- | --- | --- |
| R1 |  | Not started |
| R2 |  | Not started |
| R3 |  | Not started |

## Commands Are Supporting Evidence

Commands should not be the centre of the lab.

Commands should appear after the learner understands:

* what they are trying to prove
* why the command is useful
* what output they expect
* what a failure might mean
* how the result will be verified

## Implementation Task Style

Implementation tasks should be written as guidance, not a copy-paste script.

Use language such as:

* You need to prove...
* Useful commands may include...
* Record the evidence...
* Explain why...
* Verify that...
* Decide whether...

Avoid lab briefs that only say:

```text
Run this command.
Run this command.
Run this command.
```

## Required Reasoning Sections

Every lab should include sections for:

* issues encountered
* decisions made
* security and production considerations
* break/fix notes
* testing and verification
* final outcome
* what would improve in production
* exactly seven reflection questions

## Break/Fix Integration

Because break/fix is mandatory, every story should include something that can realistically go wrong.

The lab should explain why the failure matters.

Examples:

* a bad input could misclassify an incident
* a missing file could break a deployment report
* a wrong SQL join could produce misleading customer data
* a failed Docker run could block a deployment helper
* a bad regex could miss important error codes
* a missing metric could hide a production issue

## Two-Part Structure Integration

Every lab still has two parts:

1. Part 1 — New Chapter Content
2. Part 2 — Cumulative Repetition

Both parts should have context and purpose.

Part 1 explains why the new concept matters.

Part 2 explains why old concepts are being reused and how they support the current task.

## Reference Material Rule

Each lab must include:

* full chapter references where books are used
* official online documentation where tooling or current behaviour matters
* date checked for online documentation

## Evidence Requirement

The learner should be asked to capture evidence, not simply claim completion.

Evidence may include:

* command output
* test output
* expected vs actual result
* traceback or error message
* before/after output
* generated files
* customer-facing summary
* runbook or decision note

## Final Rule

No PythonLabs lab should feel like disconnected command practice.

Every lab must answer:

> Why am I doing this, what problem does it solve, how do I prove it worked, what broke, how did I fix it, and why would this matter in real engineering work?
