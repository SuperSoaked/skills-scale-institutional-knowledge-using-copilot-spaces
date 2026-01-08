# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This folder contains the canonical process documents used by OctoAcme to initiate, plan, execute, release, and continuously improve projects. Use this README as the primary entry point for onboarding new contributors, running projects, and finding the process artifacts referenced in project repositories.

## Project Management Processes Overview

OctoAcme follows a customer-focused, iterative delivery approach driven by clear roles, small increments, and measurable outcomes. Projects move through a lightweight initiation gate (one-pager to define the problem and success metrics), into planning where the team breaks work into shippable backlog items and defines acceptance criteria and a Definition of Done, then into execution using a project board and small pull requests with CI and review gates. Releases follow a standard checklist with rollback playbooks and post-deploy verification, and every effort finishes with a retrospective to capture learnings and convert them into tracked action items.

Decision-making and ownership are explicit: Product Managers own outcomes and prioritization, Project Managers coordinate delivery, Developers build and test, QA validates acceptance criteria, and Stakeholders provide inputs and approvals. Communication is enforced through a regular cadence of standups, weekly delivery syncs, demos, and stakeholder updates; a single source of truth (project README or release doc) is used for status and announcements. Risk management uses a lightweight Risk Register and clear escalation paths from team-level triage up to sponsor-level intervention when business impact is high.

Quality assurance combines automated unit, integration, and end-to-end smoke tests with CI security scanning and manual QA where needed. The pull request process requires linking to issues and acceptance criteria, passing automated checks before review, and at least one approval before merge. Continuous improvement is reinforced by retrospectives that prioritize 2–3 action items, add them to the backlog, and measure the impact of improvements over time.

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution &amp; Tracking](octoacme-execution-and-tracking.md)
- [Risk Management &amp; Communication](octoacme-risks-and-communication.md)
- [Release &amp; Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective &amp; Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles &amp; Personas](octoacme-roles-and-personas.md)

## Quick Start

- Review the Project One-pager template in the Project Initiation Guide to validate ideas.
- Use the Project Planning doc to create a prioritized backlog with acceptance criteria and a DoD.
- Follow Execution &amp; Tracking for branch, PR, and CI expectations.
- Use the Release &amp; Deployment Guide for pre-release checks and rollback plans.
- Run a Retrospective after releases or milestones and convert actions into backlog items.
