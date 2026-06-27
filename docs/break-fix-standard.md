# Break/Fix Standard

## Purpose

Breaking and fixing things is a core part of the PythonLabs series.

The goal is to build troubleshooting confidence, not just write code that works once.

Every meaningful lab should include a controlled failure, an investigation step, a fix, and verification evidence.

## Core Pattern

Use this pattern:

```text
Break -> Observe -> Investigate -> Fix -> Verify -> Document
```

## Safety Rule

Only break local, synthetic, disposable lab components.

Do not intentionally break:

* real company systems
* real customer systems
* personal devices outside the lab folder
* cloud resources that could create cost or security risk
* accounts, credentials, secrets, or access controls
* anything you cannot safely restore

## What Can Be Broken

Safe examples:

* a Python script with a logic bug
* a missing input file
* invalid CSV or JSON data
* bad user input
* incorrect regex pattern
* missing required field
* broken function return value
* incorrect SQL query
* failed Docker build
* container run error
* wrong environment variable
* failed test
* malformed configuration file
* missing output folder
* synthetic unhealthy metric
* mock API timeout or error response

## Required Break/Fix Section

Each lab should include a section called:

```text
## Break/Fix Scenario
```

That section should include:

| Field | Description |
| --- | --- |
| Fault introduced | What was deliberately broken |
| Expected symptom | What failure should appear |
| Evidence captured | Error message, failed test, bad output, or log line |
| Investigation steps | How the issue was narrowed down |
| Fix applied | What changed |
| Verification | How the fix was proven |
| Prevention | How the same issue could be avoided later |

## Testing Requirement

The break/fix work must be tested.

At minimum:

* one test should fail because of the introduced fault
* the same test should pass after the fix
* the final documentation should show what changed

In early labs, this can be manual.

In later labs, this should use formal test files where practical.

## SRE Relevance

Break/fix work builds SRE-relevant habits:

* incident investigation
* hypothesis-driven troubleshooting
* log and error interpretation
* rollback thinking
* verification after change
* customer-impact reasoning
* root-cause notes
* prevention and hardening

## Customer-Facing Note

For customer-adjacent labs, include a short explanation written for a non-developer stakeholder.

It should say:

* what failed
* what was affected
* what was fixed
* how the fix was verified
* what will reduce recurrence

## Relationship to Part 1 and Part 2

Each lab has two parts:

1. Part 1 — New Chapter Content
2. Part 2 — Cumulative Repetition

The break/fix scenario may appear in either part, but it should usually connect to the new chapter content while forcing the learner to reuse older topics.

## Final Rule

A lab is stronger when something fails safely and is fixed with evidence.

Do not treat failure as an accident to hide. Treat it as part of the lab record.
