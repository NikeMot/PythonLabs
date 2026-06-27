# Book Reference Policy

## Purpose

This document defines how reference books should be used in PythonLabs.

The lab series should use complete chapters as study units. It should not be built from scattered small extracts.

## Main Rule

When a book is used in a lab, use a full chapter as the reference unit.

A reference should be written like this:

```text
Book Title — Chapter X: Chapter Title
```

## Primary Chapter Rule

Each of the first 20 labs has one primary chapter from **Automate the Boring Stuff with Python**.

That chapter decides:

* the lab topic
* the lab folder
* the main Python concept
* the expected difficulty

Example:

```text
Primary reference: Automate the Boring Stuff with Python — Chapter 4: Lists
Folder: labs/04-lists/
```

## Supplementary Chapter Rule

Other books may be used to strengthen the lab, but they should also be used as full chapters.

Examples:

| Area | Reference style |
| --- | --- |
| Python fundamentals | Learning Python — full relevant chapter |
| Idiomatic Python | Fluent Python — full relevant chapter |
| Testing | Test-Driven Development with Python — full relevant chapter |
| Design | A Philosophy of Software Design — full relevant chapter |
| Algorithms | The Algorithm Design Manual — full relevant chapter |
| SQL | SQL book or official database guide — full relevant chapter or full guide page |
| Docker | Docker documentation — full guide page |
| Grafana | Grafana documentation — full guide page |
| AI APIs | Official API documentation — full guide page |

## Lab Reference Format

Each lab should use this table style:

| Role | Reference | Used for |
| --- | --- | --- |
| Primary | Automate the Boring Stuff with Python — Chapter X: Title | Main lab topic |
| Supplementary | Book Title — Chapter Y: Title | Deeper understanding |
| Tooling | Official documentation — full guide page | Tool commands or current API behaviour |

## If a Chapter Is Large

A lab may focus on the parts of a chapter needed for the build, but the reference remains the full chapter.

Example:

```text
Reference: Learning Python — full chapter on functions
Lab focus: function definitions, parameters, return values, and scope
```

## Reason

Full-chapter references make the series more rigorous. They show that the learner is studying complete concepts and then applying them in practical tools.
