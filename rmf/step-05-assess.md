# RMF Step 5 — Assess

![Last Reviewed](https://img.shields.io/badge/Last%20Reviewed-March%202026-green)
![NIST Reference](https://img.shields.io/badge/NIST-SP%20800--53A-blue)

> 📅 Verify against current NIST SP 800-53A guidance.
> Official source: [NIST SP 800-53A](https://csrc.nist.gov/publications/detail/sp/800-53a/rev-5/final)

---

## Overview

Implementing security controls is only half the work.
Step 5 of the RMF is Assess and it exists to answer
one critical question — are the controls that were
selected and implemented actually working as intended?
Implementation means nothing if the controls are not
functioning correctly, consistently, and in the way
they were designed to operate.

---

## Who Conducts the Assessment

Assessments are conducted by assessors who examine
the system's controls objectively. Depending on the
organization and the type of system, assessors may
come from within the organization itself or from an
independent third party. Federal systems often require
independent assessors to ensure objectivity. The
assessor's job is not to find fault for its own sake. It is to provide an accurate picture of the system's
actual security posture so that the Authorizing
Official in Step 6 can make an informed decision.

---

## What Assessors Look For

Assessors examine controls across three dimensions
to determine whether they are functioning as required:

| Assessment Dimension | What It Means |
|---------------------|--------------|
| Completeness | Is the control fully implemented with no gaps? |
| Effectiveness | Is the control actually doing what it is supposed to do? |
| Documentation | Is the control documented clearly enough to be verified? |

Common examples of what assessors verify include
whether audit logging is active and capturing events
at the required frequency; whether multi-factor
authentication is enforced for all users without
exception; whether backup systems are actually
performing backups and whether those backups can
be successfully restored; and whether access controls
are limiting permissions to only what is necessary
for each role.

---

## When Controls Fail Assessment

When an assessor finds a control that is incomplete,
ineffective, or insufficiently documented, the result
is a finding. Findings are not the end of the world
but they do require action. Every finding that cannot
be remediated immediately must be captured in a
Plan of Action and Milestones (POAM). The POAM
outlines the weakness, maps it to the relevant
control, defines the milestones for remediation,
and establishes a target completion date.

There is also a category of controls that an
organization may be unable to implement at all.
This can happen when implementation would break
a critical system function, when the cost is
prohibitive, or when the technical environment
simply cannot support the control as specified.
In these situations the organization opens a POAM
for risk acceptance, which requires leadership
to formally acknowledge the risk and sign off on
the decision to accept it rather than remediate it.

---

## The Role of the GRC Analyst in Step 5

The GRC Analyst does not sit on the sidelines during
an assessment. This is an active and demanding phase
that requires the GRC Analyst to coordinate access
for assessors to the right people, systems, and
documentation; to serve as the primary point of
contact between assessors and the system team;
to help locate and organize evidence that supports
implementation statements; and in some cases to
actively defend implementation decisions when
assessors have questions.

Being prepared for Step 5 means that the GRC
Analyst has been paying attention throughout Steps
1 through 4. A system that arrives at assessment
with complete documentation, clearly written
implementation statements, and a team that
understands their controls will move through this
step far more efficiently than one that treated
the previous steps as paperwork exercises.

---

## Key Terms

| Term | Definition |
|------|-----------|
| Assessment | A formal examination of security controls to determine if they are implemented correctly and operating effectively |
| Finding | A control weakness identified during an assessment that requires corrective action |
| POAM | Plan of Action and Milestones — documents a weakness and the plan to remediate it |
| Risk Acceptance | A formal decision by leadership to acknowledge and accept a risk rather than remediate it |
| Independent Assessor | An assessor with no direct stake in the system being assessed, required for objectivity |
| Security Assessment Report (SAR) | The formal output of the assessment process documenting all findings and recommendations |

---

## Connection to the Next Step

The Security Assessment Report produced in Step 5
along with all outstanding POAMs and the System
Security and Privacy Plan are the primary inputs
into Step 6 — Authorize. The Authorizing Official
will review everything produced up to this point
and make the final determination on whether the
system is approved to operate.
