# AI for Developers and SRE

## Purpose

This topic area records how AI will be included in the PythonLabs learning path.

AI should be included where it helps build better developer, automation, and SRE skills. It should not replace understanding of Python, software engineering, Linux, networking, cloud, or reliability fundamentals.

## How AI Fits the Lab Track

AI can appear in two ways:

1. As a dedicated topic area for broader AI engineering concepts.
2. As an enrichment section inside relevant Python labs.

The main Python lab order still follows **Automate the Boring Stuff with Python** chapter by chapter.

## AI Topics to Include Over Time

| Topic | Why it matters |
| --- | --- |
| AI-assisted coding | Helps with drafting, reviewing, and refactoring code, but code must still be understood and tested |
| Model APIs | Useful for building internal tools, assistants, classifiers, and automation helpers |
| Structured model output | Important when model output needs to be parsed by scripts or APIs |
| Evaluation | Helps check whether an AI-assisted tool is accurate enough to trust |
| Retrieval | Useful for tools that answer questions from runbooks, logs, docs, or knowledge bases |
| Safety and privacy | Required when working with operational, customer, or company data |
| Human review | AI output should support decisions, not silently replace engineering judgement |
| Reliability | AI features need fallbacks, tests, monitoring, and clear failure behaviour |

## Examples of AI-Enriched Labs

| Automate chapter | AI enrichment idea |
| --- | --- |
| Python Basics | Use AI to review a simple script and compare its suggestions with your own understanding |
| Flow Control | Build a rule-based incident classifier, then compare it with an AI-assisted classification approach later |
| Functions | Refactor repeated AI-helper logic into functions |
| Lists | Rank or filter generated suggestions and check for duplicates |
| Dictionaries | Store structured AI responses as dictionaries |
| Strings | Clean and format AI-generated text safely |
| Regex | Extract incident IDs, hostnames, or error codes from AI-assisted summaries |
| Input Validation | Validate structured AI output before trusting it |
| Files | Save and review AI-assisted reports locally |
| CSV and JSON | Work with JSON responses from model APIs |
| APIs | Call an AI API safely from a Python script |
| Debugging | Use AI as a debugging assistant, then verify the fix independently |

## SRE-Relevant AI Project Ideas

Possible future projects:

* incident summary assistant
* log explanation helper
* runbook search assistant
* ticket quality checker
* alert enrichment helper
* change-risk checklist generator
* post-incident action item extractor
* documentation review assistant

## Rules for AI Use in Labs

* Do not paste private/company data into AI tools.
* Do not commit secrets, keys, or real operational data.
* Do not trust generated code without reading and testing it.
* Record what AI helped with and what you verified yourself.
* Prefer small, testable AI-assisted features over large opaque systems.
* Keep deterministic rule-based logic where reliability is required.
* Use AI as a helper, not as a substitute for engineering judgement.

## Portfolio Angle

Including AI correctly can show that you understand modern developer workflows while still respecting reliability, privacy, testing, and operational risk.

The goal is to become an engineer who can use AI responsibly in software and SRE work, not someone who blindly copies model output.
