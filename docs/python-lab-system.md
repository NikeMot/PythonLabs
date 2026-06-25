# Python Lab System

## Primary Guide

Daily Python labs follow **Automate the Boring Stuff with Python** as the main chapter-by-chapter roadmap.

Each lab should be anchored to exactly one primary chapter from Automate.

## Enrichment Sources

Other books and concepts may be used to deepen the lab:

| Source | Use |
| --- | --- |
| Learning Python | deeper fundamentals, objects, names, types, scope, modules |
| Fluent Python | idiomatic Python and better Python style when appropriate |
| Architecture Patterns with Python | maintainability, project structure, boundaries, services |
| Test-Driven Development with Python | tests, assertions, test design, confidence in changes |
| A Philosophy of Software Design | decomposition, complexity reduction, naming, interfaces |
| The Algorithm Design Manual | DSA and algorithmic reasoning when appropriate |
| Discrete Mathematics with Applications | logic, sets, counting, graph thinking when appropriate |
| SRE/DevOps books | reliability, observability, production concerns, automation value |

## Lab Style

Labs should be beginner-friendly but meaningful.

They should not be copy-paste tutorials. They should provide enough guidance to start, while still requiring independent thinking, testing, and reference checking.

Each lab should include:

* a realistic operational or software engineering scenario
* requirements and constraints
* expected files or script outputs
* implementation tasks
* verification evidence
* reflection questions
* security and production considerations
* optional stretch work

## SRE Angle

Each lab should connect Python to operational usefulness where possible.

Examples:

* ticket intake tools
* incident priority calculators
* log parsers
* config validators
* JSON/YAML/CSV processors
* API clients
* health check scripts
* report generators
* automation helpers

## DSA / LeetCode Timing

DSA and LeetCode-style tasks should be introduced when the topic naturally supports them.

Examples:

| Python topic | DSA transfer |
| --- | --- |
| Lists | arrays, searching, sorting |
| Dictionaries | hash maps, frequency counting |
| Strings | parsing, validation, sliding windows later |
| Files | streaming records, line-by-line processing |
| Regex | pattern matching and extraction |
| APIs | pagination, caching, deduplication |

The DSA section should show both:

1. the abstract algorithm pattern, and
2. the SRE/software engineering version of the same pattern.

## Upload Rule

When a lab is created in this chat, it should be uploaded to the appropriate chapter folder in this repository.

Example:

```text
labs/01-python-basics/lab-01-ticket-intake-calculator.md
```

## Naming Rule

Use lower-case, hyphen-separated paths.

Good:

```text
01-python-basics
lab-01-ticket-intake-calculator.md
```

Avoid:

```text
Lab_One
Python Basics
Final Work.md
```
