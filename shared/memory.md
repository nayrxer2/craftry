AI Product Development Team — Shared Memory

Version: 1.0.0
Purpose: Persistent shared knowledge for the AI Product Development Team.

1. Purpose

This document serves as the central memory repository for all AI specialists.

Its purpose is to preserve important project knowledge, decisions, constraints, conventions, and lessons learned across conversations and development sessions.

All specialists must consult this document when relevant before making decisions or performing work.

This document complements:

AGENTS.md — Global team instructions.
Individual SKILL.md files — Specialist responsibilities and operating rules.
project-context.md — Current project information.
handoff-contracts.md — Specialist communication standards.
decision-log.md — Formal decision history.
2. Project Environment
Current Development Stack
Category	Technology
Framework	Next.js
Programming Language	TypeScript
Runtime	Not yet fixed
AI Provider	Not yet fixed
Agent Orchestration	Not yet implemented
Database	Not yet fixed
Deployment	Not yet fixed
Compatibility Requirements
Keep specialist instructions provider-independent.
Do not assume a particular AI model.
Do not assume a specific agent execution framework.
Do not assume a particular database.
Prefer TypeScript-compatible implementation approaches.
Inspect the existing repository before proposing structural changes.
3. AI Team Structure

The team consists of six professional specialists and one central orchestrator.

3.1 Product Manager

Responsibility: Product direction.

Owns:

Product vision
Product strategy
Product goals
Product scope
Feature prioritization
MVP definition
Product roadmap
Product requirements documents
3.2 Business Analyst

Responsibility: Business and requirements analysis.

Owns:

Business requirements
Functional requirements
Non-functional requirements
Business rules
Use cases
Acceptance criteria
Requirements traceability
3.3 UX Designer

Responsibility: User experience and usability.

Owns:

User research
User personas
User journeys
Information architecture
Navigation
User flows
Wireframes
Interaction specifications
Usability evaluation
3.4 System Analyst

Responsibility: System behavior and technical specifications.

Owns:

System boundaries
Architecture proposals
Component specifications
Database models
API contracts
Data flows
Integration specifications
Technical constraints
Architecture decision records
3.5 UI Designer

Responsibility: Visual interface design.

Owns:

Visual direction
Typography
Color systems
Design tokens
Component specifications
Design systems
Responsive layouts
High-fidelity designs
Visual quality assurance
3.6 Software Engineer

Responsibility: Software implementation.

Owns:

Frontend development
Backend development
API implementation
Database integration
Authentication implementation
Automated testing
Debugging
Code reviews
Deployment implementation
3.7 Orchestrator

Responsibility: Coordination and quality control.

Owns:

Task classification
Specialist selection
Task delegation
Dependency management
Workflow coordination
Handoff validation
Conflict resolution
Approval tracking
Final delivery reporting

The orchestrator coordinates the specialists but does not replace their professional expertise.

4. Team Operating Principles

All specialists must follow these principles:

Respect specialist responsibilities.
Use the minimum number of specialists necessary.
Never activate the entire team unnecessarily.
Preserve approved project decisions.
Never fabricate research, requirements, or test results.
Clearly distinguish assumptions from verified facts.
Identify missing information.
Document important decisions.
Maintain requirements traceability.
Escalate decisions outside individual authority.
Respect dependencies between tasks.
Never claim work was executed without evidence.
5. Workflow Knowledge

The standard product development workflow is:

Product Discovery — Product Manager.
Business Analysis — Business Analyst.
UX and System Analysis — UX Designer and System Analyst.
UI Design — UI Designer.
Software Implementation — Software Engineer.
Validation — Relevant specialists.
Release Readiness — Orchestrator and required approvers.

Parallel execution is permitted when dependencies and required inputs are satisfied.

The workflow is not unnecessarily rigid. Small isolated tasks may bypass unrelated stages.

6. Decision and Approval Rules

The Product Owner retains final authority over major product decisions.

Specialist authority:

Decision	Responsible Role
Product strategy	PM
Product priorities	PM
Business requirements	BA
Business rules	BA / authorized business stakeholder
User experience	UX Designer
Technical specifications	System Analyst
Visual design	UI Designer
Implementation details	Software Engineer
Cross-team coordination	Orchestrator

Require appropriate approval before:

Major scope changes.
Business policy changes.
High-impact architecture changes.
Destructive database operations.
Production deployment.
Irreversible external actions.
7. Project Documentation Standards

Maintain the following documents as separate sources of truth:

Document	Purpose
AGENTS.md	Global instructions
memory.md	Persistent shared knowledge
project-context.md	Current project state
handoff-contracts.md	Task communication
decision-log.md	Formal decision records

Specialists must update the appropriate document when authorized and when a meaningful change occurs.

Do not duplicate entire documents inside memory.

8. Memory Management Rules
What to Remember

Store information that is likely to remain useful:

Confirmed architectural decisions.
Approved technical conventions.
Important project constraints.
Repeated user preferences.
Established coding standards.
Important lessons learned.
Confirmed business decisions.
Cross-specialist collaboration rules.
Resolved issues with reusable solutions.
What NOT to Remember

Do not permanently store:

Temporary conversation details.
Unverified assumptions as facts.
Duplicate information.
Sensitive credentials or secrets.
API keys and access tokens.
Personal confidential information.
Temporary debugging output.
Outdated decisions without marking them superseded.
Memory Update Procedure

Before updating memory:

Identify the proposed information.
Determine whether it is reusable.
Check whether it already exists.
Verify its source.
Determine whether it conflicts with existing knowledge.
Update the appropriate section.
Record important decisions in decision-log.md.
Update the version or revision history.

Never silently overwrite important historical knowledge.

9. Knowledge Confidence

Classify information using these labels:

CONFIRMED: Verified or explicitly approved.
ASSUMED: Used temporarily but not verified.
PROPOSED: Suggested but not approved.
SUPERSEDED: Replaced by a newer decision.
UNKNOWN: Information is unavailable.

Never present ASSUMED, PROPOSED, or UNKNOWN information as confirmed.

10. Conflict Resolution

When specialists disagree:

Identify the conflicting statements.
Identify the responsible decision owners.
Review approved requirements and decisions.
Evaluate business impact.
Evaluate user impact.
Evaluate technical impact.
Present alternatives and trade-offs.
Escalate to the appropriate authority.
Record the final decision.

The orchestrator must not resolve conflicts by arbitrarily overriding specialist ownership.

11. Repository Structure

Current agreed structure:

text
[project]/
│
├── .agent/
│   └── skills/
│       ├── orchestrator/
│       │   └── SKILL.md
│       ├── product-manager/
│       │   └── SKILL.md
│       ├── business-analyst/
│       │   └── SKILL.md
│       ├── ux-designer/
│       │   └── SKILL.md
│       ├── system-analyst/
│       │   └── SKILL.md
│       ├── ui-designer/
│       │   └── SKILL.md
│       └── software-engineer/
│           └── SKILL.md
│
├── shared/
│   ├── memory.md
│   ├── project-context.md
│   ├── handoff-contracts.md
│   └── decision-log.md
│
├── AGENTS.md
│
├── src/
├── public/
├── package.json
└── tsconfig.json

12. Current Known Decisions
ID	Decision	Status
MEM-001	Team consists of six professional specialists	CONFIRMED
MEM-002	Specialists coordinate through an orchestrator	CONFIRMED
MEM-003	Skills must contain strict activation rules	CONFIRMED
MEM-004	Skills must be provider-independent	CONFIRMED
MEM-005	Current development stack is Next.js and TypeScript	CONFIRMED
MEM-006	Skills are stored under .agent/skills/	CONFIRMED
MEM-007	Shared documentation is stored under root shared/	CONFIRMED
MEM-008	AI execution runtime is not yet selected	UNKNOWN
MEM-009	Database and persistence technology are not yet selected	UNKNOWN
13. Future Considerations

The following capabilities are potential future improvements, not yet confirmed implementations:

Dynamic agent registry.
Provider-independent model adapters.
Task execution scheduler.
Persistent task state.
Cross-agent communication.
Approval workflow.
Execution audit logs.
Retry and failure handling.
Human-in-the-loop controls.
Agent performance evaluation.
Knowledge retrieval system.
Project-specific memory isolation.
14. Final Rule

Memory exists to improve continuity, consistency, and decision quality.

It must not become an uncontrolled collection of conversation history.

Store verified, reusable, relevant knowledge.

When information is missing, ask or investigate rather than inventing it.