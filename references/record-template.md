# Research idea record

Use one Markdown log per project by default. Keep an index and full entries together. Populate only available information; mark missing fields unknown or undecided.

## Project index

| ID | Title | Progress | Next action |
| --- | --- | --- | --- |
| IDEA-YYYYMMDD-NNN | Short title | Captured | Concrete action |

## Entry template

### IDEA-YYYYMMDD-NNN — Title

- **Project:** Project name
- **Created / updated:** User-local dates; include timezone when relevant
- **Origin:** User idea / assistant proposal / user-reported supervisor request / directly sourced supervisor request; attribute components separately
- **Progress:** Captured / assessing / planned / in progress / paused / completed / rejected
- **Evidence state:** Unchecked / source checked / internally tested / externally validated / mixed; scope labels to individual claims and attach support
- **Decision owner / decision:** Unknown unless supplied
- **Related ideas:** Stable IDs or none

**Research question**

State what would be established or compared.

**Original idea and rationale**

Preserve user intent and useful reasoning. Mark assistant additions as proposals. Include a brief original excerpt when wording matters.

**Proposed method and dependencies**

List minimum data, software, review, and experimental prerequisites. Separate available resources from assumed or missing resources.

**Claims and sources**

| Claim | Type | Source / locator | Inspection status | Scope / limitations |
| --- | --- | --- | --- | --- |
| Specific premise | Proposal / inference / reported result / source-checked result | Actual URL, DOI, PMID, file and section, or dated excerpt | Mentioned only / inspected / human reviewed | Applicable conditions |

**Uncertainties and risks**

Record alternatives, confounders, conflicts, source overlap, leakage, and missing evidence where relevant.

**Smallest next step**

State one bounded action, its expected output, and the decision it informs. Do not invent deadlines or approvals.

**Success / stop criteria**

Record agreed criteria, label proposed criteria, or leave undecided.

**Decision and change history**

- Date — actor/source — finding/decision — artifact — next-step implication.

## Synthetic example

This example has no real project results.

- **Title:** Compare metadata-filtered and text-only retrieval.
- **Origin:** User proposed the comparison; assistant suggested fixed retrieval depth.
- **Progress / evidence:** Captured / unchecked.
- **Question:** Does population metadata reduce unsupported generalization while retaining useful answer coverage?
- **Method:** Use reviewed questions, the same corpus, and a fixed answer model.
- **Source:** Current conversation excerpt only; no paper checked.
- **Unknowns:** Annotation capacity, test-set independence, retrieval depth.
- **Next step:** Inventory source-field coverage; do not run the comparison yet.
- **Success / stop:** Proposed: proceed if required fields and review capacity are available; not an agreed threshold.
