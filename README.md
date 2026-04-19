# 1Factory (1factory)
1Factory is a leading provider of quality management software solutions for manufacturing companies. The platform helps businesses streamline their operations, improve efficiency, and ensure product quality at every stage of the production process. Features include real-time monitoring, automated data collection, advanced analytics, and integration with ERP and PLM systems via a REST API.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/1factory/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Analytics, Data Collection, Manufacturing, Monitoring, Quality

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-04-19

## APIs

### 1Factory API
This API allows you to create and query a number of objects in your 1Factory account. The API accepts and returns request and response bodies as JSON, using UTF-8 encoding. Supports part master management, manufacturing and receiving inspections, supplier quality, first article inspections (FAI), and quality management system records (NCRs, CAPAs, complaints).

**Human URL:** [https://www.1factory.com/api-doc/index.html](https://www.1factory.com/api-doc/index.html)

#### Tags:

 - Manufacturing, Quality, Inspections

#### Properties

- [Documentation](https://www.1factory.com/api-doc/index.html)
- [OpenAPI](openapi/1factory-openapi.json)
- [JSONSchema](json-schema/1factory-part-master-schema.json)
- [JSONSchema](json-schema/1factory-inspection-schema.json)
- [JSONSchema](json-schema/1factory-plan-schema.json)
- [JSONSchema](json-schema/1factory-fai-schema.json)
- [JSONSchema](json-schema/1factory-capa-schema.json)
- [JSONSchema](json-schema/1factory-complaint-schema.json)

## Common Properties

- [Website](https://www.1factory.com/)
- [Documentation](https://www.1factory.com/api-doc/index.html)
- [Security](https://www.1factory.com/technical-overview.html)
- [Support](https://1factoryhelp.zendesk.com/hc/en-us)
- [TermsOfService](https://www.1factory.com/resources/TOS%20May%2020%202021.pdf)

## Features

| Name | Description |
|------|-------------|
| Manufacturing Quality Control | Factory floor quality control, inspection planning, and statistical process control (SPC) |
| Quality Management System (QMS) | Document control, training management, audits, and compliance workflows |
| Supplier Quality Management | Vendor oversight, incoming inspection management, and supplier corrective actions |
| First Article Inspection (FAI) | Automated drawing ballooning and AS9102-compliant first article inspection |
| Real-Time Analytics | Real-time quality analytics and audit-ready reporting dashboards |
| CMM Data Integration | Automatic import of CMM measurement data with SPC analysis |
| ERP/PLM Integration | API-based integration with ERP and PLM systems for part and work order sync |

## Use Cases

| Name | Description |
|------|-------------|
| Manufacturing Inspection | Create and track manufacturing inspections with measurement data and SPC analysis |
| Supplier Qualification | Manage supplier certifications, conduct receiving inspections, and track supplier CAPAs |
| Non-Conformance Management | Log, track, and resolve non-conformances, CAPAs, and customer complaints |
| First Article Inspection | Conduct and document AS9102 first article inspections for aerospace and defense |
| ERP Data Sync | Synchronize part master data, work orders, and inspection results with ERP systems |

## Integrations

| Name | Description |
|------|-------------|
| ERP Systems | Sync part master data, work orders, and inspection records with ERP platforms |
| PLM Systems | Connect with PLM systems for design-to-manufacturing quality continuity |
| CMM Equipment | Auto-import measurement data from CMM equipment directly into inspections |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [1Factory API](openapi/1factory-openapi.json)

### JSON Schema

- 62 schema files covering part masters, inspections, plans, FAI, NCRs, CAPAs, complaints, suppliers, and more

### JSON Structure

- 62 JSON Structure files (json-structure.org format)

### JSON-LD

- [1Factory Context](json-ld/1factory-context.jsonld)

### Examples

- 62 example JSON files for all schemas

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [1Factory API](capabilities/shared/1factory.yaml) — 38 operations for quality management, inspections, and QMS

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [1Factory Quality Management](capabilities/1factory-quality-management.yaml) | 1Factory API | 10 | Quality Engineer, Production Manager, Supplier Quality Manager |

## Vocabulary

- [1Factory Vocabulary](vocabulary/1factory-vocabulary.yaml) — Unified taxonomy mapping 11 resources, 4 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [1Factory Spectral Rules](rules/1factory-spectral-rules.yml) — 30 rules across 13 categories enforcing 1Factory API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
