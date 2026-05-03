# SonarQube

SonarQube is a leading code quality and security platform that provides Web APIs for managing projects, quality gates, issues, and integrations with CI/CD pipelines to deliver clean, secure code.

**URL:** [https://raw.githubusercontent.com/api-evangelist/sonarqube/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sonarqube/refs/heads/main/apis.yml)

## Tags

Code Quality, DevOps, Security, Static Analysis

## APIs

### SonarQube Web API

HTTP API for programmatic interaction with SonarQube Server — project management, quality gates, issues, rules, users, and CI/CD integration.

- **Documentation:** [https://docs.sonarsource.com/sonarqube-server/latest/extension-guide/web-api/](https://docs.sonarsource.com/sonarqube-server/latest/extension-guide/web-api/)
- **Reference:** [https://api-docs.sonarsource.com/](https://api-docs.sonarsource.com/)
- **OpenAPI:** [openapi/sonarqube-web-api-openapi.yml](openapi/sonarqube-web-api-openapi.yml)

**Operations:**
- `GET /projects/search` — Search Projects
- `POST /projects/create` — Create Project
- `POST /projects/delete` — Delete Project
- `GET /issues/search` — Search Issues
- `GET /qualitygates/list` — List Quality Gates
- `GET /qualitygates/project_status` — Get Quality Gate Status
- `GET /measures/component` — Get Component Measures
- `GET /rules/search` — Search Rules
- `GET /users/search` — Search Users
- `GET /system/status` — Get System Status
- `GET /system/health` — Get System Health

## Artifacts

### OpenAPI

- [openapi/sonarqube-web-api-openapi.yml](openapi/sonarqube-web-api-openapi.yml) — SonarQube Web API specification

### JSON Schemas

- [json-schema/sonarqube-issue-schema.json](json-schema/sonarqube-issue-schema.json) — Code issue (bug, vulnerability, code smell)
- [json-schema/sonarqube-project-schema.json](json-schema/sonarqube-project-schema.json) — SonarQube project
- [json-schema/sonarqube-quality-gate-schema.json](json-schema/sonarqube-quality-gate-schema.json) — Quality gate definition

### JSON Structure

- [json-structure/sonarqube-web-api-structure.json](json-structure/sonarqube-web-api-structure.json) — Web API data entity structures

### JSON-LD

- [json-ld/sonarqube-context.jsonld](json-ld/sonarqube-context.jsonld) — Linked data context

### Spectral Rules

- [rules/sonarqube-rules.yml](rules/sonarqube-rules.yml) — API governance rules for SonarQube's Web API conventions

### Naftiko Capabilities

| Capability | Description |
|---|---|
| [capabilities/code-quality-governance.yaml](capabilities/code-quality-governance.yaml) | Unified code quality governance workflow (10 tools) |
| [capabilities/shared/sonarqube-web-api.yaml](capabilities/shared/sonarqube-web-api.yaml) | Shared: SonarQube Web API (9 tools) |

### Examples

- [examples/sonarqube-search-issues-example.json](examples/sonarqube-search-issues-example.json) — Search issues response with bugs and vulnerabilities
- [examples/sonarqube-quality-gate-status-example.json](examples/sonarqube-quality-gate-status-example.json) — Quality gate status with failing coverage condition
- [examples/sonarqube-component-measures-example.json](examples/sonarqube-component-measures-example.json) — Project metrics (coverage, bugs, vulnerabilities)

### Vocabulary

- [vocabulary/sonarqube-vocabulary.yml](vocabulary/sonarqube-vocabulary.yml) — SonarQube domain vocabulary (static analysis, issues, quality gates)

## Common Properties

- [Website](https://www.sonarsource.com/)
- [Product](https://www.sonarsource.com/products/sonarqube/)
- [Documentation](https://docs.sonarsource.com/sonarqube-server/)
- [API Reference](https://api-docs.sonarsource.com/)
- [GitHub Organization](https://github.com/SonarSource)
- [Community](https://community.sonarsource.com/)
- [Blog](https://www.sonarsource.com/blog/)
- [Status](https://status.sonarsource.com/)
- [Pricing](https://www.sonarsource.com/plans-and-pricing/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
