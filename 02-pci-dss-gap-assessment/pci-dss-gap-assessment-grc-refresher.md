# PCI DSS Gap Assessment – GRC Refresher Notes

## What it is

A PCI DSS gap assessment is a structured review of an environment against PCI DSS requirements to identify where controls are:
- in place
- partially in place
- missing
- weakly implemented
- not yet evidenced

It helps answer:
- what PCI DSS expects
- what the current state looks like
- where the gaps are
- what risk those gaps create
- what remediation should happen next

In GRC terms, a PCI DSS gap assessment is a compliance analysis artifact that connects:
- control interpretation
- compliance readiness
- documentation quality
- remediation planning
- ownership and accountability

## Why it matters

Organizations that store, process, or transmit cardholder data cannot rely on assumptions.

A PCI DSS gap assessment forces the organization to compare:
- required controls
- actual controls
- documented evidence
- residual weaknesses

It turns vague statements like:
- “we are probably compliant”
- “security is mostly in place”
- “the payment system should be covered”

into structured compliance analysis.

That is why a PCI DSS gap assessment matters in:
- compliance readiness reviews
- internal assessments
- audit preparation
- remediation planning
- payment security governance

## What this project proves

The SkyBridge PCI DSS gap assessment proves that you can:
- interpret control requirements against a business scenario
- identify current-state weaknesses
- distinguish between implemented controls and missing controls
- document gaps clearly
- connect gaps to risk impact
- recommend remediation actions
- assign ownership and timelines

That is real compliance and control thinking.

## The logic of the main columns

### Requirement ID
A unique identifier for the control requirement being assessed.

Why it matters:
- keeps the assessment traceable
- supports cross-reference to PCI DSS requirements
- prevents confusion during review

Professional explanation:
> The Requirement ID provides a reference point for each assessed control area, making the gap assessment easier to track and discuss.

### PCI DSS Requirement
This identifies the actual PCI DSS control area or expectation being reviewed.

Examples:
- firewall and network security
- secure configurations
- access control
- logging and monitoring
- vulnerability management

Professional explanation:
> The PCI DSS Requirement column anchors each row to a specific compliance obligation so the assessment remains tied to the standard rather than opinion.

### Current State
This describes what currently exists in the environment.

It should answer:
- what is already implemented
- how the process currently operates
- whether evidence appears available

Professional explanation:
> Current State describes how the control environment presently functions and whether the organization appears to have implemented the relevant requirement in practice.

### Gap Identified
This describes what is missing, weak, inconsistent, or undocumented.

This is one of the most important columns.

A gap is not just “bad security.”
A gap is the specific difference between:
- what the standard expects
- and what the organization currently has

Professional explanation:
> The Gap Identified column documents the difference between the required control state and the current operating reality.

### Risk Impact
This explains why the gap matters.

Possible impacts:
- regulatory non-compliance
- cardholder data exposure
- unauthorized access
- detection failure
- audit weakness
- operational disruption

Professional explanation:
> Risk Impact translates the control gap into business and compliance consequences, making the issue meaningful to management and stakeholders.

### Priority
This reflects urgency.

Typical values:
- High
- Medium
- Low

Priority is usually influenced by:
- severity of the gap
- exposure level
- likelihood of exploitation
- business criticality
- audit significance

Professional explanation:
> Priority helps determine which gaps require immediate remediation and which can be handled through scheduled corrective action.

### Recommended Action / Remediation
This states what should happen next.

Examples:
- implement MFA
- formalize access review process
- strengthen logging coverage
- document retention settings
- update secure configuration standards

Professional explanation:
> Recommended Action defines the remediation step needed to close the gap or reduce the related compliance and security exposure.

### Owner
This identifies the accountable person or function.

Examples:
- IAM Manager
- Security Operations Lead
- Infrastructure Manager
- Compliance Analyst
- Data Protection Officer

Professional explanation:
> The Owner is the accountable function responsible for coordinating remediation, providing evidence, or driving control improvement.

### Target Date
This gives the remediation timeline.

Why it matters:
- prevents open-ended issues
- supports accountability
- allows tracking in risk or compliance review meetings

Professional explanation:
> The Target Date establishes expected remediation timing and helps convert findings into actionable follow-up.

### Status
This shows the current state of the gap.

Typical values:
- Open
- In Progress
- Closed
- Under Review

Professional explanation:
> Status provides visibility into remediation progress and shows whether the identified gap remains unresolved.

## How to explain the PCI DSS gap assessment in an interview

Use something like this:

> I built a PCI DSS gap assessment using a fictional airline payment environment to practice structured compliance analysis against payment security requirements. The project focused on comparing current-state controls to PCI DSS expectations, identifying specific control gaps, documenting the risk impact of those gaps, and proposing remediation actions with ownership and target dates. It helped me strengthen my understanding of how compliance requirements are translated into control review, documented findings, and actionable remediation planning.

That answer is strong because it is:
- honest
- compliance-focused
- business-aware
- grounded in control language

## The deeper lesson

This PCI DSS gap assessment is not just a checklist.

It is a model of how compliance work happens:
- identify the requirement
- examine the current state
- document the gap
- explain the risk
- assign ownership
- drive remediation

That is the mindset you are building.

## The mistake to avoid

Do not describe the project like this:
> I checked PCI DSS controls in a spreadsheet.

That sounds shallow.

Describe it like this:
> I built a structured PCI DSS gap assessment to evaluate current-state controls against payment security requirements, identify compliance gaps, document business and security impact, and propose remediation actions in a regulated payment environment.

That sounds like compliance work.

## Helpful distinctions

### Gap vs weakness
A gap is a missing or insufficient control relative to the requirement.

A weakness may exist even where a control technically exists, but the control may be:
- inconsistent
- undocumented
- partially implemented
- ineffective

### Gap vs remediation action
A gap is the problem.
A remediation action is the planned response.

Example:
- Gap: MFA is not enforced for administrative access
- Remediation: Implement MFA for all administrative accounts and validate enrollment

### Compliance readiness vs compliance certification
A gap assessment helps measure readiness.
It does not by itself prove the organization is fully compliant or certified.

## Suggested next study topic

The next high-value topic to study from this project is:
- how to distinguish between a control deficiency, a compliance gap, and a remediation plan

That is where many beginners remain weak.
