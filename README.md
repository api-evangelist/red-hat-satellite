# Red Hat Satellite (red-hat-satellite)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Red Hat Satellite is a systems management product that helps deploy, configure, and maintain systems across physical, virtual, and cloud environments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/red-hat-satellite/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/red-hat-satellite/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Configuration Management
- Lifecycle Management
- Patch Management
- Subscription Management
- Systems Management

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Red Hat Satellite REST API

The main REST API for Red Hat Satellite 6.x, providing programmatic access to all Satellite functions including host management, content management, provisioning, and configuration.

- **Human URL:** [https://access.redhat.com/documentation/en-us/red_hat_satellite/](https://access.redhat.com/documentation/en-us/red_hat_satellite/)
- **Base URL:** `https://satellite.example.com/api/v2`

#### Tags

- Automation
- REST API
- Systems Management

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/using_the_satellite_rest_api/index)
- [OpenAPI](https://satellite.example.com/apidoc/v2.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/red-hat-satellite-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/red-hat-satellite-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-satellite-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/red-hat-satellite-host-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/red-hat-satellite-host-create-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/red-hat-satellite-host-update-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/red-hat-satellite-host-interface-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/red-hat-satellite-host-interface-create-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/red-hat-satellite-content-view-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/red-hat-satellite-content-view-create-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/red-hat-satellite-content-view-update-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/red-hat-satellite-subscription-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/red-hat-satellite-lifecycle-environment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/red-hat-satellite-organization-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/red-hat-satellite-foreman-task-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/red-hat-satellite-host-structure.json)
- [JSON Structure](json-structure/red-hat-satellite-host-create-structure.json)
- [JSON Structure](json-structure/red-hat-satellite-host-update-structure.json)
- [JSON Structure](json-structure/red-hat-satellite-host-interface-structure.json)
- [JSON Structure](json-structure/red-hat-satellite-host-interface-create-structure.json)
- [JSON Structure](json-structure/red-hat-satellite-content-view-structure.json)
- [JSON Structure](json-structure/red-hat-satellite-content-view-create-structure.json)
- [JSON Structure](json-structure/red-hat-satellite-content-view-update-structure.json)
- [JSON Structure](json-structure/red-hat-satellite-subscription-structure.json)
- [JSON Structure](json-structure/red-hat-satellite-lifecycle-environment-structure.json)
- [JSON Structure](json-structure/red-hat-satellite-organization-structure.json)
- [JSON Structure](json-structure/red-hat-satellite-foreman-task-structure.json)
- [Example](examples/red-hat-satellite-host-example.json)
- [Example](examples/red-hat-satellite-host-create-example.json)
- [Example](examples/red-hat-satellite-host-update-example.json)
- [Example](examples/red-hat-satellite-host-interface-example.json)
- [Example](examples/red-hat-satellite-host-interface-create-example.json)
- [Example](examples/red-hat-satellite-content-view-example.json)
- [Example](examples/red-hat-satellite-content-view-create-example.json)
- [Example](examples/red-hat-satellite-content-view-update-example.json)
- [Example](examples/red-hat-satellite-subscription-example.json)
- [Example](examples/red-hat-satellite-lifecycle-environment-example.json)
- [Example](examples/red-hat-satellite-organization-example.json)
- [Example](examples/red-hat-satellite-foreman-task-example.json)
- [JSON-LD](json-ld/red-hat-satellite-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://access.redhat.com/documentation/en-us/red_hat_satellite/6.14/html/api_guide/chap-api_guide-authentication)
- [Getting Started](https://docs.redhat.com/en/documentation/red_hat_satellite/6.18/html/using_the_satellite_rest_api/introduction-to-satellite-api)
- [API Reference](https://docs.redhat.com/en/documentation/red_hat_satellite/6.18/html/using_the_satellite_rest_api/index)

### Red Hat Satellite Hammer CLI

Command-line interface tool for Red Hat Satellite that provides scriptable access to Satellite functions including host management, content views, and provisioning.

- **Human URL:** [https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/using_the_hammer_cli_tool/index](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/using_the_hammer_cli_tool/index)

#### Tags

- Automation
- CLI
- Command Line

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/using_the_hammer_cli_tool/index)
- [Code Examples](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html/using_the_hammer_cli_tool/hammer-cheat-sheet)
- [Authentication](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html/using_the_hammer_cli_tool/hammer-authentication)
- [Postman Collection](collections/red-hat-satellite-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-satellite-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat Satellite Foreman API

Core Foreman API integrated into Red Hat Satellite for host lifecycle management, provisioning, and configuration management. This is the upstream project API that powers Satellite's core functionality including the web UI, users, organizations, and security.

- **Human URL:** [https://theforeman.org/api.html](https://theforeman.org/api.html)
- **Base URL:** `https://satellite.example.com/api`

#### Tags

- Foreman
- Host Management
- Provisioning
- REST API

#### Properties

- [Documentation](https://apidocs.theforeman.org/)
- [API Reference](https://apidocs.theforeman.org/foreman/latest/apidoc/v2.html)
- [GitHub Organization](https://github.com/theforeman)
- [GitHub Repository](https://github.com/theforeman/foreman)
- [GitHub Repository](https://github.com/theforeman/apidocs)
- [Postman Collection](collections/red-hat-satellite-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-satellite-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat Satellite Katello API

Content management API for Red Hat Satellite handling repositories, content views, lifecycle environments, subscriptions, and errata. Katello is the upstream plugin that provides Satellite's content and subscription management capabilities.

- **Human URL:** [https://theforeman.org/plugins/katello/](https://theforeman.org/plugins/katello/)
- **Base URL:** `https://satellite.example.com/katello/api`

#### Tags

- Content Management
- Lifecycle Environments
- Repositories
- REST API
- Subscriptions

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/using_the_satellite_rest_api/index)
- [API Reference](https://apidocs.theforeman.org/katello/latest/apidoc/v2.html)
- [Documentation](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/managing_content/index)
- [GitHub Repository](https://github.com/Katello/katello)
- [GitHub Organization](https://github.com/Katello)
- [Postman Collection](collections/red-hat-satellite-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-satellite-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat Satellite Ansible Collection

The redhat.satellite Ansible collection provides modules, roles, and plugins for automating Red Hat Satellite configuration and management through the Satellite API. Based on the theforeman.foreman community collection.

- **Human URL:** [https://catalog.redhat.com/en/software/collection/redhat/satellite](https://catalog.redhat.com/en/software/collection/redhat/satellite)

#### Tags

- Ansible
- Automation
- Configuration Management
- Infrastructure as Code

#### Properties

- [Documentation](https://redhatsatellite.github.io/satellite-ansible-collection/develop/README.html)
- [GitHub Repository](https://github.com/RedHatSatellite/satellite-ansible-collection)
- [Marketplace](https://catalog.redhat.com/en/software/collection/redhat/satellite)
- [GitHub Repository](https://github.com/theforeman/foreman-ansible-modules)
- [Blog](https://www.redhat.com/en/blog/automating-red-hat-satellite-with-ansible)
- [Postman Collection](collections/red-hat-satellite-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-satellite-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://access.redhat.com/)
- [Documentation](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16)
- [Support](https://access.redhat.com/support/)
- [Status Page](https://status.redhat.com/)
- [Blog](https://www.redhat.com/en/blog/channel/red-hat-satellite)
- [GitHub Organization](https://github.com/theforeman)
- [Knowledge Center](https://access.redhat.com/solutions/)
- [Support](https://access.redhat.com/community/)
- [Support](https://community.theforeman.org/)
- [Release Notes](https://docs.redhat.com/en/documentation/red_hat_satellite/6.18/html-single/release_notes/index)
- [Documentation](https://access.redhat.com/support/policy/updates/satellite)
- [Documentation](https://access.redhat.com/articles/1365633)
- [Documentation](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html/provisioning_hosts/index)
- [Documentation](https://docs.redhat.com/en/documentation/red_hat_satellite/6.16/html-single/managing_content/index)
- [API Reference](https://apidocs.theforeman.org/)
- [C L I](https://github.com/theforeman/hammer-cli-foreman)
- [GitHub Repository](https://github.com/theforeman/foreman-ansible-modules)
- [Spectral Rules](rules/red-hat-satellite-spectral-rules.yml)
- [Vocabulary](vocabulary/red-hat-satellite-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
