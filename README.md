# Microsoft 365 Data Security Investigations

A collection of hands-on Microsoft 365 data-security exercises performed in an authorized lab environment. This project demonstrates external-sharing governance, SharePoint permission review, Microsoft Purview audit-log analysis, file-activity reconstruction, and insider-risk investigation.

## Project Objectives

- Review SharePoint and OneDrive external access.
- Apply least privilege to collaboration permissions.
- Trace external sharing through Microsoft Purview Audit.
- Reconstruct file access, downloads, and deletion activity.
- Investigate clustered downloads and external data sharing.
- Correlate related audit operations into activity timelines.
- Document audit-log delays and evidence limitations.
- Develop evidence-based investigation and containment decisions.

## Case Studies

| Case Study | Topics | Status |
|---|---|---|
| [External Sharing and Access Governance](case-studies/01-external-sharing-and-access-governance.md) | External sharing, permissions, re-sharing, compliance reporting | Draft |
| [File Activity Audit Investigation](case-studies/02-file-activity-audit-investigation.md) | File access, deletion events, timeline reconstruction | Draft |
| [Insider Risk Investigation](case-studies/03-insider-risk-investigation.md) | Bulk downloads, external sharing, data-exfiltration indicators | Draft |

## Technologies and Security Concepts

- Microsoft SharePoint Online
- Microsoft OneDrive
- Microsoft Purview Audit
- External-sharing controls
- SharePoint permission management
- Least privilege
- Audit-log investigation
- Evidence correlation
- Insider-risk analysis
- Security-event timeline reconstruction
- Data-exfiltration indicators
- Compliance reporting
- Incident triage

## Notable Findings

- An external recipient’s access was reduced from edit to view.
- External edit access permitted re-sharing in the tested configuration.
- Audit events were not always immediately available.
- Six generated downloads produced five matching audit results during the reviewed search.
- One sharing action could generate multiple related audit operations.
- The absence of an expected operation did not prove that the corresponding user action never occurred.

## Repository Structure

- `case-studies/` — Detailed documentation of the data-security investigations
- `evidence/` — Screenshots and audit evidence referenced by the case studies

## Lab Scope

All activities were intentionally generated in an authorized Microsoft 365 test environment using organizational and external test accounts.

The evidence may display test-account names, lab tenant information, IP addresses, file names, external test recipients, and audit telemetry captured during the exercises. The repository does not contain passwords, authentication tokens, private keys, customer data, or genuine payroll information.

## Current Status

This repository contains working drafts of three case studies. Supporting screenshots and audit evidence will be added as the project continues.

The content remains in Draft status so it can be revised before final publication.
