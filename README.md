# Stellar Cyber

Stellar Cyber is an Open XDR platform that provides AI-driven security operations capabilities including threat detection, investigation, and response. The platform offers an OAS-compliant REST API at `/connect/api/v1/` that enables downstream applications to perform complex queries, automate security workflows, manage cases and alerts, administer multi-tenant environments, and build custom integrations across 500+ security tools.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/stellar-cyber/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Cybersecurity, Security, XDR, SIEM, SOAR, AI

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-02

## APIs

### Stellar Cyber Open XDR API

The Stellar Cyber REST API provides programmatic access to the Open XDR platform, enabling automation of security operations including case management, tenant administration, connector management, alert handling, query operations, user management, watchlists, sensors, and security event management. JWT-based authentication with tokens obtained from the `/access_token` endpoint.

**Human URL:** [https://docs.stellarcyber.ai/](https://docs.stellarcyber.ai/)

**Base URL:** `https://{platform-hostname}/connect/api/v1`

#### Tags

- Cybersecurity, Security, XDR, SIEM, SOAR, Threat Detection, Incident Response

#### Properties

- [Documentation](https://docs.stellarcyber.ai/)
- [Reference](https://docs.stellarcyber.ai/6.3.x/Using/API/API-Intro.htm)
- [OpenAPI](openapi/stellar-cyber-openapi.yml)

## OpenAPI Specs

- [stellar-cyber-openapi.yml](openapi/stellar-cyber-openapi.yml)

## Rules

- [stellar-cyber-rules.yml](rules/stellar-cyber-rules.yml) — Spectral ruleset enforcing Stellar Cyber API conventions

## Capabilities

### Workflow Capabilities

- [security-operations.yaml](capabilities/security-operations.yaml) — Unified SOC workflow for incident response, alert triage, case management, and playbook automation (13 tools)

### Shared Definitions

- [shared/stellar-cyber.yaml](capabilities/shared/stellar-cyber.yaml) — Stellar Cyber Open XDR API consumed definition

## JSON Schema

- [stellar-cyber-case-schema.json](json-schema/stellar-cyber-case-schema.json) — Schema for security case objects
- [stellar-cyber-alert-schema.json](json-schema/stellar-cyber-alert-schema.json) — Schema for security alert objects

## JSON Structure

- [stellar-cyber-case-structure.json](json-structure/stellar-cyber-case-structure.json) — Field structure documentation for cases

## JSON-LD

- [stellar-cyber-context.jsonld](json-ld/stellar-cyber-context.jsonld) — JSON-LD context mapping Stellar Cyber entities to schema.org

## Examples

- [stellar-cyber-list-cases-example.json](examples/stellar-cyber-list-cases-example.json) — List Cases API example
- [stellar-cyber-create-case-example.json](examples/stellar-cyber-create-case-example.json) — Create Case API example

## Vocabulary

- [stellar-cyber-vocabulary.yml](vocabulary/stellar-cyber-vocabulary.yml) — Domain vocabulary for Stellar Cyber Open XDR concepts

## Common Properties

- [Portal](https://stellarcyber.ai/)
- [Documentation](https://docs.stellarcyber.ai/)
- [Website](https://stellarcyber.ai/)
- [GitHub Organization](https://github.com/stellarcyber)
- [Support](https://stellarcyber.zendesk.com)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
