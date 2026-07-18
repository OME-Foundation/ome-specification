# R-002 Stage A search log

Status: Stage A in progress; Search Rounds 001 and 002 recorded. Candidate
selection only—no evidence registration, appraisal, coverage classification or
claim assessment.

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
| R2-EXC-003 | *ISO/IEC 12207* | https://en.wikipedia.org/wiki/ISO/IEC_12207 | Wikipedia discovery summary is not eligible evidence; search the issuing standard directly. |
| R2-EXC-004 | *Model-based systems engineering* | https://en.wikipedia.org/wiki/Model-based_systems_engineering | Wikipedia discovery summary is not eligible evidence; direct authoritative and primary sources are searchable. |
| R2-EXC-005 | *System integration* | https://en.wikipedia.org/wiki/System_integration | Wikipedia discovery summary is not eligible evidence; direct standards remain future search leads. |
| R2-EXC-006 | *Arcadia (engineering)* | https://en.wikipedia.org/wiki/Arcadia_(engineering) | Wikipedia discovery summary is not eligible evidence; search the method's authoritative documentation directly. |
| R2-EXC-007 | *ISO 15926* | https://en.wikipedia.org/wiki/ISO_15926 | Wikipedia discovery summary is not eligible evidence; search the issuing standard directly. |
| R2-EXC-008 | *MBASE* | https://en.wikipedia.org/wiki/MBASE | Wikipedia discovery summary is not eligible evidence; direct primary or authoritative sources are searchable. |
| R2-EXC-009 | *Breaking silos: unifying DevOps and MLOps into a unified software supply chain* | https://www.techradar.com/pro/breaking-silos-unifying-devops-and-mlops-into-a-unified-software-supply-chain | Trade commentary outside the selected R-002 unit and without independently inspectable evidence. |
| R2-EXC-010 | *Breaking boundaries: Empowering channel partners to unite DevOps and MLOps for a stronger software supply chain* | https://www.itpro.com/software/development/breaking-boundaries-empowering-channel-partners-to-unite-devops-and-mlops-for-a-stronger-software-supply-chain | Trade commentary outside the selected R-002 unit and without independently inspectable evidence. |
| R2-EXC-011 | *The partial adoption trap: Coordination failure, trust, and cultural lock-in in health AI adoption* | https://arxiv.org/abs/2605.17388 | Query-term match did not address the selected cross-lifecycle unit closely enough for this round; no inference was drawn from exclusion. |
| R2-EXC-012 | *A Model-Driven Digital Twin for the Systematic Improvement of DevOps Pipelines* | https://arxiv.org/abs/2604.02077 | Query-term match concerned a DevOps-pipeline model rather than the selected organisational cross-lifecycle unit; no inference was drawn from exclusion. |

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

All ten families remain incomplete against the Stage A stopping rules. Six have
not yet received a dedicated search; F-01, F-03, F-09 and F-10 have only
initial coverage and still require an independent discovery route and the
required searches for sufficient practice, implemented use, limitations and
competing explanations. No cornerstone source has undergone citation chaining,
no two-round diminishing-return test exists and the Evidence Reviewer has not
reviewed search completeness.

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

## CTO Independent Search-Round Review

Status: complete.

- **Execution scope:** approved. The round is limited to the immutable search
  log, exact queries, execution context, candidate selection, exclusions,
  access limitations, family coverage and stopping-rule position.
- **Excluded-result provenance:** approved after correction. Each previously
  aggregated Wikipedia, trade-press and arXiv result now has its own local
  identifier, exact title and exact returned URL.
- **Stopping-rule fidelity:** approved after correction. All ten families remain
  incomplete; six lack a dedicated search and F-01, F-03, F-09 and F-10 have
  initial coverage only.
- **Reproducibility limits:** approved. Hidden provider, ranking, result counts,
  complete result sets and execution identifier remain explicitly disclosed.
- **Research boundary:** approved. No evidence registration or promotion,
  appraisal, N-01–N-06 mapping, coverage classification, evidential direction,
  confidence, claim assessment or Stage B work has entered the round.
- **Independent decision:** approve PR #20.
- **Required corrections:** none remaining.

## Accountable decision

Status: approved by the founder on 2026-07-18 through the merge decision for
[PR #20](https://github.com/OME-Foundation/ome-specification/pull/20).

The accountable decision accepts Search Round 001 as an execution and
provenance record. It does not register or appraise evidence, classify an
approach, change C-003 or C-005, assign confidence or authorise Stage B.

## Search Round 002

### Round record

- **Round ID:** R2-A-002.
- **Execution date:** 2026-07-18.
- **Research Lead:** repository execution agent (Codex).
- **Purpose:** extend dedicated discovery into traceability, decision and
  rationale provenance, organisational memory and knowledge management, and
  semantic or graph-based lifecycle integration; begin required citation-
  chaining attempts for Round 001 MBSE candidates.
- **Mandatory families targeted:** F-04, F-05, F-06 and F-07.
- **Secondary families touched:** F-01 and F-08 through digital-thread and
  operational-feedback vocabulary.
- **Public/private boundary:** public-source discovery only; no ContextBridge,
  customer, commercial or private product information used.

### Search invocation

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
- **Complete ranked result sets:** not exposed or captured; the returned tool
  output was truncated.
- **Execution identifier:** no durable tool-run identifier was exposed.

The exact inputs and selected durable links are recorded. The returned result
set and ordering are not reproducible from this record.

### Exact queries

1. `requirements traceability operational feedback learning decision rationale empirical lifecycle primary study`
2. `decision provenance architecture rationale implementation operation lessons learned primary study`
3. `organizational memory knowledge management engineering lifecycle decisions operations learning empirical`
4. `engineering knowledge graph semantic digital thread lifecycle traceability operational feedback case study`

### Query intent

| Query | Primary purpose | Strategy families |
| --- | --- | --- |
| 1 | Seek traceability that connects requirements or intent to operation and learning rather than development artifacts alone. | F-04, F-08 |
| 2 | Seek decision, rationale and provenance mechanisms spanning design-time and run-time effects. | F-05 |
| 3 | Seek organisational-memory and knowledge-management practice connected to engineering lifecycles and decisions. | F-06 |
| 4 | Seek semantic knowledge-graph or digital-thread practice with operational feedback and an inspectable case. | F-07, F-01 |

## Round 002 retained candidates

Retention is triage only. No candidate has been appraised, mapped to N-01
through N-06, assigned a coverage level or registered as evidence.

### R2-CAND-005

- **Title:** *Standards-Based Digital Thread as Authoritative Source of Truth*.
- **Authors visible during triage:** Chris C. Gorringe, Eric Gould and Ion Neag.
- **Publication lead:** IEEE Systems Council paper page.
- **Stable URL:** https://ieeesystemscouncil.org/media/standards-based-digital-thread-authoritative-source-truth
- **Discovery query:** 4.
- **Candidate family:** F-01/F-04/F-07; standards-based digital-thread case.
- **Selection reason:** the returned abstract describes integration of product,
  test, diagnostic and sustainment engineering and traceability from
  engineering databases into test results and diagnostic reasoning.
- **Triage limit:** publication identity, case method, maintenance, governance
  and organisational use require primary-source inspection.

### R2-CAND-006

- **Title:** *Improving the Organisational Memory by recording decision making,
  rationale and team configuration*.
- **Authors visible during triage:** Matías Alvarado, René Bañares-Alcántara and
  Alfredo Trujillo.
- **Publication lead:** *Journal of Petroleum Science and Engineering*, 2005.
- **Durable identifier:** https://doi.org/10.1016/j.petrol.2004.11.009
- **Discovery query:** 3.
- **Candidate family:** F-05/F-06; organisational memory with decision rationale
  and evolving workflow.
- **Selection reason:** the returned primary record describes an organisational-
  memory architecture representing workflow, participant profiles, decision
  rationale and reuse for planning, decisions and process optimisation.
- **Triage limit:** the result describes an architecture and intended
  deployment; implementation, maintained use and outcomes are unverified.

### R2-CAND-007

- **Title:** *Decision Provenance: Harnessing data flow for accountable
  systems*.
- **Authors visible during triage:** Jatinder Singh, Jennifer Cobbe and Chris
  Norval.
- **Stable identifier:** https://arxiv.org/abs/1804.05741
- **Discovery query:** 2.
- **Candidate family:** F-05; decision-provenance definition and proposed
  accountability mechanism.
- **Selection reason:** the returned record defines provenance across design-
  time and run-time decision pipelines and their flow-on effects.
- **Triage limit:** the record appears conceptual; implementation and lifecycle
  breadth require appraisal against the primary publication.

### R2-CAND-008

- **Title:** *A closed-loop design approach based on the combination of
  knowledge graph and digital twin: a high-speed train bogie case study*.
- **Publication lead:** *Advanced Engineering Informatics*, 2026.
- **Durable identifier:** https://doi.org/10.1016/j.aei.2025.103912
- **Discovery query:** 4.
- **Candidate family:** F-07/F-09; knowledge-graph and digital-twin composition.
- **Selection reason:** the primary abstract describes closed-loop lifecycle
  feedback, semantic association and dynamic updating in a bounded engineering
  case.
- **Triage limit:** decision reasoning, governance, maintained use and outcomes
  have not been inspected.

### R2-CAND-009

- **Title:** *An Extended Knowledge Management Framework During the Software
  Development Life Cycle*.
- **Authors visible during triage:** Ali A. Alawneh, Ezz Hattab and Walid
  Al-Ahmad.
- **Publication lead:** *International Journal of Information Technology and
  Management Review*, 2008.
- **Durable identifier:** https://doi.org/10.2991/itmr.2008.1.2.4
- **Discovery query:** 3.
- **Candidate family:** F-06; proposed composition of knowledge-management and
  software-development lifecycles.
- **Selection reason:** the returned publisher record describes a framework
  integrating five knowledge types, five software-development phases and the
  knowledge-management lifecycle.
- **Triage limit:** the framework's relationship semantics, evidence basis,
  operation and learning coverage require appraisal.

### R2-CAND-010

- **Title:** *Architecture Decision Records in Practice: An Action Research
  Study*.
- **Publication lead:** ECSA 2024, LNCS 14889.
- **Durable identifier:** https://doi.org/10.1007/978-3-031-70797-1_22
- **Discovery query:** 2.
- **Candidate family:** F-05/F-10; implemented rationale practice, adoption and
  burden lead.
- **Selection reason:** the returned institutional record describes a three-
  month action-research study of ADR adoption, documentation culture,
  knowledge transfer, repository placement and distributed-system limits.
- **Triage limit:** it may remain a bounded decision-record practice rather
  than cross-lifecycle integration; full appraisal is required.

### R2-CAND-011

- **Title:** *Knowledge Management in Software Engineering: A Systematic Review
  of Studied Concepts, Findings and Research Methods Used*.
- **Stable identifier:** https://arxiv.org/abs/1811.12278
- **Discovery query:** 3.
- **Candidate family:** F-06; review and vocabulary source.
- **Selection reason:** the returned record identifies empirical studies of
  knowledge-management initiatives in software engineering and may locate
  stronger primary candidates.
- **Triage limit:** primary publication identity, review method and included
  studies require verification before use or citation chaining.

### R2-CAND-012

- **Title:** *Linking knowledge management, organizational learning and
  memory*.
- **Publication lead:** *Journal of Innovation & Knowledge*, 2020.
- **Durable identifier:** https://doi.org/10.1016/j.jik.2019.04.002
- **Discovery query:** 3.
- **Candidate family:** F-06; systematic conceptual synthesis.
- **Selection reason:** the returned open primary record reports a literature
  review linking knowledge management, organisational learning and memory.
- **Triage limit:** the result may establish vocabulary and adjacency rather
  than engineering lifecycle integration.

## Round 002 deferred leads

| ID | Lead | Exact URL | Reason deferred |
| --- | --- | --- | --- |
| R2-DEF-005 | *Using LLMs in Generating Design Rationale for Software Architecture Decisions* | https://doi.org/10.1145/3785010 | Recent direct rationale-generation study, but the query result does not establish cross-lifecycle use; revisit in F-05 appraisal discovery. |
| R2-DEF-006 | *Implementation feedback of the IVOA Provenance data model* | https://arxiv.org/abs/2007.08615 | Implementation and burden lead for dataset provenance, but its astronomy-data scope is narrower than the selected organisational lifecycle unit. |
| R2-DEF-007 | *Organizational Learning, Knowledge Management Practices and Firm's Performance: An Empirical Study of a Heavy Engineering Firm in India* | https://eric.ed.gov/?id=EJ1054354 | Empirical organisational-learning lead in engineering, but the returned record does not connect its measures to lifecycle relationships. |
| R2-DEF-008 | *Mapping knowledge management and organizational learning in support of organizational memory* | https://www.sciencedirect.com/science/article/abs/pii/S0925527309001765 | Case-based organisational-memory lead; durable publication identity and exact relevance require inspection. |
| R2-DEF-009 | *Building a Manufacturing Digital Thread using Graph and Generative AI on AWS* | https://aws.amazon.com/blogs/industries/building-a-manufacturing-digital-thread-using-graph-and-generative-ai-on-aws/ | Concrete graph implementation lead, but vendor-authored and not independent evidence of sufficiency or outcomes. |
| R2-DEF-010 | *Enabling Connections in the Product Lifecycle* | https://vtechworks.lib.vt.edu/bitstream/handle/10919/85627/Hedberg_TD_D_2018.pdf | Potential primary digital-thread dissertation surfaced through query 4; metadata, scope and stable repository record require verification. |

## Round 002 excluded results

Each returned item is preserved individually. Exclusion is from this round's
candidate set, not a source-quality judgement.

| ID | Result | Exact URL | Exclusion reason |
| --- | --- | --- | --- |
| R2-EXC-013 | *Digital Thread Knowledge Graphs* | https://www.envisioning.com/research/quadrant/digital-thread-graph | Trend and market description without an inspectable primary implementation study. |
| R2-EXC-014 | *Semantics-First Digital Thread: Linking Requirements, Models, and Tests for Traceable Engineering* | https://novedge.com/blogs/design-news/semantics-first-digital-thread-linking-requirements-models-and-tests-for-traceable-engineering | Commercial blog post making broad lifecycle claims without independent evidence. |
| R2-EXC-015 | *Organizational memory* | https://en.wikipedia.org/wiki/Organizational_memory | Wikipedia discovery summary; direct primary and authoritative sources are searchable. |
| R2-EXC-016 | *Digital thread* | https://en.wikipedia.org/wiki/Digital_thread | Wikipedia discovery summary; direct standards and primary research are searchable. |
| R2-EXC-017 | *Corporate amnesia* | https://en.wikipedia.org/wiki/Corporate_amnesia | Wikipedia discovery summary and not a selected engineering-lifecycle unit. |
| R2-EXC-018 | *Federated digital thread* | https://en.wikipedia.org/wiki/Federated_digital_thread | Wikipedia discovery summary; search primary standards and implementation reports directly. |
| R2-EXC-019 | *Organizational learning* | https://en.wikipedia.org/wiki/Organizational_learning | Wikipedia discovery summary; primary organisational-learning sources are searchable. |
| R2-EXC-020 | *Architectural decision* | https://en.wikipedia.org/wiki/Architectural_decision | Wikipedia discovery summary; direct architecture-decision research is searchable. |
| R2-EXC-021 | *A New Model for the Organizational Knowledge Life Cycle* | https://arxiv.org/abs/0705.1084 | Abstract-level theoretical graph model did not provide a sufficiently close engineering lifecycle unit for this round; no inference was drawn. |

## Round 002 access and reproducibility limitations

- The search interface did not expose per-query result counts, ranking,
  underlying provider, complete result sets or a durable execution identifier.
- The returned search output was truncated, so this log cannot represent the
  complete visible result set.
- Publisher or full-text access was not tested for every candidate.
- Several primary records were discoverable only through repositories or
  institutional metadata during triage.
- Search-engine result text supports candidate selection only, not appraisal.
- No claim is made that retained candidates are the strongest versions of their
  families.

## Citation-chaining attempts

Citation chaining was attempted but not completed.

### R2-CHAIN-001 — R2-CAND-001

- **Seed DOI:** https://doi.org/10.1002/j.2334-5837.2018.00514.x
- **Forward/backward graph interface attempted:** OpenAlex Works API.
- **Exact endpoints attempted:**
  - `https://api.openalex.org/works/https://doi.org/10.1002/j.2334-5837.2018.00514.x`
  - `https://api.openalex.org/works/doi:10.1002/j.2334-5837.2018.00514.x`
- **Outcome:** the browsing interface rejected both URL forms as unsafe before
  an OpenAlex response was retrieved.
- **Fallback attempted:** the accessible ResearchGate publication record's
  `Citations (11)` and `References (18)` links.
- **Fallback outcome:** both link fetches failed with a cache miss; no citing or
  referenced source was selected.
- **Status:** incomplete; future independent citation route required.

### R2-CHAIN-002 — R2-CAND-002

- **Seed DOI:** https://doi.org/10.1002/sys.21592
- **Forward/backward graph interface attempted:** OpenAlex Works API.
- **Exact endpoints attempted:**
  - `https://api.openalex.org/works/https://doi.org/10.1002/sys.21592`
  - `https://api.openalex.org/works/doi:10.1002/sys.21592`
- **Outcome:** the browsing interface rejected both URL forms as unsafe before
  an OpenAlex response was retrieved.
- **Status:** incomplete; future independent citation route required.

No citation-chaining candidate was retained or excluded. Failed interface
access is not counted as satisfying the stopping rule.

## Family coverage after Round 002

| Family | Cumulative state | Note |
| --- | --- | --- |
| F-01 — Named cross-lifecycle approaches | Initial coverage only | Digital-thread candidate added; independent discovery route and evidence modes remain incomplete. |
| F-02 — Enterprise architecture and governance | Touched, not yet dedicated | Round 001 EA-to-MBSE lead remains; dedicated governance search required. |
| F-03 — Systems engineering, MBSE and lifecycle management | Initial coverage only | Citation chaining attempted for two candidates but not completed. |
| F-04 — Traceability and impact analysis | Initial coverage only | Dedicated query executed; no candidate is classified as full lifecycle coverage. |
| F-05 — Decisions, rationale and provenance | Initial coverage only | Decision-provenance, organisational-memory rationale and ADR candidates retained. |
| F-06 — Organisational memory and knowledge management | Initial coverage only | Framework and review candidates retained; no appraisal performed. |
| F-07 — Semantic and graph-based integration | Initial coverage only | Digital-thread and closed-loop graph candidates retained; no appraisal performed. |
| F-08 — DevOps, SRE and operational learning | Touched, not yet dedicated | Operational-feedback vocabulary used; dedicated search required. |
| F-09 — Deliberate compositions | Initial coverage only | Knowledge-graph/digital-twin candidate added; no composition mapped. |
| F-10 — Adoption, burden and harmful integration | Initial coverage only | ADR adoption and earlier MBSE adoption leads retained; evidence modes remain incomplete. |

## Round 002 stopping-rule position

All ten families remain incomplete against the Stage A stopping rules. F-02 and
F-08 have not received dedicated searches. The other eight have initial
coverage only and still require independent discovery routes and the required
searches for sufficient practice, implemented use, limitations and competing
explanations. Citation chaining was attempted but not completed, no two-round
diminishing-return test is satisfied and the Evidence Reviewer has not reviewed
search completeness.

## Round 002 boundary

Search Round 002 adds execution and source-selection provenance only. It does
not:

- register or appraise evidence;
- map a candidate to N-01 through N-06;
- assign a coverage level or evidential direction;
- change C-003 or C-005;
- assign confidence or disposition;
- complete a citation chain or stopping rule;
- authorise Stage B; or
- introduce OME terminology, canon or product material.

## Round 002 corrections

None recorded.

## CTO Independent Search-Round Review — Round 002

Status: pending.

## Accountable decision — Round 002

Status: pending founder approval after independent review.
