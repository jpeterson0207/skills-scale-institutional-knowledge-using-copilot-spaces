# OctoAcme Project Management Docs

This README serves as the entry point to OctoAcme's project management process documentation. It provides an overview and convenient links to all process documents in the `docs/` folder.

## Overview of Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management grounded in clear ownership, iterative delivery, and data-driven decision-making. The framework spans five core phases: **Initiation** (validating business need and stakeholder alignment through a lightweight One-pager), **Planning** (breaking work into shippable increments with prioritized backlogs and risk registers), **Execution** (daily standups and weekly syncs with a project board workflow), **Release** (standardized deployment with pre-flight checks and rollback plans), and **Close & Retrospective** (capturing learnings and converting them into actionable improvements).

### Core Roles & Responsibilities

The organizational structure relies on three core roles working in concert:

- **Project Managers (PMs)** coordinate delivery, manage schedules, risks, and communications to keep teams on track and stakeholders informed.
- **Product Managers (PdMs)** define what should be built by owning the product vision, prioritizing the backlog, and measuring outcomes through success metrics.
- **Developers** implement features, write tests, and collaborate on design while helping identify technical risks.

This clear separation of ownership prevents bottlenecks and ensures that strategic decisions (what to build) remain distinct from execution (how to build it and when).

### Communication & Risk Management

Communication and risk management are woven throughout OctoAcme's workflows. Teams maintain consistent cadences—daily standups (15 minutes), weekly PM-PdM syncs, twice-weekly delivery standups, and monthly stakeholder updates—supported by a single source of truth (the project repository) and standardized templates. Risk management is continuous: risks are identified during planning, assessed for impact and likelihood, actively mitigated, and reviewed weekly. Escalation follows a tiered path (team → PM → Product Lead → Sponsor) for business-impacting issues.

### Quality & Delivery Practices

Quality and delivery practices emphasize small, testable increments and measurable outcomes. Development follows a Pull Request workflow with automated CI (tests, linting, security scanning) and requires at least one approval before merging. Quality assurance includes unit tests, integration tests, end-to-end smoke tests, and manual QA for feature acceptance. Teams track velocity and burndown, and use retrospectives to identify improvements. This combination of iterative delivery, continuous communication, and disciplined quality gates enables OctoAcme teams to balance speed with reliability.

---

## Process Docs Index

Navigate to each process document for detailed guidance:

- [**Project Management Overview**](octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, principles, roles, and artifacts.
- [**Project Initiation Guide**](octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan.
- [**Project Planning**](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog for delivery.
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Manage day-to-day execution and track progress toward project milestones.
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies.
- [**Release & Deployment Guide**](octoacme-release-and-deployment.md) — Standardize releases to production to reduce risk and improve observability.
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements.
- [**Roles and Personas**](octoacme-roles-and-personas.md) — Detailed definitions of typical roles and responsibilities in OctoAcme projects.

---

> Keep this README and the docs folder up to date as new process documents are added or updated. Use the issue template [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose updates or additions.
