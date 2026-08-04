# VNC (vnc)

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

RealVNC provides the VNC Connect remote desktop platform and VNC Developer SDK, enabling organizations to embed secure remote access into products and automate device management. The VNC Cloud REST API manages cloud address allocation and connectivity brokering, while the VNC Developer SDK (C, Java, Python, .NET, JavaScript) enables embedding Viewer and Server capabilities into applications.

**APIs.json:** [https://www.realvnc.com/en/developer/](https://www.realvnc.com/en/developer/)

## Scope

- **Type:** Index

## Tags

- Remote Desktop
- Remote Access
- VNC
- Networking
- Screen Sharing

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-19

## APIs

### VNC Cloud API

The VNC Cloud REST API manages cloud addresses that allow devices to join VNC Cloud and establish remote connections through RealVNC's managed broker service. Supports creating, listing, updating, resetting, and deleting cloud addresses with access control via groups and allowlisted peer cloud addresses.

- **Human URL:** [https://www.realvnc.com/en/developer/docs/latest/api/cloud/](https://www.realvnc.com/en/developer/docs/latest/api/cloud/)
- **Base URL:** `https://api.vnc.com/cloud/1.1`

#### Tags

- Cloud
- Remote Access
- VNC

#### Properties

- [Documentation](https://www.realvnc.com/en/developer/docs/latest/api/cloud/)
- [OpenAPI](openapi/vnc-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vnc-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vnc-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/vnc-cloud-address-schema.json) — [JSON Schema](https://json-schema.org/specification)

### VNC Connect Management API

The VNC Connect API Access feature enables programmatic management of devices registered to a team account, supporting device inventory, renaming, deduplication, and integration with ITSM tools. Authenticated with team-scoped API access keys with granular permission control.

- **Human URL:** [https://www.realvnc.com/en/connect/api-access/](https://www.realvnc.com/en/connect/api-access/)

#### Tags

- Device Management
- Automation
- VNC Connect

#### Properties

- [Documentation](https://www.realvnc.com/en/connect/api-access/)
- [Postman Collection](collections/vnc-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vnc-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VNC Developer SDK

Cross-platform SDK for embedding VNC Viewer and Server functionality into applications. Available for C, Java, Python, .NET, and JavaScript. Supports direct TCP/UDP connections, VNC Cloud brokering, end-to-end AES-128 encryption, custom messaging, multi-display, clipboard sharing, and screen annotations.

- **Human URL:** [https://www.realvnc.com/en/developer/docs/latest/overview.html](https://www.realvnc.com/en/developer/docs/latest/overview.html)

#### Tags

- SDK
- Embedded
- Remote Desktop
- Developer Tools

#### Properties

- [Documentation](https://www.realvnc.com/en/developer/docs/latest/overview.html)
- [Reference](https://www.realvnc.com/en/developer/docs/latest/api/)
- [Postman Collection](collections/vnc-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vnc-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/realvnc)
- [Website](https://www.realvnc.com/en/developer/)
- [Documentation](https://www.realvnc.com/en/developer/docs/latest/)
- [OpenAPI](openapi/vnc-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/vnc-cloud-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/vnc-cloud-address-structure.json)
- [JSON-LD](json-ld/vnc-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/vnc-vocabulary.yml)
- [Spectral Rules](rules/vnc-rules.yml)
- [Getting Started](https://www.realvnc.com/en/developer/docs/latest/overview.html)
- [GitHub Organization](https://github.com/realvnc)
- [GitHub Organization](https://github.com/realvnc-labs)
- [Pricing](https://www.realvnc.com/en/connect/pricing/)
- [Support](https://help.realvnc.com/)
- [Terms of Service](https://www.realvnc.com/en/legal/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
