Search alerts in Prisma Cloud for a specific asset ID and, if present in XSOAR, link them.
Supported Cortex XSOAR versions: 6.0.0 and later.


## Dependencies
This playbook uses the following sub-playbooks, integrations, and scripts.

### Sub-playbooks
This playbook does not use any sub-playbooks.

### Integrations
* RedLock

### Scripts
* SearchIncidentsV2
* ToTable

### Commands
* linkIncidents
* redlock-search-alerts

## Playbook Inputs
---

| **Name** | **Description** | **Default Value** | **Required** |
| --- | --- | --- | --- |
| Prisma Cloud Attribution | Attribution information from Prisma Cloud. | PrismaCloud.Attribution | Optional |
| Link Incidents | Link found Prisma Cloud incidents to current one? | True | Optional |

## Playbook Outputs
---

| **Path** | **Description** | **Type** |
| --- | --- | --- |
| foundIncidents | Found Prisma Cloud Incidents | unknown |
| Redlock.Alert | Prisma Cloud Alert | unknown |

## Playbook Image
---
![Prisma Cloud Correlate Alerts](https://raw.githubusercontent.com/demisto/content/8d80d2e630f4a6aafd1fb1a27102d14565d429b1/Packs/PrismaCloud/Playbooks/playbook-Prisma_Cloud_Correlate_Alerts.png)