# Lab 30 Break/Fix Requirements

## Purpose

Lab 30 is the SRE capstone, so break/fix work is mandatory.

The capstone should not only demonstrate a working operations toolkit. It should also demonstrate controlled failure, investigation, repair, and verification.

## Required Fault Scenarios

Lab 30 should include several deliberate safe faults.

Minimum required scenarios:

| Scenario | Fault type | Expected investigation |
| --- | --- | --- |
| Missing deployment evidence | Required input file is absent | file validation, clear error message, recovery instructions |
| Malformed operational data | CSV or JSON has missing/invalid fields | schema validation, bad record reporting |
| Failed scan run | synthetic robot scan has failed status or abnormal duration | metrics review, customer impact note |
| Broken SQL report | query initially returns wrong or incomplete result | query debugging, expected vs actual comparison |
| Failed test | regression test catches an incorrect behaviour | test failure, code fix, passing test |
| Docker issue | container build or run fails due to a controlled mistake | inspect logs, fix Dockerfile or command |
| Monitoring anomaly | synthetic metrics show unhealthy deployment state | dashboard/metric interpretation and recommended next check |

## Required Evidence

For each selected break/fix scenario, capture:

* what was broken
* command or test used to reveal it
* error message, failed output, or log evidence
* suspected cause
* fix applied
* verification after the fix
* prevention or hardening note

## Minimum Capstone Standard

Lab 30 should include at least:

* three deliberate break/fix scenarios
* one failed test that later passes
* one bad data example that is rejected safely
* one Docker or environment-related failure
* one monitoring or metric anomaly
* one customer-facing explanation of the issue and fix

## SRE Value

This is the most important part of the capstone because SRE and Forward Deployed Engineering work is often about handling systems that do not behave as expected.

The capstone should show:

* calm troubleshooting
* clear evidence gathering
* safe repair
* verification after the fix
* documentation of what happened
* prevention of recurrence

## Completion Rule

The Lab 30 capstone is not complete until the break/fix section is documented.
