# Hospitality Management Application — Complete Project Guide

**Repository:** `vaishnavsawant1994-stack/hospanlity-new` · **Review:** 15 November 2026  
**Evidence level:** current README, repository layout and manifest where available; no fresh deployed-end-to-end certification.

## Product identity and problem
Full-stack hospitality operations system with a React frontend, Express backend, MySQL data, dashboards, reporting and administration.

**Primary users:** Hospitality operators and maintainers.

## Functional areas and intended user journeys
1. Hotel/hospitality navigation and management UI.
2. Backend APIs, JWT-based authentication and MySQL connectivity.
3. Charts, reports, spreadsheet exports and notifications.
4. Project management workbook and planning material.

Features above describe documented capability areas, source/UI surfaces or product intents. A listed module is not necessarily a functioning integrated feature.

## System design and codebase
`frontend/`, `backend/`, `package.json`, `PROJECT_MANAGEMENT_SHEETS.md` and workbooks. React/Vite, Express 5, MySQL, bcrypt and JWT are documented; root package is an aggregation layer, not a complete run guide.

## Implementation status
Application source is present. Exact operational workflows, valid business data, security hardening and deployment evidence are not established by this documentation pass.

**Do not conflate:** planned scope, code existence, passing old CI, live production deployment and independent release acceptance. They require separate evidence.

## Development and testing
Inspect `frontend/package.json` and `backend/package.json` for their own install/start scripts, supply a disposable MySQL database and environment configuration, and test authenticated API calls in isolation.

Before using any environment: examine .env examples and source code, use test accounts, protect secrets, and inspect the target database prior to migrations/seed commands.

## Data security, privacy and operations
- Never use default JWT secrets or real guest records in demos.
- Separate staff roles and property/tenant scopes.
- Reconcile booking/financial updates and preserve audit trails.
Additionally validate backup/restore, audit logs, staging isolation, access reviews, monitoring and release rollback before production use.

## Priority development plan
1. Document canonical hospitality brand and correct repository spelling when approved.
2. Map screens to API/data operations.
3. Add migration/restore and integration-test evidence.
4. Decide if `hospitality` placeholder should remain separate.

## Where to read more
- [`README.md`](../README.md)
- [`PROJECT_MANAGEMENT_SHEETS.md`](../PROJECT_MANAGEMENT_SHEETS.md)
- [`frontend/`](../frontend/)
- [`backend/`](../backend/)

This guide should be revised after verified code, architecture, data schema, deployment or product-scope changes. The underlying source and gated engineering documents remain authoritative.
