# Hospitality Management Application

> Repository name note: `hospanlity-new` contains a spelling error. Confirm the final project name before renaming or consolidating repositories.

## Project overview

A full-stack hospitality-management application built with a React frontend, Express backend, and MySQL database.

## What it contains

- React 18 and Vite frontend
- Express 5 backend
- MySQL connectivity
- JWT authentication and bcrypt password hashing
- Routed application UI
- Charts, Excel export, notifications, and shared components
- Project-management workbooks and planning material

## Current status

Application source exists in `frontend/` and `backend/`, but the previous README did not describe the hospitality workflows, user roles, database schema, API, configuration, tests, or deployment state. A separate correctly spelled `hospitality` repository is currently only a placeholder.

The repository tree also includes a tracked `node_modules` directory, which should normally be removed from source control after verifying no unique source is stored there.

## Recommended next work

1. Confirm this repository as the canonical hospitality project or migrate it into the correctly spelled repository.
2. Document the exact workflows—such as property, room, booking, guest, billing, staff, inventory, or reporting—only where the implementation supports them.
3. Add safe `.env.example`, database migrations/seeding, API documentation, tests, and deployment instructions.
4. Remove generated dependencies and other non-source artifacts from version control.

## Complete project guide

For a detailed, repository-specific explanation of product purpose, intended users, workflows, technical architecture, implementation status, validation, data/security boundaries and future milestones, read the [**Project Handbook**](docs/PROJECT_HANDBOOK.md). The handbook is a documentation assessment, not a certification of live features.
