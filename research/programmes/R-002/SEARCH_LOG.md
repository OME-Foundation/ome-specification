# R-002 Stage A search log

Status: Stage A started; Search Round 001 recorded. Candidate selection only—no
evidence registration, appraisal, coverage classification or claim assessment.

This is the immutable execution log required by the approved
[search strategy](SEARCH_STRATEGY.md) and interpreted only through the approved
[construct map](CONSTRUCT_MAP.md). Original query and selection records are not
silently rewritten. Corrections must be appended as dated notes.

Candidate identifiers in this log are local triage identifiers, not Evidence
Register identifiers. `Retain`, `defer` and `exclude` are source-selection
decisions only. They do not assign evidential direction, lifecycle, confidence
or a coverage level.

## Execution context

- **Programme:** R-002 — Test the claimed cross-lifecycle coverage gap.
- **Stage:** A.
- **Research Lead:** repository execution agent (Codex).
- **Execution date:** 2026-07-18.
- **Authority:** Stage A authorised by the merge of
  [PR #19](https://github.com/OME-Foundation/ome-specification/pull/19).
- **Public/private boundary:** public-source discovery only; no ContextBridge,
  customer, commercial or private product information used.

## Search Round 001

### Round record

- **Round ID:** R2-A-001.
- **Purpose:** begin the strategy's disconfirmation-first sequence by seeking
  named lifecycle-wide approaches, systems-engineering and digital-thread
  practice, deliberate MBSE compositions, and implementation or adoption
  limitations.
- **Mandatory families targeted:** F-01, F-03, F-09 and F-10.
- **Secondary families touched:** F-02 and F-05 through enterprise-architecture,
  decision-rationale and operational-feedback vocabulary.
- **Interface:** OpenAI web-search tool exposed to the Codex desktop research
  agent as `web.run`, using its `search_query` operation.
- **Invocation shape:** four queries submitted in one invocation with
  `response_length: long`.
- **Filters:** no recency, domain or language filter supplied.
- **Locale:** no explicit locale supplied.
- **Date range:** none supplied.
- **Sort order:** not exposed.
- **Result limit:** not exposed.
- **Result counts:** not exposed by query.
- **Underlying provider and ranking configuration:** not exposed.
- **Complete ranked result sets:** not exposed or captured.
- **Execution identifier:** no durable tool-run identifier was exposed.

The query strings and selected durable links below are reproducible inputs and
selection provenance. The returned result set and ordering are not
reproducible from this record.

### Exact queries

1. `cross lifecycle integration systems engineering objective decision implementation operation learning standard`
2. `digital thread decision rationale operational feedback lifecycle standard implementation`
3. `model based systems engineering enterprise architecture DevOps integration lifecycle case study`
4. `digital thread implementation failure adoption burden maintenance empirical study`

### Query intent

| Query | Primary purpose | Strategy families |
| --- | --- | --- |
| 1 | Seek a named or standardised lifecycle-wide approach capable of making C-003 unnecessary. | F-01, F-03 |
| 2 | Seek digital-thread practice that includes decisions, reasoning and operational feedback rather than artifact connectivity alone. | F-01, F-03, F-05 |
| 3 | Seek deliberate compositions of MBSE, enterprise architecture and DevOps with inspectable implementation. | F-02, F-03, F-09 |
| 4 | Seek adoption, maintenance, burden and failure evidence from the first execution round. | F-10 |

## Retained candidates

Retention means the source appears eligible for later inspection. It does not
mean that its claims are accurate, that it satisfies N-01 through N-06 or that
it bears in any direction on C-003.

### R2-CAND-001

- **Title:** *Digital Engineering Models of Complex Systems using Model-Based
  Systems Engineering (MBSE) from Enterprise Architecture (EA) to Systems of
  Systems (SoS) Architectures & Systems Development Life Cycle (SDLC)*.
- **Authors visible during triage:** Roy Tsui, Devin Davis and John Sahlin.
- **Publication lead:** INCOSE International Symposium, 2018.
- **Durable identifier:** https://doi.org/10.1002/j.2334-5837.2018.00514.x
- **Discovery query:** 1.
- **Candidate family:** F-02/F-03; possible deliberate EA-to-MBSE mapping.
- **Selection reason:** the accessible record describes mappings from
  enterprise-architecture views into systems-of-systems models and lifecycle
  traceability, making it a plausible established-composition candidate.
- **Triage limit:** no N-01–N-06 mapping, outcome inference or source appraisal
  has been performed.

### R2-CAND-002

- **Title:** *MBSE delivers significant return on investment in evolutionary
  development of complex SoS*.
- **Publication lead:** *Systems Engineering*, 2021.
- **Durable identifier:** https://doi.org/10.1002/sys.21592
- **Discovery query:** 3.
- **Candidate family:** F-03; bounded implementation and outcome lead.
- **Selection reason:** the result describes an implemented MBSE methodology
  covering requirements, architecture, design, analysis, verification and
  validation in an evolving system-of-systems programme and reports an ROI
  evaluation.
- **Triage limit:** the result does not establish decision reasoning,
  operational learning, maintained coverage or the validity of reported
  outcomes.

### R2-CAND-003

- **Title:** *MBSE adoption experiences in organizations: Lessons learned*.
- **Publication lead:** *Systems Engineering*, 2024.
- **Durable identifier:** https://doi.org/10.1002/sys.21717
- **Discovery query:** 4.
- **Candidate family:** F-10; adoption, maintenance and burden lead.
- **Selection reason:** the result describes synthesis of published case
  studies and practitioner interviews about organisational MBSE adoption,
  including stakeholder participation and lifecycle reuse concerns.
- **Triage limit:** publication method, population, findings and relevance to
  the construct require primary-source appraisal.

### R2-CAND-004

- **Title:** *Scalable, Flexible Implementation of MBSE and DevOps in VSEs:
  Design Considerations and a Case Study*.
- **Authors visible during triage:** Cailin Simpson and Steven Simske.
- **Durable identifier:** https://doi.org/10.1002/iis2.13069
- **Discovery query:** 3.
- **Candidate family:** F-09/F-10; deliberate composition and proportionality
  lead.
- **Selection reason:** the accessible metadata describes a reduced composition
  of MBSE and DevOps for very small entities and explicitly raises full-scale
  implementation burden.
- **Triage limit:** only secondary metadata was accessible during this round;
  primary publication identity, method and case details require verification.

## Deferred leads

Deferred leads may be revisited in the appropriate family. They are not
registered evidence and are not silently excluded.

| ID | Lead | Stable URL | Reason deferred |
| --- | --- | --- | --- |
| R2-DEF-001 | *Analysis for an End-to-End MBSE Operational Architecture* | https://openaccess.cms-conferences.org/publications/book/978-1-964867-96-0/article/978-1-964867-96-0_3 | The result proposes a synthesised reference architecture and describes later executable validation as future work. Primary metadata and its value as definition rather than implementation evidence require inspection. |
| R2-DEF-002 | Fraunhofer IPK MBSE practice and railway case description | https://www.ipk.fraunhofer.de/en/expertise-and-technologies/digital-engineering/model-based-systems-engineering.html | Authoritative research-organisation page and implementation lead, but the returned page is partly service description and did not expose an independent study identifier. |
| R2-DEF-003 | HCLTech MBSE–PLM aerospace case study | https://www.hcltech.com/case-study/advancing-aerospace-engineering-through-mbse-plm-digital-convergence | Potential F-09 implementation lead, but it is vendor-authored and cannot independently establish sufficiency or outcomes. Search later for customer or primary corroboration. |
| R2-DEF-004 | *Why technology implementation fails: from adoption to dynamic technology integration* | https://doi.org/10.1080/1359432X.2026.2684522 | Potential F-10 alternative-explanation source, but it is general technology integration rather than a selected lifecycle approach. Revisit during the dedicated burden/failure family. |

## Excluded results

Exclusion is from this round's candidate set, not a judgement about the source's
quality or its value for its intended purpose.

| ID | Result | URL | Exclusion reason |
| --- | --- | --- | --- |
| R2-EXC-001 | CDIO Standards 2.1 | https://www.cdio.org/content/cdio-standard-21 | The result uses a Conceive–Design–Implement–Operate lifecycle but governs engineering education and curriculum outcomes, not the organisational engineering-memory practice under investigation. Retain its vocabulary only as a search lead. |
| R2-EXC-002 | IEEE Technology Navigator: System Integration | https://technav.ieee.org/topic/system-integration/ | Aggregated topic page rather than an authoritative standard text or primary study. The referenced ISO/IEC/IEEE standards remain future direct-search leads. |
| R2-EXC-003 | Wikipedia pages for MBSE, system integration, Arcadia, ISO 15926 and MBASE | https://www.wikipedia.org/ | Discovery summaries are not eligible evidence and were not needed where direct authoritative or primary searches can be run. |
| R2-EXC-004 | Recent DevOps/MLOps trade-press articles | https://www.techradar.com/ and https://www.itpro.com/ | Vendor and trade commentary outside the selected R-002 unit and without independently inspectable evidence. |
| R2-EXC-005 | Recent arXiv results on health-AI adoption and DevOps-pipeline digital twins | https://arxiv.org/ | Query-term matches did not address the selected cross-lifecycle unit closely enough for this round; no inference was drawn from exclusion. |

## Access limitations

- The search interface did not expose complete result sets, result counts,
  ranking configuration, underlying provider or a durable run identifier.
- Publisher pages for R2-CAND-002 and R2-CAND-003 returned through search but
  did not render through the subsequent page-opening interface.
- R2-CAND-004 was available through secondary metadata; its primary publisher
  record was not inspected.
- One deferred conference page returned an opening error after appearing in
  search results.
- Paywall, authentication, language and database-index coverage were not tested
  systematically in this round.
- No claim is made that the candidates are the strongest versions of their
  source families.

## Citation chaining

No backward or forward citation chaining was performed. The round was limited
to initial discovery and durable-identity triage. Citation chaining remains
required for eligible cornerstone sources under the approved stopping rules.

## Family coverage after Round 001

| Family | Round 001 state | Note |
| --- | --- | --- |
| F-01 — Named cross-lifecycle approaches | Initial search executed | No candidate has been classified as lifecycle-wide coverage. |
| F-02 — Enterprise architecture and governance | Touched, not yet dedicated | One EA-to-MBSE candidate retained. |
| F-03 — Systems engineering, MBSE and lifecycle management | Initial search executed | Three MBSE-related candidates retained; no appraisal performed. |
| F-04 — Traceability and impact analysis | Not searched directly | Future round required. |
| F-05 — Decisions, rationale and provenance | Touched, not yet dedicated | Query vocabulary used; no selected direct candidate. |
| F-06 — Organisational memory and knowledge management | Not searched | Future round required. |
| F-07 — Semantic and graph-based integration | Not searched | Future round required. |
| F-08 — DevOps, SRE and operational learning | Touched through composition query | No dedicated search completed. |
| F-09 — Deliberate compositions | Initial search executed | MBSE–DevOps and EA-to-MBSE composition leads retained. |
| F-10 — Adoption, burden and harmful integration | Initial search executed | One adoption candidate retained and one general source deferred. |

## Stopping-rule position

No stopping rule is satisfied by this round alone. Eight families still require
dedicated or additional searching, no cornerstone source has undergone citation
chaining, no two-round diminishing-return test exists and the Evidence Reviewer
has not reviewed search completeness.

## Round boundary

Round 001 records discovery and source-selection provenance only. It does not:

- register an evidence record;
- appraise a source;
- map any candidate against N-01 through N-06;
- assign defined, implemented, maintained or outcome-supported coverage;
- assign supporting, conflicting, contextual or inconclusive direction;
- change C-003 or C-005;
- assign confidence or disposition;
- perform independent evidence review;
- authorise Stage B; or
- introduce OME terminology, canon or product material.

## Corrections

None recorded.
