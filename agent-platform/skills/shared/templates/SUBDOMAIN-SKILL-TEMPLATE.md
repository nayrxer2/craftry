SUBDOMAIN-SKILL-TEMPLATE.md

Template Version: 1.0.0
Status: PROPOSED
Skill Level: SUBDOMAIN
Activation: On-Demand

1. METADATA
   name: "[subdomain-name]" description: "[What this subdomain organizes and when it is relevant]"
   Field Value
   Subdomain ID SUBDOMAIN-[XXX]
   Version 1.0.0
   Parent Domain [Domain ID]
   Skill Level SUBDOMAIN
   Priority [P0/P1/P2/P3]
   Status [Lifecycle status]
2. MISSION

Define the specialized engineering capability and the outcomes it organizes.

3. SCOPE
   3.1 Included Responsibilities

[List owned capabilities.]

3.2 Excluded Responsibilities

[List capabilities belonging elsewhere.]

3.3 Boundaries

[Define responsibility limits.]

4. RESPONSIBILITIES
   Maintain the atomic skill registry.
   Define capability boundaries.
   Establish activation and selection criteria.
   Identify dependencies.
   Detect overlapping responsibilities.
   Maintain capability metadata.
   Support domain-level discovery.
   Define subdomain validation requirements.
5. CAPABILITY TAXONOMY

Document each capability category:

Capability Responsibility Priority Selection Criteria
[Name] [Scope] [Priority] [Conditions] 6. ATOMIC SKILL REGISTRY
Skill ID Skill Name Responsibility Priority Status Path
[ID] [Name] [Scope] [Priority] [Status] [Path]

Only approved registry entries may be represented as approved capabilities.

7. ACTIVATION AND SELECTION
   7.1 Activation Conditions

[When this subdomain is relevant.]

7.2 Selection Criteria

[How relevant atomic skills are identified.]

7.3 Non-Activation

[When another subdomain owns the task.]

7.4 Minimum Sufficient Selection

Avoid loading unnecessary sibling capabilities.

8. SKILL DEPENDENCIES

Use unique atomic skill IDs.

Source Skill Dependency Skill ID Type Condition Justification
[ID] [ID] HARD / CONDITIONAL / RELATED [Condition] [Reason]

Rules:

HARD dependencies are necessary for correct execution.
CONDITIONAL dependencies apply only under specified conditions.
RELATED dependencies are optional supporting capabilities.
Circular HARD dependencies must be rejected.
Missing dependencies must be reported. 9. COORDINATION RULES

Define:

Shared inputs.
Execution order.
Output integration.
Conflicting recommendations.
Cross-domain handoffs.
Escalation requirements. 10. VALIDATION REQUIREMENTS

Validate:

Unique capability ownership.
Correct registry entries.
Explicit dependencies.
Clear activation criteria.
Independent atomic execution.
No unnecessary duplication.
Registry consistency. 11. EVALUATION SCENARIOS

Include:

Correct skill selection.
Multiple skill selection.
Incorrect selection.
Missing capability.
Unnecessary dependency.
Overlapping responsibilities.
Non-activation.

Define expected behavior and critical failures.

12. DEFINITION OF DONE

The subdomain is complete when its registry, boundaries, dependencies, selection criteria, and validation requirements are complete and consistent.

13. REFERENCES

List relevant domain and technical references.

14. CHANGE HISTORY
    Version Date Change Status
    1.0.0 [Date] Initial approved structure [Status]
