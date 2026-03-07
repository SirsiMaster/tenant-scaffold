# ADR-001: Tenant Initialization

**Status:** Accepted
**Date:** {{PROVISIONED_DATE}}
**Provisioned by:** Sirsi Provisioning Engine (ADR-030)

## Context

{{TENANT_NAME}} was provisioned as a {{PLAN_TIER}} tenant on the Sirsi Technologies platform.

## Decision

- **Plan**: {{PLAN_TIER}}
- **Cloud Provider**: {{CLOUD_PROVIDER}}
- **Region**: {{REGION}}
- **Owner UID**: {{OWNER_UID}}
- **Slug**: {{TENANT_SLUG}}

## Consequences

- Tenant inherits Sirsi UCS, CI/CD pipelines, and operational rules
- Superadmin attachment is immutable (Cylton + Hypervisor)
- Design language defaults to Swiss Neo-Deco (customizable via tenant tokens)
