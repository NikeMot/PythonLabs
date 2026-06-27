# Lab Operating Model

## Purpose

This document defines how the PythonLabs series should be run.

The learner should focus on solving the lab. Documentation, lab packaging, GitHub upload, and final write-up structure are handled by ChatGPT in this chat.

## Role Split

| Responsibility | Owner |
| --- | --- |
| Read the lab brief | Learner |
| Solve the lab tasks | Learner |
| Run commands and tests locally | Learner |
| Share outputs, errors, screenshots, or notes when needed | Learner |
| Create the lab brief | ChatGPT |
| Maintain the lab template | ChatGPT |
| Prepare documentation wording | ChatGPT |
| Ask reflection questions | ChatGPT |
| Upload lab briefs and reflection answers to GitHub | ChatGPT |
| Keep files in the correct chapter folder | ChatGPT |

## Lab Flow

1. ChatGPT creates the lab brief and uploads it to the correct `PythonLabs` chapter folder.
2. The learner solves the lab locally.
3. The learner shares the final result, notes, command output, or screenshots as needed.
4. ChatGPT asks exactly seven reflection questions.
5. The learner answers the seven questions.
6. ChatGPT prepares the final lab output/documentation.
7. ChatGPT uploads the reflection answers and final documentation to the correct GitHub folder.

## Reflection Rule

At the end of each lab, ask exactly seven reflection questions.

The questions should cover:

1. the main technical concept practised
2. what was difficult or confusing
3. how the solution works
4. what broke or needed fixing
5. how the lab connects to SRE, automation, or software engineering
6. what would need improving for production use
7. what the learner would do differently next time

## Documentation Rule

The learner should not need to write the full documentation manually.

ChatGPT should turn the learner's answers, notes, errors, and outputs into structured lab documentation using the repository template.

## Upload Rule

Lab files should be uploaded to the folder matching the primary **Automate the Boring Stuff with Python** chapter.

Example:

```text
labs/01-python-basics/lab-01-ticket-intake-calculator.md
```

Reflection answers and final outputs should be uploaded to the same lab folder or as a clearly named follow-up file.

## Naming Convention

Use lower-case, hyphen-separated names.

Examples:

```text
lab-01-ticket-intake-calculator.md
lab-01-reflection.md
lab-01-completed-output.md
```

Avoid names such as:

```text
Final.md
My Work.md
Lab_One.md
```

## Evidence Rule

The learner may provide evidence in simple form:

* copied terminal output
* short notes
* error messages
* screenshots without sensitive data
* final script content
* test results

ChatGPT should organise this evidence into the lab documentation.

## Privacy Rule

Do not upload:

* real company data
* real user data
* secrets
* API keys
* private hostnames
* private screenshots
* book PDFs or EPUBs
* sensitive AI prompts or outputs
