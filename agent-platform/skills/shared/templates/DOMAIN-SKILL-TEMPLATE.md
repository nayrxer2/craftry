DOMAIN-SKILL-TEMPLATE.md

Template Version: 1.0.0
Status: PROPOSED
Skill Level: DOMAIN
Activation: On-Demand
Architecture: DOMAIN → SUBDOMAIN → ATOMIC SKILL

1. METADATA
   name: "[domain-name]" description: "[What this domain owns and when it should be activated]"
   Field Value
   Domain ID DOMAIN-[XXX]
   Version 1.0.0
   Skill Level DOMAIN
   Parent None
   Priority [P0/P1/P2/P3]
   Status [Lifecycle status]
   Activation On-Demand
2. MISSION

Define the domain's engineering mission, business value, primary responsibilities, and expected outcomes.

3. AUTHORITY AND RESPONSIBILITY
   3.1 Owns

[Responsibilities exclusively owned by this domain.]

3.2 May Recommend

[Decisions it may advise on but does not own.]

3.3 Exclusions

[Responsibilities owned by other domains.]

3.4 Delegation

[Conditions requiring cross-domain delegation.]

4. ACTIVATION PROTOCOL
   4.1 MUST ACTIVATE

[Concrete conditions.]

4.2 MUST NOT ACTIVATE

[Conditions outside its responsibility.]

4.3 Activation Decision

Evaluate the actual engineering responsibility, not keywords alone.

4.4 Required Context

[Minimum project and task information.]

5. DOMAIN CAPABILITY TAXONOMY

For every subdomain document:

Subdomain ID.
Name.
Mission.
Responsibilities.
Exclusions.
Priority.
Activation conditions.
Registry location. 6. SKILL DISCOVERY AND ORCHESTRATION
6.1 Task Analysis

Determine the actual problem and expected outcome.

6.2 Subdomain Selection

Identify the smallest set of relevant subdomains.

6.3 Atomic Skill Discovery

Consult the selected subdomain registries.

6.4 Capability Selection

Select only the atomic skills necessary for correct execution.

6.5 Dependency Resolution

Resolve HARD and CONDITIONAL dependencies.

RELATED capabilities remain optional.

6.6 Execution Planning

Define:

Skill execution order.
Shared inputs.
Expected outputs.
Dependencies.
Validation requirements.
6.7 Missing Capability

Report capability gaps. Do not silently substitute unrelated skills.

6.8 Cross-Domain Delegation

Identify the responsible domain and delegate explicitly.

7. EXECUTION GOVERNANCE

Follow the approved execution modes:

ANALYZE
RECOMMEND
PREPARE
EXECUTE
APPROVAL-REQUIRED

The consuming runtime enforces permissions.

The domain must not interpret skill instructions as permission to perform unauthorized operations.

8. CONFLICT RESOLUTION

Resolve conflicts by examining:

Responsibility ownership.
Approved project requirements.
Applicable architecture decisions.
Supporting evidence.
Technical trade-offs.
Relevant domain authority.

Escalate unresolved material conflicts.

9. VALIDATION AND QUALITY GATES

Validate:

Correct domain activation.
Correct subdomain selection.
Correct atomic skill selection.
Dependency compliance.
No unnecessary capability loading.
Cross-domain coordination.
Deliverable completeness.
Evidence-backed decisions. 10. REQUIRED DELIVERABLES

Produce only relevant outputs:

Task analysis.
Capability selection.
Execution plan.
Delegation requirements.
Technical recommendations.
Validation findings.
Capability gaps. 11. EVALUATION SCENARIOS

Include:

Normal activation.
Multiple subdomain selection.
Incorrect activation.
Missing atomic skill.
Unnecessary skill loading.
Cross-domain delegation.
Conflicting recommendations.

For each scenario define expected behavior and critical failure conditions.

12. SKILL GOVERNANCE

Define procedures for:

Subdomain registration.
Atomic skill registration.
Capability duplication detection.
Lifecycle management.
Version compatibility.
Registry maintenance.
Deprecation.
Approval. 13. DEFINITION OF DONE

Define measurable completion requirements for domain-level orchestration.

14. PROFESSIONAL OPERATING STANDARD

The domain must challenge flawed assumptions, respect ownership boundaries, minimize unnecessary activation, identify uncertainty, and report incomplete work.

15. REFERENCES

List relevant authoritative domain references.

Research records belong to the relevant atomic skills.

16. CHANGE HISTORY
    Version Date Change Status
    1.0.0 [Date] Initial approved structure [Status]
