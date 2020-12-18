Find a Public Cloud resource by Public IP using Prisma Cloud inventory
Supported Cortex XSOAR versions: 6.0.0 and later.


## Dependencies
This playbook uses the following sub-playbooks, integrations, and scripts.

### Sub-playbooks
* Prisma Cloud - Find Azure Resource by Public IP
* Prisma Cloud - Find AWS Resource by Public IP
* Prisma Cloud - Find GCP Resource by Public IP

### Integrations
This playbook does not use any integrations.

### Scripts
This playbook does not use any scripts.

### Commands
This playbook does not use any commands.

## Playbook Inputs
---

| **Name** | **Description** | **Default Value** | **Required** |
| --- | --- | --- | --- |
| PublicIPAddress | Public IP Address to look up |  | Required |
| CloudProvider | Public Cloud Provider \(AWS, Azure, GCP\) |  | Optional |

## Playbook Outputs
---

| **Path** | **Description** | **Type** |
| --- | --- | --- |
| PrismaCloud.Attribution | Prisma Cloud attributed asset information. | unknown |

## Playbook Image
---
![Prisma Cloud - Find Public Cloud Resource by Public IP](https://raw.githubusercontent.com/demisto/content/8d80d2e630f4a6aafd1fb1a27102d14565d429b1/Packs/PrismaCloud/Playbooks/playbook-Prisma_Cloud_-_Find_Public_Cloud_Resource_by_Public_IP.png)