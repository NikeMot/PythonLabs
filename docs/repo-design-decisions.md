# Repository Design Decisions

## Context

This repository contains a sequence of Python and software engineering labs. The core path follows **Automate the Boring Stuff with Python** chapter by chapter.

The repository also needs to support broader SRE/software engineering development, including:

* Python automation
* CLI tooling
* data parsing
* file handling
* API clients and API design
* testing and debugging
* DSA and LeetCode-style pattern transfer
* software design and maintainability
* operational/SRE tooling

## Decision

Use a single repository divided into numbered chapter folders under `labs/`.

Each numbered folder maps to one chapter/topic from **Automate the Boring Stuff with Python**.

Example:

```text
labs/01-python-basics/
labs/02-flow-control/
labs/03-functions/
```

Individual labs are stored inside the relevant chapter folder using lower-case, hyphen-separated names.

Example:

```text
labs/01-python-basics/lab-01-ticket-intake-calculator.md
```

## Rationale

A single repository shows one connected learning path and avoids cluttering GitHub with many small repositories.

Numbered folders make the learning order obvious.

Chapter-based folders keep the Python learning path aligned with the primary book while still allowing enrichment from other books and SRE scenarios.

Separating `docs/` from `labs/` keeps general standards separate from lab-specific work.

## Naming Convention

Use this style:

```text
01-python-basics
02-flow-control
03-functions
```

Use lower-case words separated by hyphens.

For individual lab files, use:

```text
lab-01-short-lab-name.md
lab-02-short-lab-name.md
```

## Alternatives Considered

| Alternative | Reason it was not chosen |
| --- | --- |
| One repo per chapter | Too many repositories; harder to review as a learning journey |
| One flat `labs/` folder | Would become difficult to navigate as labs grow |
| Folders by tool only | The current Python roadmap is book/chapter-led, not tool-led |
| Notes-only repository | Labs should produce evidence, not just summaries |

## Consequences

This structure is easy to navigate but requires consistent naming.

When a lab touches multiple skills, it should still live under the primary **Automate** chapter folder. Supplementary concepts should be listed in the lab's reference section.

## Future Changes

Later, the repository may add top-level folders for larger projects, for example:

```text
projects/
  sre-toolkit/
  incident-api/
  log-parser/
```

These should only be added when the daily labs grow into larger, multi-chapter projects.
