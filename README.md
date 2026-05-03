# VNC

RealVNC provides the VNC Connect remote desktop platform and VNC Developer SDK, enabling organizations to embed secure remote access into products and automate device management. The VNC Cloud REST API manages cloud address allocation and connectivity brokering, while the VNC Developer SDK (C, Java, Python, .NET, JavaScript) enables embedding Viewer and Server capabilities into applications.

- **Website:** [https://www.realvnc.com/en/developer/](https://www.realvnc.com/en/developer/)
- **Documentation:** [https://www.realvnc.com/en/developer/docs/latest/](https://www.realvnc.com/en/developer/docs/latest/)
- **GitHub (RealVNC):** [https://github.com/realvnc](https://github.com/realvnc)
- **GitHub (RealVNC Labs):** [https://github.com/realvnc-labs](https://github.com/realvnc-labs)

## APIs

### VNC Cloud API

The VNC Cloud REST API manages cloud addresses that allow devices to join VNC Cloud and establish remote connections through RealVNC's managed broker service.

- **Base URL:** `https://api.vnc.com/cloud/1.1`
- **Authentication:** HTTP Basic (API Key + Secret)
- **Documentation:** [https://www.realvnc.com/en/developer/docs/latest/api/cloud/](https://www.realvnc.com/en/developer/docs/latest/api/cloud/)
- **OpenAPI Spec:** [openapi/vnc-cloud-openapi.yml](openapi/vnc-cloud-openapi.yml)

### VNC Connect Management API

Programmatic management of devices registered to a VNC Connect team account.

- **Documentation:** [https://www.realvnc.com/en/connect/api-access/](https://www.realvnc.com/en/connect/api-access/)

### VNC Developer SDK

Cross-platform SDK for embedding VNC Viewer and Server into applications (C, Java, Python, .NET, JavaScript).

- **Documentation:** [https://www.realvnc.com/en/developer/docs/latest/overview.html](https://www.realvnc.com/en/developer/docs/latest/overview.html)
- **API Reference:** [https://www.realvnc.com/en/developer/docs/latest/api/](https://www.realvnc.com/en/developer/docs/latest/api/)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [openapi/vnc-cloud-openapi.yml](openapi/vnc-cloud-openapi.yml) | VNC Cloud REST API — cloud address management |

### JSON Schema

| Schema | Description |
|--------|-------------|
| [json-schema/vnc-cloud-address-schema.json](json-schema/vnc-cloud-address-schema.json) | VNC Cloud Address resource schema |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [json-structure/vnc-cloud-address-structure.json](json-structure/vnc-cloud-address-structure.json) | Cloud Address field-level documentation |

### JSON-LD Context

| Context | Description |
|---------|-------------|
| [json-ld/vnc-context.jsonld](json-ld/vnc-context.jsonld) | Linked data context for VNC resources |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [rules/vnc-rules.yml](rules/vnc-rules.yml) | API linting rules for VNC conventions |

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [capabilities/remote-access-management.yaml](capabilities/remote-access-management.yaml) | Unified remote access infrastructure management |
| [capabilities/shared/vnc-cloud.yaml](capabilities/shared/vnc-cloud.yaml) | Shared VNC Cloud API consumed definition |

### Examples

| Example | Description |
|---------|-------------|
| [examples/vnc-createCloudAddress-example.json](examples/vnc-createCloudAddress-example.json) | Create a cloud address |
| [examples/vnc-listCloudAddresses-example.json](examples/vnc-listCloudAddresses-example.json) | List cloud addresses |
| [examples/vnc-getCloudAddress-example.json](examples/vnc-getCloudAddress-example.json) | Get a cloud address |
| [examples/vnc-deleteCloudAddress-example.json](examples/vnc-deleteCloudAddress-example.json) | Delete a cloud address |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [vocabulary/vnc-vocabulary.yml](vocabulary/vnc-vocabulary.yml) | VNC domain vocabulary and terminology |

## Scope

- **Type:** Index
- **Tags:** Remote Desktop, Remote Access, VNC, Networking, Screen Sharing

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
