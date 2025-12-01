<!-- SYNC IMPACT REPORT
- Version: 1.0.0
- Modified Principles: None (Initial creation)
- Added sections: Core Principles, Development Workflow, Quality Gates, Governance
- Removed sections: None
- Templates requiring updates: 
  - ✅ .specify/templates/plan-template.md
  - ✅ .specify/templates/spec-template.md
  - ✅ .specify/templates/tasks-template.md
- Follow-up TODOs: None
-->
# my_kitplus_gemini Constitution

## Core Principles

### I. Spec-Driven Development
Every feature must begin with a specification. The spec defines the 'what' and the 'why', and must be approved before implementation begins. This ensures clarity and alignment on project goals.

### II. Plan-Driven Architecture
Once a spec is approved, an architectural plan must be created. The plan outlines the 'how', including key technical decisions, APIs, and data structures. This prevents rework and ensures technical coherence.

### III. Task-Oriented Implementation
Implementation is broken down into small, testable tasks. Each task corresponds to a specific part of the plan and spec, enabling incremental progress and making code easier to review and test.

### IV. Test-First Mandate
For every task, tests must be written before the implementation code (TDD). Tests must fail before the code is written (Red), pass after the code is written (Green), and code should be cleaned up (Refactor).

### V. Continuous Documentation
All significant work, from user requests to architectural decisions, must be documented in Prompt History Records (PHRs) and Architectural Decision Records (ADRs). This creates a living, searchable history of the project.

## Development Workflow
The standard workflow is: Spec -> Plan -> Tasks -> Red -> Green -> Refactor. Each stage must be completed before the next begins.

## Quality Gates
All code must pass automated tests, linting, and type-checking before being merged. Code reviews are required for all changes and must focus on adherence to the constitution and the approved plan.

## Governance
This constitution is the single source of truth for project practices. Any deviation requires a formal amendment. Amendments are proposed via pull request, require approval from the project lead, and must include a plan to update any affected documentation or templates. All project members are responsible for upholding these principles.

**Version**: 1.0.0 | **Ratified**: 2025-11-29 | **Last Amended**: 2025-11-29