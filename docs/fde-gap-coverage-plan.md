# Forward Deployed Engineer Gap Coverage Plan

## Purpose

This document adds the missing Forward Deployed Engineer capability areas into the 30-lab PythonLabs plan.

The 30-lab structure remains:

* 20 chapter labs based on **Automate the Boring Stuff with Python**
* 10 drilling labs that combine, test, and apply the same content

The added target areas are:

* SQL depth
* Docker hands-on evidence
* Grafana and monitoring
* deployment engineering
* customer-facing technical communication
* stronger testing maturity
* APIs and integration work
* Linux and networking troubleshooting
* warehouse/robot/deployment synthetic data
* CI/CD and portfolio polish

## Coverage Rule

All of these areas should appear in the lab series.

They do not need to appear equally in every lab. They should be introduced gradually and then reinforced in the drilling labs.

## Where Each Gap Is Covered

| Gap | Primary labs | Drilling labs | Evidence expected |
| --- | --- | --- | --- |
| SQL depth | 16 | 23, 26, 29, 30 | queries, joins, aggregation, Python database access |
| Docker | 12, 17 | 27, 29, 30 | Dockerfile, build/run commands, container logs |
| Grafana and monitoring | 11, 17 | 27, 30 | metrics output, dashboard design, monitoring notes |
| Deployment engineering | 09, 10, 17 | 25, 29, 30 | deployment checklist, validation script, rollback notes |
| Customer-facing communication | all labs | 21-30 | issue summary, customer impact note, advisory note |
| Testing maturity | all labs | 21-30 | normal tests, edge cases, bad input, pytest later |
| APIs and integration | 12, 16 | 24, 26, 29 | API client, JSON response handling, timeouts/errors |
| Linux/networking troubleshooting | 11, 17 | 24, 27, 30 | log checks, ports, DNS/HTTP notes, resource checks |
| Warehouse/robot synthetic data | 04, 05, 16 | 23, 26, 29, 30 | customers, sites, robots, runs, incidents, metrics |
| CI/CD and portfolio polish | 11 | 27, 29, 30 | GitHub Actions tests, README, run instructions |

## SQL Requirements

SQL should be strong enough to support customer deployment and incident investigation work.

Minimum SQL outcomes:

* create tables for customers, warehouse sites, robots, deployments, incidents, scan runs, and metrics
* insert synthetic data
* query deployment status
* filter failed deployments or failed scan runs
* aggregate incidents by customer, site, severity, and service
* join customer, site, robot, deployment, and incident tables
* export SQL results to CSV or JSON using Python
* explain query results in customer-facing language

SQLite is acceptable for local labs. PostgreSQL can be added later as a stretch target.

## Docker Requirements

Docker should be used to prove that selected Python tools can run consistently outside the local editor.

Minimum Docker outcomes:

* write a Dockerfile for at least one Python tool
* build the image
* run the container
* pass input and output files safely
* use environment variables without committing secrets
* inspect container logs
* debug at least one container failure
* document build and run commands

## Grafana and Monitoring Requirements

Grafana should be introduced through monitoring-style lab outputs.

Minimum monitoring outcomes:

* generate synthetic metrics from Python
* produce deployment health, scan duration, failure count, and incident count data
* store metrics in CSV, JSON, SQLite, or another simple local format
* design Grafana dashboard panels
* explain what each panel tells a deployment engineer or customer
* include only safe screenshots if screenshots are used

## Deployment Engineering Requirements

The labs should simulate customer deployment work.

Minimum deployment outcomes:

* pre-deployment checklist
* environment validation script
* version/configuration check
* health-check script
* deployment evidence folder
* failure and rollback notes
* customer handover summary
* known issues section

## Customer-Facing Communication Requirements

Every substantial lab should include a short customer-facing or stakeholder-facing explanation.

Examples:

* incident summary
* customer impact note
* technical recommendation
* deployment readiness note
* root-cause summary
* known issue explanation
* handover note

The writing should be clear, factual, and technically accurate.

## Testing Requirements

Everything should be tested.

Minimum testing standard for every lab:

* at least two normal test cases
* at least one edge case or bad-input case
* expected result
* actual result
* verification table
* note on what is not yet tested

From the drilling labs onward, use formal test files where appropriate, especially with `pytest`.

## API and Integration Requirements

The series should include API and integration work.

Minimum API outcomes:

* call an HTTP endpoint or local mock endpoint
* handle JSON responses
* check status codes
* handle timeouts or failed responses
* parse useful fields from API output
* save results to CSV, JSON, or SQLite
* document API assumptions and failure modes

## Linux and Networking Troubleshooting Requirements

The labs should connect Python to operational troubleshooting.

Minimum troubleshooting outcomes:

* inspect logs
* check whether a port is expected to be open
* understand HTTP status results
* record DNS or hostname assumptions
* check disk, memory, or runtime data where appropriate
* explain failure symptoms, likely causes, and next checks

## Synthetic Warehouse Data Standard

Use synthetic data that resembles a warehouse robotics or logistics environment.

Safe example entities:

* customers
* warehouse sites
* robots
* scan runs
* software versions
* deployment windows
* incidents
* alerts
* battery metrics
* scan duration metrics
* inventory discrepancy counts
* site health checks

Never use real customer or company data.

## CI/CD and Portfolio Polish Requirements

The later labs should make the repository look like a serious engineering portfolio.

Minimum outcomes:

* clean README files
* clear run instructions
* sample data
* `requirements.txt` or `pyproject.toml` where appropriate
* test command documented
* GitHub Actions test workflow by the drilling phase
* Docker build instructions by the drilling phase
* production-readiness notes
* runbooks or handover notes for larger labs

## Final Outcome

By Lab 30, PythonLabs should demonstrate readiness for a Forward Deployed Engineer conversation by showing:

* practical Python tools
* tested code
* SQL reporting
* deployment-style troubleshooting
* Docker usage
* monitoring/Grafana thinking
* API and JSON handling
* customer-facing technical writing
* synthetic warehouse operations data
* production-readiness awareness
