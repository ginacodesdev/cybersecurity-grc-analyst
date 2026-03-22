# RMF Step 4 — Implement

![Last Reviewed](https://img.shields.io/badge/Last%20Reviewed-March%202026-green)
![NIST Reference](https://img.shields.io/badge/NIST-SP%20800--53A-blue)

> 📅 Verify against current NIST SP 800-53A guidance.
> Official source: [NIST SP 800-53A](https://csrc.nist.gov/publications/detail/sp/800-53a/rev-5/final)

---

## Overview

With the security controls selected in Step 3, the
organization now moves into execution. Step 4 of the
RMF is Implement and it is where the selected controls
are actually put into place across the system. This
is the step where planning becomes action and where
the security posture of the system begins to take
its actual shape.

---

## What Implementation Looks Like

Implementation is not a single event. It is a process
that occurs across the system development life cycle
and involves multiple teams working in coordination.
Technical controls are configured by system
administrators. Policy-based controls are developed
and approved by program and compliance teams.
Physical controls are put in place by facilities
and operations staff. The GRC Analyst ensures that
all of this activity is happening in alignment with
what was selected and documented in Step 3.

---

## Types of Controls Being Implemented

| Control Type | Examples |
|-------------|---------|
| Technical | Multi-factor authentication, encryption, firewalls, audit logging, patch management |
| Administrative | Security policies, procedures, training requirements, access review processes |
| Physical | Facility access controls, surveillance systems, equipment security |
| Operational | Incident response procedures, backup and recovery processes, configuration management |

---

## Documentation Requirements in Step 4

Implementation is not complete until it is documented.
For every control that is implemented, the system
must maintain an implementation statement that
describes how the control was applied, who is
responsible for it, and how it can be verified.
These implementation statements become part of the
System Security and Privacy Plan and serve as the
primary evidence during the assessment in Step 5.

Incomplete or vague implementation statements are
one of the most common issues found during security
assessments. A statement that says a control is
implemented without explaining how it is implemented
provides no real assurance and will likely result
in a finding.

---

## Common Implementation Challenges

Implementation rarely goes exactly as planned. Some
of the most common challenges that GRC Analysts and
system teams encounter during Step 4 include the
following:

| Challenge | Impact |
|-----------|--------|
| Legacy systems that cannot support modern controls | May require compensating controls or POAMs |
| Resource constraints limiting implementation timelines | Can delay authorization and introduce risk |
| Conflicting technical requirements between controls | Requires careful coordination between security and engineering teams |
| Insufficient documentation of implemented controls | Creates gaps that assessors will flag in Step 5 |

---

## The Role of the GRC Analyst in Step 4

The GRC Analyst serves as a coordinator and quality
control checkpoint during implementation. While
technical teams handle the actual configuration
work, the GRC Analyst ensures that implementation
aligns with what was selected and documented,
that implementation statements are clear and
complete, that any gaps or deviations are identified
and addressed early, and that the system is building
toward an assessment-ready state before Step 5 begins.

Catching implementation gaps early is significantly
less costly than discovering them during a formal
assessment. The GRC Analyst's proactive involvement
in this step is what separates organizations that
sail through Step 5 from those that accumulate
findings and POAMs.

---

## Key Terms

| Term | Definition |
|------|-----------|
| Implementation Statement | Documentation describing how a specific security control was applied to a system |
| Technical Control | A control enforced through technology such as software configurations or hardware settings |
| Administrative Control | A control enforced through policies, procedures, and organizational processes |
| Compensating Control | An alternative measure used when the primary control cannot be implemented as specified |
| POAM | Plan of Action and Milestones — a document tracking security weaknesses and remediation plans |

---

## Connection to the Next Step

Everything implemented in Step 4 will be examined
in Step 5 — Assess. Assessors will review
implementation statements, test controls, and
verify that what was documented actually reflects
what was built. The quality of the work done in
Step 4 directly determines how smooth or how
difficult the assessment process will be.
