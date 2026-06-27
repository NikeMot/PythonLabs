# Condensed Lab Roadmap

## Purpose

This document defines the preferred size and structure of the PythonLabs series.

The goal is to keep the series practical and substantial without turning every book chapter into a separate small exercise.

## Target Lab Count

The main PythonLabs series should contain approximately **24 to 30 labs**.

This is the preferred range because it is large enough to cover Python, software engineering, SRE automation, DSA transfer, API design, and AI integration, while still being focused enough to complete.

## Design Principle

Labs may be longer and more practical if that allows related concepts to be combined naturally.

The series should avoid tiny isolated exercises where possible.

A good lab should produce something useful, such as:

* a command-line tool
* a parser
* a validator
* a report generator
* an API client
* a testable module
* a small automation workflow
* an AI-assisted operational helper
* a portfolio-quality mini-project

## Relationship to Automate Chapters

**Automate the Boring Stuff with Python** still controls the learning order, but one lab may cover:

* one chapter in depth, or
* one primary chapter plus related concepts from nearby chapters, or
* one practical project that combines several previously learned chapters.

Each lab should still name one primary Automate chapter for placement in the repository.

## Proposed Distribution

| Phase | Labs | Focus |
| --- | ---: | --- |
| Phase 1 | 1-6 | Python fundamentals and basic command-line tools |
| Phase 2 | 7-12 | data structures, strings, regex, validation, and DSA transfer |
| Phase 3 | 13-18 | files, CSV, JSON, spreadsheets, document automation, and reports |
| Phase 4 | 19-23 | debugging, testing, APIs, scheduling, and operational automation |
| Phase 5 | 24-27 | AI-assisted developer/SRE tooling and safer AI workflows |
| Phase 6 | 28-30 | capstone SRE software engineering projects |

## Example Condensed Lab Plan

| Lab | Primary folder | Practical outcome |
| --- | --- | --- |
| 01 | `01-python-basics` | ticket intake calculator |
| 02 | `02-flow-control` | incident priority decision engine |
| 03 | `03-functions` | reusable ticket and escalation helper functions |
| 04 | `04-lists` | asset inventory checker with duplicate detection |
| 05 | `05-dictionaries-and-structuring-data` | incident summary and service ownership mapper |
| 06 | `06-working-with-strings` | ticket note formatter and text cleaner |
| 07 | `07-pattern-matching-with-regular-expressions` | log and incident ID extractor |
| 08 | `08-validating-user-input` | safer command-line input validator |
| 09 | `09-file-io` | read/write ticket and incident evidence files |
| 10 | `10-organizing-files` | lab evidence organiser |
| 11 | `11-debugging` | debug and harden a broken operations script |
| 12 | `16-csv-and-json-data` | CSV/JSON asset and incident report generator |
| 13 | `13-excel-spreadsheets` | spreadsheet audit/report automation |
| 14 | `15-pdf-and-word-documents` | document/report extraction workflow |
| 15 | `12-web-scraping` | public status-page or documentation checker |
| 16 | `17-time-scheduling-and-program-launching` | scheduled local health-check runner |
| 17 | `18-email-and-messaging` | notification draft or alert message generator |
| 18 | `20-gui-automation` | safe GUI automation experiment with strict limits |
| 19 | `04-lists` / `05-dictionaries-and-structuring-data` | DSA transfer lab: arrays, hash maps, grouping |
| 20 | `16-csv-and-json-data` | API-style JSON processing and structured output |
| 21 | `topics/ai-for-developers-and-sre` | AI-assisted code review and verification lab |
| 22 | `topics/ai-for-developers-and-sre` | structured AI output validation lab |
| 23 | `topics/ai-for-developers-and-sre` | runbook/ticket summarisation helper design |
| 24 | `12-web-scraping` / API topic | API client for operational data |
| 25 | `11-debugging` | testing and logging upgrade lab |
| 26 | `projects/incident-toolkit` | incident toolkit mini-project |
| 27 | `projects/log-analysis-toolkit` | log analysis mini-project |
| 28 | `projects/config-validator` | config validation mini-project |
| 29 | `projects/sre-operations-toolkit` | integrated SRE toolkit capstone |
| 30 | `projects/sre-operations-toolkit` | production hardening, README, tests, and portfolio polish |

## Lab Length

Individual labs can be longer than the earlier beginner labs.

A longer lab is acceptable when it:

* combines related concepts naturally
* produces a practical tool
* includes testing or verification
* has clear operational relevance
* creates better portfolio evidence

## Reflection Rule

Even if labs are longer, each lab still ends with exactly seven reflection questions.

## Documentation Rule

The learner solves the lab. ChatGPT handles final documentation and GitHub upload.
