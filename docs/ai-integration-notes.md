# AI Integration Notes

## Purpose

AI will be included in PythonLabs as a useful software engineering and SRE skill area.

The main learning order still follows **Automate the Boring Stuff with Python**. AI is added when it helps the lab become more realistic, modern, or production-aware.

## Integration Rule

Every lab can include an optional **AI Extension** section when relevant.

The AI Extension should answer:

* What AI concept is being introduced?
* Why is it relevant to developers or SREs?
* What should be verified manually?
* What should not be trusted automatically?
* What privacy or safety issue could appear?

## When to Add AI

Add AI when the lab touches:

* text summarisation
* log or ticket explanation
* classification
* structured output
* API calls
* JSON processing
* documentation generation
* code review
* debugging
* testing support
* runbook search
* operational decision support

## When Not to Add AI

Do not add AI when it would distract from the core Python concept.

Early beginner labs should stay focused on Python fundamentals. AI can be mentioned as a future extension, but it should not make the core lab harder.

## Standard AI Extension Format

```text
## AI Extension

Concept:

Use case:

Task:

Verification:

Risks:

Production note:
```

## Safety Rules

* Do not use real company data.
* Do not commit secrets or credentials.
* Do not rely on AI output without testing.
* Do not let AI make production decisions without human review.
* Keep examples small, synthetic, and safe.
* Prefer explainable rule-based logic where deterministic behaviour is required.
