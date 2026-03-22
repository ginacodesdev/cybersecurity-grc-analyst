# RMF Step 2 — Categorize

![Last Reviewed](https://img.shields.io/badge/Last%20Reviewed-March%202026-green)
![NIST Reference](https://img.shields.io/badge/NIST-SP%20800--60-blue)

> 📅 Verify against current NIST SP 800-60 guidance.
> Official source: [NIST SP 800-60](https://csrc.nist.gov/publications/detail/sp/800-60/vol-1-rev-1/final)

---

## Overview

Once the system has been defined and the groundwork
has been laid in Step 1, the next step is to determine
how sensitive the system actually is. Step 2 of the
RMF is Categorize and it is where the organization
takes a holistic look at the system to determine its
impact level. This impact level drives everything that
comes next, particularly which security controls will
be required in Step 3.

---

## The CIA Triad as the Categorization Lens

Categorization is built around the CIA Triad: 
Confidentiality, Integrity, and Availability. For
every data type that the system processes, stores,
or transmits, the organization must ask what the
impact would be if that data or system were
compromised in relation to each of the three
principles.

| CIA Principle | Question to Ask |
|---------------|----------------|
| Confidentiality | What is the impact if unauthorized parties access this data? |
| Integrity | What is the impact if this data is altered or corrupted? |
| Availability | What is the impact if this system or data becomes inaccessible? |

---

## Impact Levels

Each data type is assigned an impact level based on
the potential consequences of a compromise. The three
levels are defined as follows:

| Impact Level | Definition |
|-------------|-----------|
| Low | A compromise would result in limited or no negative effects on the organization |
| Moderate | A compromise would result in serious but non-critical effects on the organization |
| High | A compromise would result in catastrophic effects on the organization |

The overall system impact level is determined by the
highest impact level assigned across all data types
and all three CIA principles. A system that handles
even one high-impact data type is considered a high
impact system regardless of its other characteristics.

---

## Key Documents Produced in Step 2

Three documents are particularly important to the
categorization process:

| Document | Purpose |
|----------|---------|
| Privacy Threshold Analysis (PTA) | Determines whether the system handles personally identifiable information (PII) and to what extent |
| Privacy Impact Analysis (PIA) | Assesses the risks associated with the collection, use, and handling of PII |
| System Categorization Summary (FIPS 199) | The formal document that records the system's impact level for Confidentiality, Integrity, and Availability |

Together these documents establish how the system
handles data and what the overall impact level is.
They also inform which security and privacy controls
will need to be selected in Step 3.

---

## The Role of the GRC Analyst in Step 2

The GRC Analyst ensures that categorization is
conducted accurately and completely. This means
working with system owners and data custodians to
identify all data types the system handles, applying
the CIA Triad consistently across each data type,
and ensuring the required documentation is completed
and reviewed before moving forward.

Categorization errors at this step have downstream
consequences. An underclassified system may receive
insufficient controls, leaving it vulnerable. An
overclassified system may receive more controls than
necessary, creating unnecessary cost and complexity.
Getting this step right is essential.

---

## Key Terms

| Term | Definition |
|------|-----------|
| CIA Triad | The three core principles of information security: Confidentiality, Integrity, and Availability |
| Impact Level | The assessed severity of harm that would result from a compromise of the system or its data |
| FIPS 199 | Federal Information Processing Standard that defines the categories of impact for federal information systems |
| PII | Personally Identifiable Information — any data that can be used to identify a specific individual |
| Privacy Threshold Analysis | An initial assessment to determine if a system triggers privacy requirements |

---

## Connection to the Next Step

The impact level established in Step 2 directly
determines which security controls are required in
Step 3 — Select. A high impact system will require
a more comprehensive set of controls than a low
impact system. Every categorization decision made
here has a direct and measurable effect on the
workload, cost, and complexity of everything that
follows.
