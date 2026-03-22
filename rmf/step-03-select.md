# RMF Step 3 — Select

![Last Reviewed](https://img.shields.io/badge/Last%20Reviewed-March%202026-green)
![NIST Reference](https://img.shields.io/badge/NIST-SP%20800--53-blue)

> 📅 Verify against current NIST SP 800-53 Rev 5 guidance.
> Official source: [NIST SP 800-53](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)

---

## Overview

With the system defined and its impact level established,
the organization is now ready to determine exactly which
security controls are needed to protect it. Step 3 of
the RMF is Select and it is where the appropriate
baseline of security controls is chosen based on the
system's categorization from Step 2.

---

## What Are Security Controls

Security controls are the safeguards and countermeasures
that organizations put in place to protect the
confidentiality, integrity, and availability of their
systems and data. They are not just technical settings
or configurations. They include policies, procedures,
physical protections, and administrative requirements
that together form a comprehensive security posture.

NIST SP 800-53 is the primary catalog of security and
privacy controls used in this step. It organizes
controls into families that each address a specific
area of security such as access control, incident
response, configuration management, and many others.

---

## Control Baselines

NIST provides three pre-defined control baselines that
correspond directly to the impact levels established
in Step 2. These baselines serve as a starting point
for control selection.

| Impact Level | Control Baseline |
|-------------|-----------------|
| Low | Minimum set of controls sufficient for low impact systems |
| Moderate | Expanded set of controls for systems with moderate risk |
| High | Comprehensive set of controls for systems where compromise would be catastrophic |

Organizations do not simply adopt a baseline and stop
there. Baselines are a starting point. Controls can
be tailored (added, modified, or in some cases removed) based on the specific risk environment, operational
requirements, and organizational policies.

---

## Control Families in NIST SP 800-53

NIST SP 800-53 organizes its controls into families.
Each family addresses a distinct area of security and
privacy. Some of the most commonly referenced families
in GRC work include the following:

| Family | Abbreviation | Focus Area |
|--------|-------------|-----------|
| Access Control | AC | Who can access what and under what conditions |
| Audit and Accountability | AU | Logging, monitoring, and review of system activity |
| Configuration Management | CM | Maintaining secure system configurations |
| Incident Response | IR | Preparing for and responding to security incidents |
| Risk Assessment | RA | Identifying and evaluating risks to the system |
| System and Information Integrity | SI | Protecting against malicious code and system flaws |
| Planning | PL | Documenting security and privacy plans |
| Program Management | PM | Organizational-level security program oversight |

---

## Tailoring Controls

Not every control in a baseline will apply to every
system in exactly the same way. Tailoring is the
process of adjusting the baseline to fit the specific
context of the system being secured. This can include
adding controls that address risks specific to the
system's environment, modifying how a control is
implemented to align with operational constraints,
or documenting why a control is not applicable and
what compensating measure exists in its place.

Tailoring decisions must be documented and justified.
They become part of the System Security and Privacy
Plan that was initiated in Step 1.

---

## The Role of the GRC Analyst in Step 3

The GRC Analyst plays a central role in control
selection by ensuring that the right baseline is
applied, that tailoring decisions are properly
documented, and that the selected controls address
the risks identified during categorization. This
requires a working knowledge of NIST SP 800-53,
an understanding of the system's technical environment,
and the ability to communicate control requirements
clearly to system owners, administrators, and other
stakeholders who will be responsible for implementing
them.

Control selection is also where the GRC Analyst
begins thinking ahead to Step 5 — Assess. Controls
that are selected must eventually be verified. Selecting
controls that are measurable, testable, and clearly
defined makes the assessment process significantly
more straightforward.

---

## Key Terms

| Term | Definition |
|------|-----------|
| Security Control | A safeguard or countermeasure designed to protect the confidentiality, integrity, or availability of a system |
| Control Baseline | A pre-defined set of controls mapped to a specific impact level |
| NIST SP 800-53 | The NIST catalog of security and privacy controls for federal information systems |
| Control Family | A grouping of related security controls that address a common area of security |
| Tailoring | The process of adjusting a control baseline to fit the specific needs and context of a system |
| Compensating Control | An alternative control implemented when the primary control cannot be applied |

---

## Connection to the Next Step

The controls selected in Step 3 define exactly what
needs to be built, configured, and documented in
Step 4 — Implement. Every control selected here
becomes a work item for the teams responsible for
standing up and securing the system. Clear and
accurate control selection in this step makes
implementation more efficient and assessment
more reliable.
