# PythonLabs

## Overview

The `PythonLabs` repository contains hands-on Python and software engineering labs aimed at developing practical automation, tooling, and SRE-adjacent development skills.

The main learning path follows **Automate the Boring Stuff with Python** chapter by chapter. Each lab is enriched with deeper material from books such as **Learning Python**, **Fluent Python**, **Architecture Patterns with Python**, **Test-Driven Development with Python**, **A Philosophy of Software Design**, and DSA/algorithm references when the timing is right.

The goal is not to collect notes. The goal is to build small, useful tools and document them with evidence, verification, decisions, and production relevance.

---

## Goals

The goals of this repository are to:

* Build practical Python skill through daily labs
* Connect Python learning to SRE, platform engineering, automation, and operations
* Practise software engineering habits early: structure, testing, documentation, Git, and reviewable changes
* Build evidence of problem solving, debugging, and operational thinking
* Gradually introduce API design, DSA, LeetCode-style patterns, Go, Java, and production-system thinking when appropriate

---

## Skills Covered

| Area | Status | Topics |
| --- | --- | --- |
| Python basics | In progress | variables, expressions, input/output, type conversion |
| Flow control | Not started | `if`, `elif`, `else`, loops, boolean logic |
| Functions | Not started | decomposition, parameters, return values, scope |
| Data structures | Not started | lists, dictionaries, sets, tuples, frequency maps |
| Strings and regex | Not started | parsing, validation, extraction, log analysis |
| Files and data formats | Not started | text files, CSV, JSON, paths |
| Debugging and testing | Not started | tracebacks, assertions, unit tests, edge cases |
| APIs and automation | Not started | HTTP, JSON APIs, API clients, service tooling |
| Software design | Not started | clean structure, modules, naming, maintainability |
| DSA / LeetCode transfer | Not started | arrays, hash maps, sorting, searching, stacks, queues |
| SRE tooling | Not started | health checks, config validators, incident helpers, log parsers |

---

## Repository Structure

The `labs/` folder is organised by the chapters of **Automate the Boring Stuff with Python**.

```text
PythonLabs/
├── README.md
├── .gitignore
├── docs/
│   ├── commit-strategy.md
│   ├── lab-output-template.md
│   ├── python-lab-system.md
│   └── repo-design-decisions.md
├── labs/
│   ├── 01-python-basics/
│   ├── 02-flow-control/
│   ├── 03-functions/
│   ├── 04-lists/
│   ├── 05-dictionaries-and-structuring-data/
│   ├── 06-manipulating-strings/
│   ├── 07-pattern-matching-with-regular-expressions/
│   ├── 08-input-validation/
│   ├── 09-reading-and-writing-files/
│   ├── 10-organizing-files/
│   ├── 11-debugging/
│   ├── 12-web-scraping/
│   ├── 13-working-with-excel-spreadsheets/
│   ├── 14-working-with-google-sheets/
│   ├── 15-working-with-pdf-and-word-documents/
│   ├── 16-working-with-csv-files-and-json-data/
│   ├── 17-keeping-time-scheduling-tasks-and-launching-programs/
│   ├── 18-sending-email-and-text-messages/
│   ├── 19-manipulating-images/
│   └── 20-controlling-the-keyboard-and-mouse-with-gui-automation/
└── scripts/
```

---

## How to Use This Repository

Each lab folder contains a lab brief and, later, any output/evidence files created while completing the lab.

Each lab should normally include:

* Scenario
* Reference material
* Requirements
* Constraints
* Implementation tasks
* Verification evidence
* Issues encountered
* Decisions made
* Security and production considerations
* Reflection questions

Start with `labs/01-python-basics/`.

---

## Security and Privacy Notes

The repository must not contain:

* passwords
* API keys
* SSH private keys
* `.env` files
* cloud credentials
* company/private data
* screenshots containing private account or tenant information
* book PDFs, EPUBs, or copyrighted source material
* generated secrets or tokens used during experiments

---

## Current Progress

| Folder | Status |
| --- | --- |
| `01-python-basics` | In progress |
| `02-flow-control` onwards | Not started |
