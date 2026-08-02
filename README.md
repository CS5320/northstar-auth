# Northstar Authentication Service

Provides authentication and authorization services across the Northstar platform.

## Responsibilities

- User authentication
- Session management
- Role-based authorization
- OAuth integrations

## Current Status

Stable

Several modernization efforts are currently being evaluated.

## Known Issues

- Legacy authentication endpoints still supported
- Authorization rules duplicated across services
- Technical debt surrounding permissions

Architecture decisions are documented in the Architecture repository.

## Upcoming Work

The Authentication Service remains stable but several architectural improvements have been identified.

### TODO

- [ ] Consolidate permission definitions
- [ ] Retire legacy authentication endpoints
- [ ] Review password reset workflow
- [ ] Evaluate role hierarchy for future products
---

## Maintainers

Engineering Management

- Emily Chen — Director of Engineering
- Marcus Alvarez — Principal Software Architect

For architecture questions, see the Architecture repository.

> **Note**
>
> This repository is actively maintained. Documentation may not always reflect the latest implementation. When conflicts arise, Architecture Decision Records (ADRs) are considered the authoritative source.
