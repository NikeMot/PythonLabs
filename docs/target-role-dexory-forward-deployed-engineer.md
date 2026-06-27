# Target Role Alignment — Dexory Forward Deployed Engineer

## Role Target

Target role: **Forward Deployed Engineer** at Dexory.

Based on the provided role summary, the target capability areas are:

* customer deployment support
* technical issue investigation
* system performance monitoring
* technical advisory work
* Python
* SQL
* Docker
* Grafana
* solutions engineering
* logistics/warehouse technology context

## Why This Role Fits PythonLabs

Forward Deployed Engineering sits between software engineering, customer delivery, troubleshooting, data analysis, and operations.

That matches the purpose of PythonLabs: practical Python, automation, testing, SRE-style troubleshooting, structured data handling, and operational tooling.

## Skills to Prove Through the 30 Labs

| Role requirement | Evidence to build in PythonLabs |
| --- | --- |
| Python proficiency | tested CLI tools, parsers, validators, report generators, API clients |
| SQL proficiency | drilling labs using SQLite/PostgreSQL-style queries, joins, filtering, aggregation |
| Docker experience | containerise selected tools and run them reproducibly |
| Grafana experience | create metrics/logging data and visualise it in dashboards later |
| Monitoring system performance | health-check scripts, metrics output, alert-style reports |
| Investigating technical issues | debugging labs, log parsing, incident analysis, root-cause notes |
| Customer deployments | deployment checklists, runbooks, environment validation scripts |
| Technical advisory | clear README files, decision notes, issue explanations, final reflections |

## Roadmap Adjustment

The 30-lab plan remains:

* 20 chapter labs based on Automate the Boring Stuff with Python
* 10 drilling labs

However, the drilling labs should explicitly include Dexory-relevant skills:

| Drilling lab | Dexory-oriented emphasis |
| --- | --- |
| 21 | rebuild CLI tools with cleaner structure and tests |
| 22 | incident classifier with edge cases and customer-impact reasoning |
| 23 | asset/inventory analyser using lists, dictionaries, grouping, and DSA patterns |
| 24 | log and ticket parser with regex, validation, and failure examples |
| 25 | deployment evidence organiser for customer rollout files |
| 26 | SQL + CSV/JSON operational report generator |
| 27 | debug a broken deployment/support script with regression tests |
| 28 | AI-assisted review/summarisation with manual verification and privacy rules |
| 29 | Dockerised incident/deployment toolkit with tests |
| 30 | monitoring/reporting capstone with Grafana-ready metrics and production-readiness notes |

## SQL Additions

SQL should be included mainly in the drilling labs and project-style work.

Minimum SQL evidence:

* create tables for customers, sites, robots, deployments, incidents, and metrics
* insert sample synthetic data
* query deployment status
* filter failed runs
* aggregate incident counts by site/service/severity
* join customer/site/device data
* export query results to CSV or JSON
* use Python to query the database safely

SQLite is acceptable for local labs. PostgreSQL can be added later if needed.

## Docker Additions

Docker should be introduced after the Python basics are stable.

Minimum Docker evidence:

* write a Dockerfile for one Python tool
* run the tool in a container
* pass input/output files safely
* avoid baking secrets into images
* document build and run commands
* explain when Docker helps with customer deployments

## Grafana Additions

Grafana should be introduced through monitoring-style labs.

Minimum Grafana evidence:

* produce metrics-like data from Python scripts
* store or expose synthetic metrics
* design dashboard panels for deployment health, failures, and performance
* explain what each panel would tell a customer or deployment engineer
* include screenshots only if they contain no sensitive information

## Testing Requirement

Every lab should be tested.

For this target role, testing matters because a Forward Deployed Engineer may run tools in customer-adjacent environments where bad assumptions can waste deployment time or damage trust.

Evidence should include:

* normal cases
* edge cases
* bad input cases
* expected output
* actual output
* what is still not tested

## Portfolio Outcome

By the end of the 30 labs, the repository should show evidence that the learner can:

* write practical Python tools
* test and debug their own code
* process operational data
* query and report on SQL data
* work with files, CSV, JSON, and APIs
* reason about deployment failures
* containerise tools with Docker
* design monitoring outputs suitable for Grafana
* document decisions clearly
* explain technical issues in a customer-facing way

## Interview Story

The final portfolio story should be:

> I built a tested Python operations toolkit across 30 labs. The work includes ticket and incident tooling, log parsing, asset analysis, CSV/JSON reporting, SQL-backed operational reports, Dockerised utilities, monitoring-style outputs, and documentation written as if supporting real customer deployments.
