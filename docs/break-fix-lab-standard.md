# Break/Fix Lab Standard

## Purpose

Breaking and fixing should be a mandatory part of every PythonLabs lab.

The goal is not only to write working code. The goal is to practise troubleshooting, diagnosis, repair, verification, and incident-style explanation.

## Core Rule

Every lab must include a **Break/Fix** section.

A lab is not complete until the learner has:

1. intentionally broken something
2. observed the failure
3. captured the error, symptom, or incorrect behaviour
4. diagnosed the likely cause
5. fixed the issue
6. rerun tests or checks
7. explained the fix in plain technical language

## Where Break/Fix Fits

Each lab already has two parts:

1. **Part 1 — New Chapter Content**
2. **Part 2 — Cumulative Repetition**

Break/Fix should appear in both parts where practical.

Minimum expectation:

* Part 1 should include at least one break/fix scenario related to the new chapter topic.
* Part 2 should include at least one break/fix scenario that uses earlier topics.

## Break/Fix Format

Each lab brief should include this section:

```text
## Break/Fix Requirement

Break scenario:

Expected failure:

How to observe it:

Diagnosis task:

Fix requirement:

Verification after fix:

Incident-style note:
```

## Types of Things to Break

Use safe, local, synthetic failures only.

Examples:

| Area | Safe break/fix example |
| --- | --- |
| Python basics | wrong type conversion, missing variable, incorrect arithmetic |
| Flow control | wrong branch order, unreachable condition, incorrect priority mapping |
| Functions | missing return value, wrong parameter, repeated logic |
| Lists | off-by-one error, duplicate handling bug, empty list bug |
| Dictionaries | missing key, wrong nested structure, incorrect lookup |
| Strings | bad formatting, whitespace issue, case-sensitivity bug |
| Regex | pattern too broad, pattern too narrow, failed extraction |
| Input validation | accepts invalid input, rejects valid input |
| Files | missing file, wrong path, bad encoding assumption |
| CSV/JSON | malformed row, missing field, invalid JSON |
| SQL | wrong join, missing filter, incorrect aggregation |
| APIs | failed status code, timeout, missing JSON field |
| Docker | missing dependency, wrong command, bad file mount |
| Monitoring | metric missing, wrong threshold, false positive alert |
| AI | unverified generated output, unsafe prompt content, malformed structured output |

## Troubleshooting Evidence

Each lab should capture evidence of the failure and the fix.

Acceptable evidence:

* error message
* traceback
* failed test output
* incorrect program output
* before/after command output
* notes describing the symptom
* test result after the fix

## Testing Requirement

Break/Fix must be connected to testing.

At minimum:

* one test or manual check should fail before the fix
* the same test or check should pass after the fix
* the final documentation should explain what changed

As the labs progress, more break/fix scenarios should be captured through formal tests.

## SRE Relevance

This is the most important part of the lab series because SRE and Forward Deployed Engineering work often starts with something broken.

The learner should practise:

* reading symptoms
* forming a hypothesis
* checking evidence
* making a targeted fix
* verifying recovery
* documenting the incident clearly
* explaining impact and next steps

## Incident-Style Note

Each lab should include a short note after the fix.

Use this structure:

```text
Symptom:
Cause:
Fix:
Verification:
Prevention:
```

## Safety Boundaries

Break only local lab code, local files, sample data, synthetic configs, or disposable containers.

Do not break:

* real services
* company systems
* personal production accounts
* real customer data
* anything outside the lab environment

## Final Rule

Every lab should contain failure on purpose.

The learner should become comfortable seeing errors, reading them, fixing them, and proving the fix worked.
