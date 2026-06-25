# Commit Strategy

## Purpose

This document defines how commits should be made in this repository.

The goal is to keep the history readable, reviewable, and safe to revert.

## Commit Principles

Commits should be:

* small
* logical
* complete
* descriptive
* safe to revert where possible

## When to Commit

Commit when one logical unit of work is complete.

Examples:

* Add repository documentation
* Add chapter folder structure
* Add a new lab brief
* Add completed lab output
* Fix a specific documentation error
* Add tests for one script

## When Not to Commit

Do not commit when:

* secrets or credentials are present
* unrelated changes are mixed together
* the change cannot be explained
* the repository is in a broken or confusing state
* book PDFs, EPUBs, or copyrighted material are present
* private/company data is included

## Commit Message Style

Use short, descriptive messages.

Examples:

```text
Create PythonLabs README
Add Python-focused gitignore
Document repository design
Add Python Basics ticket intake lab
Add Flow Control chapter folder
```

Avoid vague messages such as:

```text
stuff
update
final
work
changes
```

## Pre-Commit Checklist

Before committing locally, run through this checklist:

1. Run `git status`.
2. Review unstaged changes.
3. Review staged changes with `git diff --staged`.
4. Confirm no secrets are included.
5. Confirm no private/company data is included.
6. Confirm the commit has one clear purpose.
7. Write a meaningful commit message.

## Branching Rules

Use branches when a change is risky, large, experimental, or separate from current work on `main`.

Create a branch for:

* a new multi-file lab
* a major documentation update
* repository restructuring
* experimental tooling
* changes that should be reviewed before merging

Branch examples:

```text
lab/python-basics-ticket-intake
lab/flow-control-priority-engine
project/sre-toolkit
fix/readme-navigation
```

When working alone, small documentation updates can be committed directly to `main`.

In a team or production environment, changes should normally be made on a branch and merged through a pull request.
