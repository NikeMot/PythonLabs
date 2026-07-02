# Side-by-Side Book Lab Model

## Purpose

PythonLabs should combine the two selected books inside one lab at a time.

The learner should not complete a separate Automate lab and then a separate Beyond lab. That would double the workload and break the 60–90 minute timebox.

Instead, each lab should be one practical story-driven lab that uses:

1. **Automate the Boring Stuff with Python** for the new Python concept and main build
2. **Beyond the Basic Stuff with Python** for development discipline
3. **official online documentation links** for current tool behaviour

## Core Rule

One lab combines both books and relevant official documentation.

Every lab should include:

* one chapter from **Automate the Boring Stuff with Python**
* one chapter from **Beyond the Basic Stuff with Python**
* links to relevant official documentation

Automate provides the main chapter path.

Beyond improves how the work is written, debugged, tested, structured, named, explained, or reviewed.

Official documentation keeps commands, APIs, modules, and tooling current.

## What This Means in Practice

Each lab should still be one coherent task.

Example:

```text
Lab 04 — Asset Inventory Checker

Automate chapter:
- Automate the Boring Stuff with Python — Chapter 4: Lists
- Link: https://automatetheboringstuff.com/

Beyond chapter:
- Beyond the Basic Stuff with Python — relevant chapter on naming, readability, or common mistakes
- Link: https://inventwithpython.com/beyond/

Official documentation:
- Python list/data structure documentation
- Link: https://docs.python.org/3/tutorial/datastructures.html

Practical outcome:
- build and test an asset inventory checker
- break and fix a list-handling bug
- document the operational reason
```

The learner does one lab, not two.

## Timebox Rule

The side-by-side model must stay inside the 60–90 minute lab timebox.

The Beyond content should be applied practically. It should not turn the lab into a second reading assignment.

## Reference Rule

Every lab must include:

1. one main Automate chapter
2. one Beyond chapter
3. one or more official documentation links

Use this format:

| Role | Reference | Link | Used for | Date checked |
| --- | --- | --- | --- | --- |
| Main Python book | Automate the Boring Stuff with Python — Chapter X: Title | https://automatetheboringstuff.com/ | New Python concept and main build | YYYY-MM-DD |
| Development companion | Beyond the Basic Stuff with Python — Chapter Y: Title | https://inventwithpython.com/beyond/ | Debugging, readability, structure, testing, or code quality | YYYY-MM-DD |
| Official docs | Official documentation page title | Direct official docs URL | Current behaviour, commands, APIs, or standard-library details | YYYY-MM-DD |

## Official Documentation Link Rule

Official documentation links should point to the specific relevant page, not only the homepage, when possible.

Examples:

| Topic | Official documentation link |
| --- | --- |
| Python tutorial | https://docs.python.org/3/tutorial/ |
| Python data structures | https://docs.python.org/3/tutorial/datastructures.html |
| Python functions | https://docs.python.org/3/tutorial/controlflow.html#defining-functions |
| Python `re` module | https://docs.python.org/3/library/re.html |
| Python `csv` module | https://docs.python.org/3/library/csv.html |
| Python `json` module | https://docs.python.org/3/library/json.html |
| Python `pathlib` module | https://docs.python.org/3/library/pathlib.html |
| Python `sqlite3` module | https://docs.python.org/3/library/sqlite3.html |
| SQLite documentation | https://www.sqlite.org/docs.html |
| pytest documentation | https://docs.pytest.org/ |
| Docker documentation | https://docs.docker.com/ |
| Dockerfile reference | https://docs.docker.com/reference/dockerfile/ |
| Docker Compose documentation | https://docs.docker.com/compose/ |
| Grafana documentation | https://grafana.com/docs/grafana/latest/ |
| GitHub Actions documentation | https://docs.github.com/actions |

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
* vague official documentation references without links

## Relationship to the Two-Part Lab Structure

The lab still has two parts:

1. **Part 1 — New Chapter Content**
2. **Part 2 — Cumulative Repetition**

Automate mainly drives Part 1.

Beyond can influence either part, especially break/fix, debugging, naming, structure, and testing.

Official documentation supports both parts where current behaviour matters.

## Final Rule

One lab. One story. One practical build.

Each lab includes one Automate chapter, one Beyond chapter, and direct links to relevant official documentation.

Automate teaches the new Python capability. Beyond improves the way the capability is developed and explained. Official docs keep the lab current.
