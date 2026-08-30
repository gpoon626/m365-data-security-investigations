# Supporting Evidence

This folder contains screenshots and audit evidence supporting the Microsoft 365 data-security case studies. All activity was intentionally generated in an authorized test environment.

## Evidence Categories

### External Sharing and Access Governance

| Evidence                                                             | Demonstrates                                                 |
| -------------------------------------------------------------------- | ------------------------------------------------------------ |
| [External user edit access](external-user-edit-access.png)           | External recipient with edit permissions                     |
| [Sharing permission options](sharing-permission-options.png)         | Available edit, view, and download restrictions              |
| [Anonymous-link settings](anonymous-link-settings.png)               | Anyone-link scope, expiration, and password controls         |
| [Audit-search processing delay](audit-search-processing-delay.png)   | Purview search latency before events became available        |
| [External-sharing audit results](external-sharing-audit-results.png) | External-sharing events displayed in the results grid        |
| [External-sharing event details](external-sharing-event-details.png) | Guest recipient, resource, location, and permission details  |
| [External re-share event](external-reshare-event.png)                | Sharing invitation generated during the re-sharing test      |
| [Tenant sharing report query](tenant-sharing-report-query.png)       | Tenant-wide sharing search without an individual-user filter |


### File Activity Audit Investigation

| Evidence                                                                     | Demonstrates                                                |
| ---------------------------------------------------------------------------- | ----------------------------------------------------------- |
| [File-access audit query](file-access-audit-query.png)                       | Search scope for accessed-file and viewed-page activity     |
| [File-access audit results](file-access-audit-results.png)                   | File and page activity returned by Microsoft Purview        |
| [File-access event details](file-access-event-details.png)                   | Timestamp, IP, actor, item, and application context         |
| [Recycled-file initial zero results](recycled-file-initial-zero-results.png) | Completed search before the expected event became available |
| [Recycled-file delayed result](recycled-file-delayed-result.png)             | Repeated search returning the expected event                |
| [Recycled-file audit event](recycled-file-audit-event.png)                   | Recorded recycle action for the test document               |


### Insider Risk Investigation

Evidence will cover:

- Clustered file-download events
- Initial zero-result audit search
- External sharing of the payroll-themed test file
- Sharing-invitation and secure-link events

## Index Status

The External Sharing and Access Governance and File Activity Audit Investigation indexes are complete. Insider Risk Investigation filenames will be added after its evidence is reviewed and uploaded.
