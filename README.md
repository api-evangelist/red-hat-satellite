# Red Hat Satellite (red-hat-satellite)
Red Hat Satellite is a systems management product that helps deploy, configure, and maintain systems across physical, virtual, and cloud environments.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/red-hat-satellite/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Configuration Management, Lifecycle Management, Patch Management, Subscription Management, Systems Management

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Red Hat Satellite REST API
The main REST API for Red Hat Satellite 6.x, providing programmatic access to all Satellite functions including host management, content management, provisioning, and configuration.

**Human URL:** [https://access.redhat.com/documentation/en-us/red_hat_satellite/](https://access.redhat.com/documentation/en-us/red_hat_satellite/)

#### Tags:

 - Automation, REST API, Systems Management

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/using_the_satellite_rest_api/index)
- [OpenAPI](https://satellite.example.com/apidoc/v2.json)
- [OpenAPI](openapi/red-hat-satellite-api.yml)
- [Authentication](https://access.redhat.com/documentation/en-us/red_hat_satellite/6.14/html/api_guide/chap-api_guide-authentication)
- [GettingStarted](https://docs.redhat.com/en/documentation/red_hat_satellite/6.18/html/using_the_satellite_rest_api/introduction-to-satellite-api)
- [APIReference](https://docs.redhat.com/en/documentation/red_hat_satellite/6.18/html/using_the_satellite_rest_api/index)

### Red Hat Satellite Hammer CLI
Command-line interface tool for Red Hat Satellite that provides scriptable access to Satellite functions including host management, content views, and provisioning.

**Human URL:** [https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/using_the_hammer_cli_tool/index](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/using_the_hammer_cli_tool/index)

#### Tags:

 - Automation, CLI, Command Line

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/using_the_hammer_cli_tool/index)
- [CodeExamples](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html/using_the_hammer_cli_tool/hammer-cheat-sheet)
- [Authentication](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html/using_the_hammer_cli_tool/hammer-authentication)

### Red Hat Satellite Foreman API
Core Foreman API integrated into Red Hat Satellite for host lifecycle management, provisioning, and configuration management.

**Human URL:** [https://theforeman.org/api.html](https://theforeman.org/api.html)

#### Tags:

 - Foreman, Host Management, Provisioning, REST API

#### Properties

- [Documentation](https://apidocs.theforeman.org/)
- [APIReference](https://apidocs.theforeman.org/foreman/latest/apidoc/v2.html)
- [GitHubOrganization](https://github.com/theforeman)
- [GitHubRepository](https://github.com/theforeman/foreman)

### Red Hat Satellite Katello API
Content management API for Red Hat Satellite handling repositories, content views, lifecycle environments, subscriptions, and errata.

**Human URL:** [https://theforeman.org/plugins/katello/](https://theforeman.org/plugins/katello/)

#### Tags:

 - Content Management, Lifecycle Environments, Repositories, REST API, Subscriptions

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/using_the_satellite_rest_api/index)
- [APIReference](https://apidocs.theforeman.org/katello/latest/apidoc/v2.html)
- [GitHubRepository](https://github.com/Katello/katello)
- [GitHubOrganization](https://github.com/Katello)

### Red Hat Satellite Ansible Collection
The redhat.satellite Ansible collection provides modules, roles, and plugins for automating Red Hat Satellite configuration and management through the Satellite API.

**Human URL:** [https://catalog.redhat.com/en/software/collection/redhat/satellite](https://catalog.redhat.com/en/software/collection/redhat/satellite)

#### Tags:

 - Ansible, Automation, Configuration Management, Infrastructure as Code

#### Properties

- [Documentation](https://redhatsatellite.github.io/satellite-ansible-collection/develop/README.html)
- [GitHubRepository](https://github.com/RedHatSatellite/satellite-ansible-collection)
- [Marketplace](https://catalog.redhat.com/en/software/collection/redhat/satellite)
- [Blog](https://www.redhat.com/en/blog/automating-red-hat-satellite-with-ansible)

## Common Properties

- [Portal](https://access.redhat.com/)
- [Documentation](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16)
- [Support](https://access.redhat.com/support/)
- [StatusPage](https://status.redhat.com/)
- [Blog](https://www.redhat.com/en/blog/channel/red-hat-satellite)
- [GitHubOrganization](https://github.com/theforeman)
- [KnowledgeCenter](https://access.redhat.com/solutions/)
- [ReleaseNotes](https://docs.redhat.com/en/documentation/red_hat_satellite/6.18/html-single/release_notes/index)
- [APIReference](https://apidocs.theforeman.org/)
- [CLI - Hammer CLI](https://github.com/theforeman/hammer-cli-foreman)

## Features

| Name | Description |
|------|-------------|
| Host Management | Manage physical, virtual, and cloud hosts across the entire lifecycle from provisioning to decommissioning. |
| Content Management | Curate and distribute RPM packages, errata, and container images through content views and lifecycle environments. |
| Patch Management | Apply security patches and errata across managed systems with controlled rollouts through lifecycle stages. |
| Subscription Management | Track and manage Red Hat subscriptions and entitlements across organizations and hosts. |
| Provisioning | Automate bare-metal and virtual machine provisioning with kickstart templates, PXE boot, and compute resources. |
| Configuration Management | Enforce desired-state configuration using Puppet classes and Ansible roles across managed hosts. |
| Multi-Tenancy | Organize hosts, content, and subscriptions into isolated organizations and locations. |

## Use Cases

| Name | Description |
|------|-------------|
| Automated Server Provisioning | Provision new servers automatically using compute resources, host groups, and kickstart templates. |
| Security Patching at Scale | Identify, test, and deploy security errata across thousands of hosts using content views and promotion workflows. |
| Hybrid Cloud Management | Manage hosts across on-premises data centers and cloud providers from a single console. |
| Compliance Reporting | Generate compliance reports using OpenSCAP integration to verify hosts meet security baselines. |
| Air-Gapped Environment Management | Manage systems in disconnected environments using content synchronization and inter-satellite sync. |

## Integrations

| Name | Description |
|------|-------------|
| Ansible | Automate Satellite operations and host configuration using the redhat.satellite Ansible collection. |
| Red Hat Insights | Proactive risk analysis and remediation recommendations for managed hosts. |
| Puppet | Apply and enforce configuration management policies using Puppet modules and classes. |
| OpenSCAP | Security compliance scanning and reporting using SCAP content and policies. |
| VMware vSphere | Provision and manage virtual machines on VMware infrastructure as compute resources. |
| Red Hat OpenStack | Provision and manage instances on OpenStack as compute resources. |
| Amazon EC2 | Provision and manage cloud instances on AWS as compute resources. |
| Google GCE | Provision and manage cloud instances on Google Cloud as compute resources. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Red Hat Satellite API](openapi/red-hat-satellite-api.yml)

### JSON Schema

- [Host Schema](json-schema/red-hat-satellite-host-schema.json)
- [Host Create Schema](json-schema/red-hat-satellite-host-create-schema.json)
- [Host Update Schema](json-schema/red-hat-satellite-host-update-schema.json)
- [Host Interface Schema](json-schema/red-hat-satellite-host-interface-schema.json)
- [Host Interface Create Schema](json-schema/red-hat-satellite-host-interface-create-schema.json)
- [Content View Schema](json-schema/red-hat-satellite-content-view-schema.json)
- [Content View Create Schema](json-schema/red-hat-satellite-content-view-create-schema.json)
- [Content View Update Schema](json-schema/red-hat-satellite-content-view-update-schema.json)
- [Subscription Schema](json-schema/red-hat-satellite-subscription-schema.json)
- [Lifecycle Environment Schema](json-schema/red-hat-satellite-lifecycle-environment-schema.json)
- [Organization Schema](json-schema/red-hat-satellite-organization-schema.json)
- [Foreman Task Schema](json-schema/red-hat-satellite-foreman-task-schema.json)

### JSON-LD

- [Red Hat Satellite Context](json-ld/red-hat-satellite-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Red Hat Satellite REST API](capabilities/shared/satellite-api.yaml) -- 21 operations for systems lifecycle management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Systems Lifecycle Management](capabilities/systems-lifecycle-management.yaml) | Satellite REST API | 18 | System Administrator |

## Vocabulary

- [Red Hat Satellite Vocabulary](vocabulary/red-hat-satellite-vocabulary.yaml)

## Rules

- [Red Hat Satellite Spectral Rules](rules/red-hat-satellite-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
