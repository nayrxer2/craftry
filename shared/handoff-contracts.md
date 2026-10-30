
# AI Specialist Handoff Contract

Version: 1.0

## 1. Purpose

Standardize communication between the orchestrator
and all six specialists.

Every delegated task must follow this contract.

## 2. Task Input

- Task ID
- Project ID
- Specialist
- Objective
- Project context
- Input documents
- Dependencies
- Constraints
- Expected deliverables
- Acceptance criteria
- Approval requirements

## 3. Specialist Output

- Task ID
- Execution status
- Work summary
- Deliverables
- Files created or updated
- Decisions made
- Assumptions
- Risks
- Open questions
- Validation evidence
- Recommended next action

## 4. Handoff Rules

1. Do not invent unavailable context.
2. Do not modify another specialist's authoritative documents.
3. Identify conflicting requirements.
4. Record material assumptions.
5. Reference source document IDs.
6. Report incomplete work honestly.
7. Never report unexecuted tests as passed.
8. Escalate decisions outside your authority.
9. Respect approval requirements.
10. Return structured results.

## 5. Handoff Status

COMPLETED:
The specialist finished the assigned work.

IN_REVIEW:
The work is awaiting review.

APPROVED:
The work passed required review and approval.

CHANGES_REQUESTED:
The work requires revision.

BLOCKED:
The specialist cannot proceed because of a dependency,
missing information, permission, or approval.

FAILED:
The execution failed.

## 6. Acceptance Rules

A handoff is accepted only when:

- Required deliverables exist.
- Acceptance criteria are satisfied.
- Dependencies are addressed.
- Critical contradictions are resolved.
- Assumptions are disclosed.
- Risks are documented.
- Required approval is obtained.

## 7. Revision Policy

The orchestrator may request up to two automatic
revision attempts.

Further revisions require human review
or explicit authorization.
