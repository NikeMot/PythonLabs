# Two-Part Lab Structure

## Purpose

Every PythonLabs lab should have two parts.

The purpose is to learn new material while constantly revisiting older material until it becomes automatic.

## Standard Structure

Each lab must include:

1. **Part 1 — New Chapter Content**
2. **Part 2 — Cumulative Repetition**

## Part 1 — New Chapter Content

Part 1 focuses on the new material from the lab's primary chapter.

For the first 20 labs, the primary chapter comes from **Automate the Boring Stuff with Python**.

Part 1 should include:

* the new chapter concept
* a practical scenario
* implementation tasks
* normal test cases
* edge or bad-input test cases
* verification evidence
* production or SRE relevance

Example:

```text
Lab 04 primary chapter: Lists
Part 1 focus: list creation, indexing, slicing, looping, and list methods
Practical outcome: asset inventory checker
```

## Part 2 — Cumulative Repetition

Part 2 revisits all major topics learned so far.

This section should not introduce a completely unrelated project. It should extend the same lab or add a related drill that forces older skills to be reused.

Part 2 should include:

* older topics from previous labs
* at least one task requiring earlier concepts
* tests covering both old and new behaviour
* a short note explaining which previous topics were reused

Example:

```text
Lab 04 Part 2 repetition:
- Python basics from Lab 01
- flow control from Lab 02
- functions from Lab 03
- lists from Lab 04
```

## Cumulative Topic Rule

By Lab N, Part 2 should require practice from Labs 1 through N where practical.

This does not mean every previous topic must appear in equal depth. It means older concepts should keep reappearing in useful ways.

Examples:

| Current lab | Part 2 should revisit |
| --- | --- |
| Lab 02 | Python basics |
| Lab 03 | Python basics, flow control |
| Lab 04 | Python basics, flow control, functions |
| Lab 05 | Python basics, flow control, functions, lists |
| Lab 06 | Python basics, flow control, functions, lists, dictionaries |
| Lab 10 | basics, flow control, functions, data structures, strings, regex, validation, files |
| Lab 20 | all chapter topics introduced so far |
| Labs 21-30 | all core topics, plus SQL, Docker, Grafana, APIs, testing, AI, and deployment workflows where relevant |

## Testing Rule

Both parts must be tested.

Each lab should include:

* at least two normal tests for Part 1
* at least one edge or bad-input test for Part 1
* at least two cumulative tests for Part 2
* a verification table
* a note on what is not yet tested

As the labs progress, tests should move from manual expected-output checks to formal test files.

## Documentation Rule

The lab brief should clearly separate Part 1 and Part 2.

Use this structure:

```text
## Part 1 — New Chapter Content

## Part 2 — Cumulative Repetition

## Testing and Verification

## Reflection Questions
```

## Drilling Labs

Labs 21-30 are still drilling labs.

For those labs, Part 1 should introduce the main drilling scenario, and Part 2 should force repetition across the full earlier track.

Examples:

* SQL report generator plus older CSV/JSON/file/string validation
* Dockerised tool plus older CLI, files, tests, and documentation
* Grafana-ready metrics plus older JSON, SQL, validation, and customer summary writing
* capstone toolkit plus all previous topics

## AI Integration

AI may appear in either part when relevant.

AI should never replace understanding of the topic. If AI is used, the lab must include manual verification and a safety/privacy note.

## Final Rule

Every lab should teach something new and reinforce what came before.

No lab should be treated as complete just because the new chapter topic works. The cumulative repetition section must also be attempted and tested.
