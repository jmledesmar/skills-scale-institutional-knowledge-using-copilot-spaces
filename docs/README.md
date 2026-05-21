# OctoAcme Project Management Docs

This README provides an overview of project management practices used by the OctoAcme team and links to all relevant process documents.

## OctoAcme Project Management Process — Summary

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The process is organized into five primary phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Closure & Retrospective**. During Initiation, teams validate business needs by developing a Project One-pager that captures the problem statement, measurable success metrics, stakeholder alignment, and resource requirements. Once stakeholders approve the initiative, the Planning phase transforms the vision into an actionable backlog with prioritized items, acceptance criteria, release timelines, and a Definition of Done. This structured foundation ensures that all team members understand scope and expectations before development begins.

Execution and delivery are managed through a regular team rhythm that includes daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations tracked on a project board with columns for Backlog, Ready, In Progress, In Review, QA, and Done. OctoAcme maintains strict quality standards by requiring unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI. Pull requests are kept small (≤400 lines when possible), include issue links and acceptance criteria, and require at least one approval before merging. The team emphasizes psychological safety and data-driven decisions, using velocity tracking, burndown metrics, and dashboards to monitor progress and identify risks early.

The organizational structure defines clear roles and accountability: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes, prioritize the backlog, and measure success; **Developers** implement features and collaborate on design and testability; and **QA/Testing** validates quality against acceptance criteria. Communication is intentional and multi-layered, with weekly PM-to-Product Lead syncs, twice-weekly team standups, monthly stakeholder updates, and a formal escalation path (Team → PM → Product Lead → Sponsor) for blockers and business-impacting issues. Risk management is ongoing, with a Risk Register maintained throughout the project lifecycle and weekly reviews embedded into syncs.

Release and deployment are treated as deliberate, safety-conscious activities with pre-release requirements including all acceptance criteria met, passing CI and security scans, documented rollback plans, and prepared smoke tests. After deployment, the team conducts a retrospective to capture learnings and convert them into actionable improvements tracked in the backlog. This continuous improvement mindset, combined with transparent communication templates for status updates and incident responses, ensures that OctoAcme teams deliver reliable features consistently while building institutional knowledge and reducing single-person dependency risk across the organization.

## Process Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## Quick Start

**New to OctoAcme projects?** Start with [Project Management Overview](octoacme-project-management-overview.md) to understand our core principles and key artifacts.

**Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) to validate business need and get stakeholder alignment.

**Already approved and ready to plan?** Use the [Project Planning](octoacme-project-planning.md) guide to break work into shippable increments.

**Managing day-to-day delivery?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for workflows, quality standards, and reporting.

**Need to handle risks or escalations?** See [Risk Management & Communication](octoacme-risks-and-communication.md) for playbooks and templates.

**Getting ready to release?** Review the [Release & Deployment Guide](octoacme-release-and-deployment.md) for pre-release checks and rollback procedures.

**Capturing learnings?** Follow [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to turn feedback into action items.

**Understanding team roles?** Check out [Roles and Personas](octoacme-roles-and-personas.md) to see responsibilities and goals for each function.
