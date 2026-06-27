# Lab 30 — SRE Operations Toolkit Capstone

## Purpose

Lab 30 is the final capstone lab for the PythonLabs series.

It should be explicitly SRE-relevant and should combine the major skills developed across the first 29 labs.

The capstone should prove that the learner can build, test, document, and explain a practical operations tool rather than only complete isolated Python exercises.

## Capstone Theme

Build an **SRE Operations Toolkit** for a synthetic warehouse robotics/customer deployment environment.

The toolkit should help a Forward Deployed Engineer or SRE-style engineer investigate deployment health, incident data, system checks, and customer-facing operational status.

## Required Capstone Capabilities

The capstone should include evidence of:

* Python CLI tooling
* functions and modular structure
* lists, dictionaries, strings, regex, files, CSV, and JSON
* input validation
* SQL-backed reporting
* API-style data handling or mock integration
* error handling and debugging
* tests and regression checks
* Docker usage
* monitoring or Grafana-ready metrics
* deployment validation
* customer-facing technical explanation
* SRE-style production-readiness notes

## Suggested Capstone Scenario

A customer warehouse site has completed a robot/software deployment.

The engineering team needs a local toolkit that can:

1. validate deployment evidence files
2. load synthetic robot/site/incident data
3. check for failed scan runs or unhealthy site metrics
4. query incident and deployment records
5. produce JSON or CSV reports
6. generate Grafana-ready metric output
7. summarise customer impact
8. provide recommended next checks
9. run tests to prove key behaviour still works
10. run inside Docker

## Suggested Project Structure

```text
projects/sre-operations-toolkit/
├── README.md
├── src/
│   └── sre_toolkit/
│       ├── __init__.py
│       ├── cli.py
│       ├── data_loader.py
│       ├── validators.py
│       ├── reports.py
│       ├── metrics.py
│       └── database.py
├── tests/
│   ├── test_validators.py
│   ├── test_reports.py
│   └── test_metrics.py
├── data/
│   ├── customers.csv
│   ├── sites.csv
│   ├── robots.csv
│   ├── deployments.csv
│   ├── incidents.csv
│   └── scan_runs.json
├── output/
│   ├── deployment-health-report.json
│   ├── customer-summary.md
│   └── grafana-metrics.json
├── Dockerfile
├── requirements.txt
└── runbook.md
```

## Part 1 — Capstone Build

Part 1 should focus on building the SRE Operations Toolkit.

Minimum requirements:

* load synthetic warehouse/deployment data
* validate required files and fields
* run at least one SQL-backed report
* detect failed or unhealthy deployment signals
* generate a customer-facing summary
* generate monitoring or Grafana-ready output
* include a runbook explaining how to use the tool

## Part 2 — Cumulative Repetition

Part 2 should deliberately reuse all major topics from the earlier track.

It should revisit:

* Python basics
* flow control
* functions
* lists
* dictionaries
* strings
* regex
* input validation
* file handling
* folder organisation
* debugging
* web/API-style data
* CSV and JSON
* scheduling concepts
* email/message drafting concepts
* safe automation principles
* SQL
* Docker
* Grafana/monitoring concepts
* AI safety and verification notes where relevant
* customer-facing technical communication

## Testing Requirements

The capstone must be tested.

Minimum testing evidence:

* unit tests for validators
* unit tests for report generation
* unit tests for metric output
* at least one regression test for a previously fixed issue
* bad-input tests
* expected vs actual output examples
* documented test command
* note on what remains untested

## Docker Requirements

The capstone should run inside Docker.

Evidence should include:

* Dockerfile
* image build command
* container run command
* example mounted input/output folder if relevant
* container log or command output
* note explaining why Docker helps deployment consistency

## Monitoring Requirements

The capstone should produce monitoring-style output.

Acceptable outputs include:

* JSON metrics
* CSV metrics
* SQLite metrics table
* Grafana dashboard design notes
* example panel list

The capstone does not need to connect to a real production Grafana instance, but it should produce outputs that are clearly suitable for dashboarding.

## Customer-Facing Output

The capstone should include a short customer-facing summary.

It should explain:

* current deployment health
* customer impact
* failed checks or risks
* recommended next action
* whether escalation is needed

The summary should be clear, factual, and safe to share in a customer-adjacent context.

## SRE Relevance

This lab should show SRE-relevant thinking:

* reliability
* observability
* incident investigation
* deployment validation
* repeatability
* automated checks
* runbooks
* production risk
* safe failure handling
* evidence-driven troubleshooting

## Completion Standard

Lab 30 is complete only when:

* the toolkit runs locally
* tests pass
* sample data is included
* output files are generated
* Docker usage is documented
* monitoring output exists
* customer-facing summary exists
* runbook exists
* final reflection questions are answered
* final documentation is uploaded

## Portfolio Story

The capstone should support this interview statement:

> I built an SRE operations toolkit in Python that validates deployment evidence, processes warehouse-style operational data, runs SQL-backed reports, generates monitoring-ready metrics, produces customer-facing summaries, runs tests, and can be executed in Docker.
