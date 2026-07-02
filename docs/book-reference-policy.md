# Book Reference Policy

## Purpose

This document defines the simplified book policy for PythonLabs.

The previous reference model was too broad. PythonLabs should not pull from many different programming books at once.

The lab series now uses:

1. **one main Python book**
2. **one companion Python development book**
3. **official online documentation** for current tools and version-specific behaviour

## Core Rule

Use only two books by default.

| Role | Book | Purpose |
| --- | --- | --- |
| Main Python book | Automate the Boring Stuff with Python | Core Python learning path and chapter-lab structure |
| Development companion book | Beyond the Basic Stuff with Python | Professional Python development habits, debugging, readability, project organisation, code quality, OOP, and Big-O |

No other book should be added to normal lab references unless the learner explicitly asks for it.

## Main Python Book Rule

The first 20 labs should follow **Automate the Boring Stuff with Python** as the primary Python book.

That book controls:

* the chapter sequence
* the primary topic of each lab
* the folder name
* the new Python concept introduced in Part 1

Use full chapters, not small fragments.

Reference format:

```text
Automate the Boring Stuff with Python — Chapter X: Chapter Title
```

## Development Companion Book Rule

Use **Beyond the Basic Stuff with Python** as the single companion book for Python development practice.

Use it when a lab needs development discipline such as:

* dealing with errors
* command-line confidence
* code formatting
* readable names
* code smells
* Pythonic code
* common Python gotchas
* effective functions
* comments, docstrings, and type hints
* project organisation with Git
* performance and Big-O
* object-oriented programming

Use full chapters, not small fragments.

Reference format:

```text
Beyond the Basic Stuff with Python — Chapter X: Chapter Title
```

## Official Online Documentation Rule

Use official online documentation for anything that changes over time or depends on current tool behaviour.

Examples:

| Area | Main authority |
| --- | --- |
| Python syntax and standard library | Python official documentation |
| pytest | pytest documentation |
| SQLite | Python `sqlite3` documentation and SQLite documentation |
| Docker | Docker documentation |
| Docker Compose | Docker documentation |
| Grafana | Grafana documentation |
| GitHub Actions | GitHub Actions documentation |
| AI APIs | official provider documentation |
| third-party libraries | official library documentation |

Official documentation is not counted as an extra book.

## What Not to Do

Do not add a large reading list to each lab.

Do not reference lots of books such as:

* Learning Python
* Fluent Python
* Test-Driven Development with Python
* Architecture Patterns with Python
* A Philosophy of Software Design
* The Algorithm Design Manual
* Clean Code
* Effective Python

These may be useful later, but they are not part of the default PythonLabs reference system.

## Lab Reference Format

Each lab should use this simple table:

| Role | Reference | Used for | Date checked |
| --- | --- | --- | --- |
| Main Python book | Automate the Boring Stuff with Python — Chapter X | New chapter content | YYYY-MM-DD |
| Development companion | Beyond the Basic Stuff with Python — Chapter Y | Development practice, if relevant | YYYY-MM-DD |
| Official docs | Official documentation page | Current commands, APIs, or library behaviour | YYYY-MM-DD |

The companion book row should only appear when it is genuinely useful for that lab.

## Timebox Protection

The two-book policy supports the 60–90 minute lab timebox.

References should support the lab. They should not turn the lab into a reading assignment.

## Final Rule

One Python book. One Python development book. Official documentation for current tooling.

Keep the references focused so the learner spends most of the session solving the lab, breaking and fixing things, testing, and explaining the result.
