# Side-by-Side Book Lab Model

## Purpose

PythonLabs should combine the two selected books inside one lab at a time.

The learner should not complete a separate Automate lab and then a separate Beyond lab. That would double the workload and break the 60–90 minute timebox.

Instead, each lab should be one practical story-driven lab that uses:

1. **Automate the Boring Stuff with Python** for the new Python concept and main build
2. **Beyond the Basic Stuff with Python** for development discipline when relevant
3. **official online documentation** for current tool behaviour

## Core Rule

One lab combines both books where useful.

Automate provides the main chapter path.

Beyond improves how the work is written, debugged, tested, structured, named, explained, or reviewed.

## What This Means in Practice

Each lab should still be one coherent task.

Example:

```text
Lab 04 — Asset Inventory Checker

Automate chapter:
- Lists

Beyond chapter or theme:
- readable names, avoiding common mistakes, or code organisation

Practical outcome:
- build and test an asset inventory checker
- break and fix a list-handling bug
- document the operational reason
```

The learner does one lab, not two.

## Timebox Rule

The side-by-side model must stay inside the 60–90 minute lab timebox.

The Beyond content should be applied lightly and practically. It should not turn the lab into a second reading assignment.

## Reference Rule

Every lab must include the main Automate chapter.

The Beyond chapter appears only when it clearly improves the lab.

Use this format:

| Role | Reference | Used for | Date checked |
| --- | --- | --- | --- |
| Main Python book | Automate the Boring Stuff with Python — Chapter X | New Python concept and main build | YYYY-MM-DD |
| Development companion | Beyond the Basic Stuff with Python — Chapter Y | Debugging, readability, structure, testing, or code quality | YYYY-MM-DD |
| Official docs | Official documentation page | Current behaviour, commands, or APIs | YYYY-MM-DD |

## How Beyond Should Be Used

Beyond should shape the engineering quality of the lab.

Use it for things like:

* better variable and function names
* clearer code layout
* avoiding common Python mistakes
* debugging approach
* error handling
* comments, docstrings, or type hints when appropriate
* project organisation
* testability
* basic performance thinking
* OOP or Big-O later in the track

## What Not to Do

Do not create:

* one Automate exercise plus one separate Beyond exercise
* long theory notes from both books
* a second independent project inside the same lab
* a reading-heavy lab that cannot be completed in 60–90 minutes

## Relationship to the Two-Part Lab Structure

The lab still has two parts:

1. **Part 1 — New Chapter Content**
2. **Part 2 — Cumulative Repetition**

Automate mainly drives Part 1.

Beyond can influence either part, especially break/fix, debugging, naming, structure, and testing.

## Final Rule

One lab. One story. One practical build.

Automate teaches the new Python capability. Beyond improves the way the capability is developed and explained.
