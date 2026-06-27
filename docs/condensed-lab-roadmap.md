# Condensed Lab Roadmap

## Purpose

This document defines the preferred size and structure of the PythonLabs series.

The goal is to cover the same overall content across **30 total labs** without turning every concept into a tiny isolated exercise.

## Target Lab Count

The PythonLabs series should contain **30 labs total**.

The structure is:

* **20 chapter labs** aligned to the 20 chapters of **Automate the Boring Stuff with Python**
* **10 drilling labs** that consolidate, test, and combine the same material into more practical SRE/software engineering exercises

This keeps the series focused while still covering Python, software engineering, SRE automation, DSA transfer, API design, AI integration, and testing.

## Testing Rule

Everything should be tested.

Every lab should include some form of verification. As the series progresses, testing should become more formal.

Expected testing progression:

| Stage | Testing approach |
| --- | --- |
| Early labs | manual test cases and expected output |
| Functions/data labs | repeatable test inputs and edge cases |
| File/CSV/JSON labs | sample files and output comparison |
| Debugging/API labs | unit tests, error cases, and failure handling |
| Drilling labs | proper test files, regression tests, and verification checklist |
| Capstone drilling labs | tests, logging checks, documentation checks, and production-readiness review |

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

**Automate the Boring Stuff with Python** controls the first 20 labs.

Each of the first 20 labs maps to one primary chapter and one chapter folder.

The final 10 drilling labs reuse the same material, but combine it into more realistic tools and scenarios.

## Distribution

| Phase | Labs | Focus |
| --- | ---: | --- |
| Phase 1 | 1-20 | One practical lab for each Automate chapter |
| Phase 2 | 21-30 | Drilling labs that combine, test, and apply the same content in practical SRE/software engineering scenarios |

## The 20 Chapter Labs

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
| 12 | `12-web-scraping` | public status-page or documentation checker |
| 13 | `13-excel-spreadsheets` | spreadsheet audit/report automation |
| 14 | `14-cloud-spreadsheets` | cloud spreadsheet reporting workflow |
| 15 | `15-pdf-and-word-documents` | document/report extraction workflow |
| 16 | `16-csv-and-json-data` | CSV/JSON asset and incident report generator |
| 17 | `17-time-scheduling-and-program-launching` | scheduled local health-check runner |
| 18 | `18-email-and-messaging` | notification draft or alert message generator |
| 19 | `19-images` | safe image/file processing automation |
| 20 | `20-gui-automation` | safe GUI automation experiment with strict limits |

## The 10 Drilling Labs

The drilling labs should reinforce the same content rather than introduce a separate unrelated track.

| Lab | Focus | Practical outcome |
| --- | --- | --- |
| 21 | Python fundamentals drill | rebuild and improve earlier CLI tools without step-by-step guidance |
| 22 | Flow control/functions drill | incident classifier with functions, edge cases, and tests |
| 23 | Lists/dictionaries/DSA drill | asset inventory analyser using arrays, hash maps, grouping, and duplicate detection |
| 24 | Strings/regex/input validation drill | log and ticket parser with strict validation and bad-input tests |
| 25 | Files/folders drill | evidence organiser that reads, writes, moves, and validates lab files |
| 26 | CSV/JSON/API-style data drill | operational report generator with structured input and output tests |
| 27 | Debugging/testing drill | broken SRE script repair with unit tests and regression checks |
| 28 | AI-assisted developer/SRE drill | AI-assisted review or summary helper with manual verification and safety notes |
| 29 | Mini-project drill | incident toolkit combining CLI, files, JSON, validation, and tests |
| 30 | Capstone drill | SRE operations toolkit polish: tests, README, logging notes, production-readiness review |

## Lab Length

Individual labs can be longer than the earlier beginner labs.

A longer lab is acceptable when it:

* combines related concepts naturally
* produces a practical tool
* includes tests or verification
* has clear operational relevance
* creates better portfolio evidence

## Testing Standard

Every lab should include:

* at least two normal test cases
* at least one edge case or bad-input case
* expected output or expected behaviour
* a verification table
* a note on what still is not tested

Later labs should include actual test files where appropriate.

## Reflection Rule

Even if labs are longer, each lab still ends with exactly seven reflection questions.

## Documentation Rule

The learner solves the lab. ChatGPT handles final documentation and GitHub upload.
