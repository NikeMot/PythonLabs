# Official Online Documentation Policy

## Purpose

This document defines how current online documentation should be used in PythonLabs.

Book chapters provide conceptual study. Official online documentation provides current tool behaviour, commands, APIs, installation guidance, and version-specific details.

## Core Rule

Every lab should include relevant official online documentation where tooling, commands, libraries, APIs, databases, containers, testing, CI/CD, or observability are involved.

The lab should not rely only on memory or book content for tools that change over time.

## Relationship to Book Chapters

Use both where appropriate:

* **Full book chapters** for concepts and deeper study
* **Official online documentation** for current syntax, commands, APIs, options, warnings, and version-specific behaviour

Example:

```text
Primary book chapter: Automate the Boring Stuff with Python — Chapter 16: CSV and JSON Data
Official docs: Python csv module documentation and Python json module documentation
```

## Documentation Checked Field

Each lab reference section should include a documentation check field:

```text
Documentation checked on: YYYY-MM-DD
```

For this project, the date should use the date the lab brief is created or updated.

## Reference Table Format

Each lab should use this reference format:

| Role | Reference | Used for | Date checked |
| --- | --- | --- | --- |
| Primary chapter | Book title — Chapter X | Main concept | YYYY-MM-DD |
| Supplementary chapter | Book title — Chapter Y | Deeper understanding | YYYY-MM-DD |
| Official documentation | Official docs page | Current commands/API/tool behaviour | YYYY-MM-DD |

## Official Documentation Sources

Use official documentation whenever possible.

| Area | Preferred official source |
| --- | --- |
| Python language and standard library | Python documentation |
| Regular expressions | Python `re` module documentation |
| CSV | Python `csv` module documentation |
| JSON | Python `json` module documentation |
| SQLite from Python | Python `sqlite3` module documentation |
| SQLite database concepts | SQLite documentation |
| Testing | pytest documentation and Python unittest documentation where needed |
| HTTP requests | Requests documentation or Python standard library documentation |
| Docker | Docker documentation |
| Docker Compose | Docker documentation |
| Grafana | Grafana documentation |
| Prometheus-style monitoring concepts | Prometheus documentation |
| GitHub Actions | GitHub Actions documentation |
| AI APIs | Official documentation for the selected AI API provider |

## Minimum Online Documentation Use by Lab Type

| Lab type | Online docs required |
| --- | --- |
| Pure Python basics | Python official documentation where syntax or built-in behaviour needs checking |
| Regex labs | Python `re` documentation |
| CSV/JSON labs | Python `csv` and `json` documentation |
| SQL labs | SQLite and Python `sqlite3` documentation |
| API labs | Requests docs, HTTP/API docs, and provider documentation |
| Testing labs | pytest documentation |
| Docker labs | Docker documentation |
| Grafana/monitoring labs | Grafana documentation and relevant monitoring docs |
| CI/CD labs | GitHub Actions documentation |
| AI labs | Official AI API documentation and safety/privacy guidance |

## Currentness Rule

Before creating a lab involving current tooling, check the relevant official documentation.

This applies especially to:

* package installation commands
* Docker commands
* Docker Compose syntax
* GitHub Actions workflow syntax
* Grafana setup or dashboard behaviour
* AI API usage
* third-party Python library APIs

## What Not to Use as the Main Authority

Avoid relying on:

* outdated blog posts
* random tutorials with unknown versions
* copied snippets without explanation
* forum answers unless troubleshooting a specific error
* unofficial summaries when official docs exist

Unofficial material can be useful for context, but official documentation should be the main authority.

## Lab Documentation Requirement

Each lab should include:

* book chapter references
* official online documentation references
* date checked
* what each reference was used for
* any version assumptions

## Version Assumptions

Where relevant, record versions.

Examples:

```text
Python version checked: 3.x
pytest version checked: x.x
Docker version checked: x.x
Grafana version checked: x.x
SQLite version checked: x.x
```

If the exact local version is unknown, the lab should include a command for the learner to check it.

## Final Rule

Books teach the concepts. Official online docs keep the labs current.

Every lab should use the right combination of both.
