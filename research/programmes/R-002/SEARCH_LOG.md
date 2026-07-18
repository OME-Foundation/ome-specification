# R-002 Stage A search log

Status: Stage A in progress; Search Rounds 001 through 004 recorded. Candidate
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
- **Meaning of targeted:** this round intentionally executed discovery for
  these families. Targeting does not indicate that any family's Stage A
  stopping conditions have been satisfied.
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

Status: complete.

- **Execution scope:** approved. Round 002 appends search execution,
  source-selection provenance, access limitations, family coverage and
  stopping-rule state without entering evidence appraisal or claim assessment.
- **Family targeting:** approved after clarification. `Targeted` records that a
  round intentionally searched a family; it does not imply that the family's
  Stage A stopping conditions are satisfied.
- **Candidate provenance:** approved. Retained, deferred and excluded records
  remain individually identified and separate from Evidence Register records.
- **Citation chaining:** approved. Failed OpenAlex and publication-record
  attempts are preserved without being represented as completed chains.
- **Stopping-rule fidelity:** approved. All ten families remain incomplete,
  with F-02 and F-08 lacking dedicated searches and the other eight at initial
  coverage only.
- **Research boundary:** approved. No evidence registration or appraisal,
  N-01–N-06 mapping, coverage level, evidential direction, confidence, claim
  assessment or Stage B authority has entered the round.
- **Independent decision:** approve PR #21.
- **Required corrections:** none remaining.

## Accountable decision — Round 002

Status: approved by the founder on 2026-07-18 through the merge decision for
[PR #21](https://github.com/OME-Foundation/ome-specification/pull/21).

The accountable decision accepts Search Round 002 as an execution and
provenance record. It does not register or appraise evidence, classify an
approach, change C-003 or C-005, assign confidence or authorise Stage B.

## Search Round 003

### Round record

- **Round ID:** R2-A-003.
- **Execution date:** 2026-07-18.
- **Research Lead:** repository execution agent (Codex).
- **Purpose:** perform dedicated F-02 and F-08 discovery, introduce Crossref as
  an independent scholarly-metadata route, and renew forward and backward
  citation chaining for R2-CAND-001 and R2-CAND-002.
- **Mandatory families targeted:** F-02 and F-08.
- **Meaning of targeted:** this round intentionally executed discovery for
  these families. Targeting does not indicate that either family's Stage A
  stopping conditions have been satisfied.
- **Secondary families touched:** F-01, F-03, F-04, F-07, F-09 and F-10 through
  citation chaining and candidate overlap.
- **Public/private boundary:** public-source discovery only; no ContextBridge,
  customer, commercial or private product information used.

## Web-search invocation — Round 003

- **Interface:** OpenAI web-search tool exposed to the Codex desktop research
  agent as `web.run`, using its `search_query` operation.
- **Invocation shape:** four queries submitted in one invocation with
  `response_length: long`.
- **Filters:** no recency, domain or language filter supplied.
- **Locale:** no explicit locale supplied.
- **Date range:** none supplied.
- **Sort order, result limit and per-query result count:** not exposed.
- **Underlying provider and ranking configuration:** not exposed.
- **Complete ranked result sets:** not exposed or captured; returned output was
  truncated.
- **Execution identifier:** no durable tool-run identifier was exposed.

### Exact web queries

1. `enterprise architecture governance strategy implementation operations feedback learning empirical case study`
2. `enterprise architecture decision rationale traceability benefits realization operational outcomes framework`
3. `DevOps SRE operational learning incident review architecture decisions requirements feedback empirical study`
4. `site reliability engineering post incident review organizational learning implementation burden case study`

| Query | Primary purpose | Strategy families |
| --- | --- | --- |
| 1 | Seek implemented enterprise-architecture governance connecting strategy, execution and operational feedback. | F-02 |
| 2 | Seek EA decision, traceability and benefit mechanisms with operational outcomes. | F-02, F-05, F-10 |
| 3 | Seek DevOps or SRE feedback from incidents into architecture, requirements or implementation. | F-08 |
| 4 | Seek post-incident learning, adoption and burden evidence. | F-08, F-10 |

## Independent Crossref discovery route

- **Interface:** public Crossref REST API.
- **Client:** PowerShell `Invoke-RestMethod`.
- **Invocation:** two HTTP GET requests, executed after the web searches.
- **Default ordering:** Crossref query relevance; no explicit sort supplied.
- **Rows requested:** five per query.
- **Filter:** `type:journal-article`.
- **Selected fields:** DOI, title, author, published, URL and type.
- **Total result counts and query scores:** available in the API response but
  not retained in the projected execution output.

### Exact Crossref requests

1. `https://api.crossref.org/works?query.title=enterprise%20architecture%20governance%20benefits%20operations%20learning&filter=type:journal-article&rows=5&select=DOI,title,author,published,URL,type`
2. `https://api.crossref.org/works?query.title=site%20reliability%20engineering%20post-incident%20review%20organizational%20learning&filter=type:journal-article&rows=5&select=DOI,title,author,published,URL,type`

The EA query returned R2-CAND-013, which web query 2 also returned, and
R2-CAND-014, which appears only in the recorded Crossref results. The SRE query
was noisy: four of five results concerned book review, automated incident
response or physical reliability rather than organisational learning from
software operations.

## Round 003 retained candidates

Retention remains triage only. Route agreement does not establish source
quality, coverage, evidential direction or relevance to C-003.

### R2-CAND-013

- **Title:** *How enterprise architecture leads to organisational benefits*.
- **Authors from Crossref:** Toomas Tamm, Peter B. Seddon and Graeme Shanks.
- **Durable identifier:** https://doi.org/10.1016/j.ijinfomgt.2022.102554
- **Discovery routes:** web query 2 and Crossref query 1.
- **Candidate family:** F-02/F-10; EA benefit mechanisms and alternatives.
- **Selection reason:** the web result describes a model of three mechanisms
  through which EA contributes to organisational benefits, including improved
  IS decision-making.
- **Triage limit:** method, population, mechanisms and lifecycle breadth require
  primary-source appraisal.

### R2-CAND-014

- **Title:** *Achieving benefits with enterprise architecture*.
- **Authors from Crossref:** Graeme Shanks, Marianne Gloet, Ida Asadi Someh,
  Keith Frampton and Toomas Tamm.
- **Durable identifier:** https://doi.org/10.1016/j.jsis.2018.03.001
- **Discovery route:** Crossref query 1.
- **Candidate family:** F-02/F-10; EA benefit mechanism and implementation lead.
- **Selection reason:** direct title and metadata match the dedicated EA benefit
  search and provide an independent-route candidate.
- **Triage limit:** no abstract or full text was inspected in this round.

### R2-CAND-015

- **Title:** *Enterprise Architecture Best Practices in Large Corporations*.
- **Publisher URL:** https://www.mdpi.com/2078-2489/10/10/293
- **Discovery route:** web query 1.
- **Candidate family:** F-02; multi-case implementation lead.
- **Selection reason:** the returned publisher record describes enterprise-
  wide EA practices in two large organisations and strategy/operations scope.
- **Triage limit:** best-practice labels, case method and outcomes require
  appraisal.

### R2-CAND-016

- **Title:** *Enterprise Architecture Adoption Challenges: An exploratory Case
  Study of the Norwegian Higher Education Sector*.
- **Stable URL:** https://www.sciencedirect.com/science/article/pii/S1877050916323973
- **Discovery route:** web query 1.
- **Candidate family:** F-02/F-10; adoption and implementation boundary lead.
- **Selection reason:** primary publisher result explicitly studies EA adoption
  challenges in a bounded sector.
- **Triage limit:** no outcome, coverage or causal inference has been made.

### R2-CAND-017

- **Title:** *The Role of Institutional Logics in Shaping Architecture
  Governance: A Case Study*.
- **Durable identifier:** https://doi.org/10.5465/ambpp.2016.44
- **Discovery route:** web query 2.
- **Candidate family:** F-02/F-10; governance-mechanism alternative.
- **Selection reason:** the result describes a longitudinal case concerning
  architecture-governance mechanisms in a telecom organisation.
- **Triage limit:** proceedings status, method and relevance require appraisal.

### R2-CAND-018

- **Title:** *Going Beyond an Incident Report with TLA+*.
- **Stable URL:** https://www.usenix.org/publications/loginonline/going-beyond-incident-report-tla
- **Discovery route:** web query 3.
- **Candidate family:** F-08/F-09; post-incident learning and design-method
  composition.
- **Selection reason:** the USENIX case describes applying a design-time formal
  method retrospectively to a 28-day outage.
- **Triage limit:** the source may remain a bounded analysis technique rather
  than maintained organisational learning.

### R2-CAND-019

- **Title:** *Site Reliability Engineering: Incident Management Guide*.
- **Authoritative URL:** https://static.googleusercontent.com/media/sre.google/en//static/pdf/IncidentManagementGuide.pdf
- **Discovery route:** web query 4.
- **Candidate family:** F-08; authoritative practitioner process and vocabulary.
- **Selection reason:** the returned guide connects postmortems, corrective
  actions, trend analysis and sharing across an organisation.
- **Triage limit:** authoritative practice guidance is not evidence of adoption,
  maintained use or outcomes.

### R2-CAND-020

- **Title:** *Case study: the experience of managers: the how of organisational
  learning after patient incidents in a hospital*.
- **Author visible during triage:** Yin Shan Joyce Mok.
- **Repository URL:** https://mro.massey.ac.nz/items/118087df-ccd6-45c8-8de0-a788ef55cad2
- **Discovery route:** web query 4.
- **Candidate family:** F-08; incident-to-organisational-learning case.
- **Selection reason:** the repository abstract describes interviews and
  document analysis across incident investigation and organisational learning.
- **Triage limit:** healthcare context and lack of engineering lifecycle links
  may restrict direct relevance.

### R2-CAND-021

- **Title:** *Organizational Learning Applied to Software Engineering: A
  Systematic Review*.
- **Authors from Crossref:** Andre Menolli, Sheila Reinehr and Andreia
  Malucelli.
- **Durable identifier:** https://doi.org/10.1142/S0218194013500356
- **Discovery route:** Crossref query 2.
- **Candidate family:** F-08/F-06; review and vocabulary lead.
- **Selection reason:** the only Crossref SRE-query result directly concerning
  organisational learning in software engineering.
- **Triage limit:** it was retrieved through a noisy query and requires review-
  method and included-study inspection.

## Citation-chain candidates retained in Round 003

The following were selected from OpenAlex citation metadata because their
titles and durable identifiers suggest material adjacent or competing
approaches. Selection is not appraisal.

| ID | Seed and direction | Candidate | Durable identifier | Triage reason |
| --- | --- | --- | --- | --- |
| R2-CAND-022 | CAND-001 forward | *MBSE-PLM Integration: Initiatives and Future Outlook* | https://doi.org/10.1007/978-3-031-25182-5_17 | Direct deliberate-composition lead. |
| R2-CAND-023 | CAND-001 forward | *A Survey on the Challenges Hindering the Application of Data Science, Digital Twins and Design Automation in Engineering Practice* | https://doi.org/10.1017/pds.2022.172 | Adoption and burden counterposition. |
| R2-CAND-024 | CAND-001 forward | *PLM Traceability Approaches Along the V-Model – A Systematic Literature Review* | https://doi.org/10.1007/978-3-031-93323-3_21 | Traceability and lifecycle review lead. |
| R2-CAND-025 | CAND-002 forward | *Towards Developing Metrics to Evaluate Digital Engineering* | https://doi.org/10.1002/sys.21640 | Outcome and measurement boundary lead. |
| R2-CAND-026 | CAND-002 forward | *Driving digital engineering integration and interoperability through semantic integration of models with ontologies* | https://doi.org/10.1002/sys.21662 | Semantic integration and interoperability lead. |
| R2-CAND-027 | CAND-001 backward | *Digital Thread and Twin for Systems Engineering: Requirements to Design* | https://doi.org/10.2514/6.2017-0875 | Earlier digital-thread lifecycle source. |
| R2-CAND-028 | CAND-002 backward | *Model-based systems engineering: Motivation, current status, and research opportunities* | https://doi.org/10.1002/sys.21438 | Field boundary and limitations source. |
| R2-CAND-029 | CAND-002 backward | *Systematic Literature Review: How is Model-Based Systems Engineering Justified?* | https://doi.org/10.2172/1561164 | Evidence-quality and justification counterposition. |
| R2-CAND-030 | CAND-002 backward | *Transitioning the SWFTS Program Combat System Product Family from Traditional Document-Centric to Model-Based Systems Engineering* | https://doi.org/10.1002/sys.21271 | Predecessor implementation source for the ROI case. |
| R2-CAND-031 | CAND-002 backward | *An operations concept for Integrated Model-Centric Engineering at JPL* | https://doi.org/10.1109/AERO.2010.5446799 | Integrated model-centric composition lead. |

## Round 003 deferred leads

| ID | Lead | Exact URL | Reason deferred |
| --- | --- | --- | --- |
| R2-DEF-011 | PagerDuty engineering post-incident-review case | https://www.pagerduty.com/ops-guides/using-pd/jeli-analysis-engineering-team/ | Concrete implementation and burden claims, but vendor-authored and not independently corroborated. |
| R2-DEF-012 | *From Incidents to Insight: Closing the Post-Incident Review Gap* | https://www.pagerduty.com/eng/from-incidents-to-insight-closing-the-post-incident-review-gap/ | Practitioner vocabulary and product context; not independent evidence. |
| R2-DEF-013 | Scotiabank enterprise-architecture case | https://www.forrester.com/report/case-study-scotiabank-succeeds-with-enterprise-architecture/RES182122 | Potential EA implementation case, but paywalled analyst summary and outcome basis not inspectable in this round. |
| R2-DEF-014 | Adaptive Capacity Labs incident-learning assessment | https://www.adaptivecapacitylabs.com/case-mid-size-e-commerce-business/ | Potential organisational-use case, but consultancy-authored and requires independent corroboration. |
| R2-DEF-015 | *A Theory Building Study of Enterprise Architecture Practices and Benefits* | https://arxiv.org/abs/2008.08112 | Potential synthesis and empirical-gap lead; primary publication identity requires verification. |
| R2-DEF-016 | *Evaluation and Implementation of Site Reliability Engineering* | https://oulurepo.oulu.fi/bitstream/10024/50800/1/nbnfioulu-202406194766.pdf | Bounded implementation thesis; stable repository record and method require inspection. |

## Crossref Round 003 non-selected results

Each result returned in the two five-row projections is preserved below.

| ID | Query | Result | Durable identifier | Disposition reason |
| --- | --- | --- | --- | --- |
| R2-XR-001 | EA | *Enterprise Architecture: Driving Business Benefits from IT* | https://doi.org/10.2139/SSRN.920666 | Deferred: relevant historical lead, but SSRN record type and full publication identity require inspection. |
| R2-XR-002 | EA | *Using Enterprise Architecture to Direct IT Governance* | https://doi.org/10.4028/www.scientific.net/AMR.971-973.2452 | Deferred: direct governance title; method and quality require inspection. |
| R2-XR-003 | EA | *Agentic AI for Modern Enterprise Architecture Governance* | https://doi.org/10.47363/JAICC/ICMLAIDS2026/2026(5)14 | Excluded from this round: recent AI-governance result did not expose an inspectable established-practice basis. |
| R2-XR-004 | SRE | *Enhancing Site Reliability Engineering: Scalable Strategies for Automated Incident Response and System Resilience* | https://doi.org/10.51219/JAIMLD/JAYA-SEHGAL/533 | Excluded: automation and resilience title, not organisational learning or lifecycle feedback. |
| R2-XR-005 | SRE | *Rezension “Site Reliability Engineering”* | https://doi.org/10.1365/S40702-017-0297-2 | Excluded: book review. |
| R2-XR-006 | SRE | *Self-Healing Database Infrastructure: Machine Learning-Driven Incident Response and Autonomous Reliability Engineering* | https://doi.org/10.32628/IJSRST2291349 | Excluded: database automation rather than organisational operational learning. |
| R2-XR-007 | SRE | *Machine Learning Applications for Reliability Engineering: A Review* | https://doi.org/10.3390/SU15076270 | Excluded: physical/general reliability engineering rather than SRE organisational learning. |

R2-CAND-013, R2-CAND-014 and R2-CAND-021 account for the other three returned
Crossref rows.

## Web Round 003 excluded results

| ID | Result | Exact URL | Exclusion reason |
| --- | --- | --- | --- |
| R2-EXC-022 | *Case Study: Enterprise Architecture Principles In Practice* | https://cioindex.com/reference/case-study-enterprise-architecture-implementation-3/ | Aggregated case page without independently inspectable source method. |
| R2-EXC-023 | *Case Study: PNC's Secret To EA Success? A Strong Customer Focus* | https://www.forrester.com/report/case-study-pncs-secret-to-ea-success-a-strong-customer-focus/RES46349 | Analyst case summary without accessible evidence basis in this round. |
| R2-EXC-024 | *EMRGF: A Practitioner Framework for Governance-Driven Enterprise Technology Modernization* | https://arxiv.org/abs/2605.06703 | Self-described practitioner framework with reported outcomes but no independently inspected empirical design. |
| R2-EXC-025 | *Enterprise architecture* | https://en.wikipedia.org/wiki/Enterprise_architecture | Wikipedia discovery summary; direct authoritative and primary sources are searchable. |
| R2-EXC-026 | *Treasury Enterprise Architecture Framework* | https://en.wikipedia.org/wiki/Treasury_Enterprise_Architecture_Framework | Wikipedia discovery summary; search authoritative government records directly. |
| R2-EXC-027 | *Enterprise architecture framework* | https://en.wikipedia.org/wiki/Enterprise_architecture_framework | Wikipedia discovery summary; direct framework specifications are searchable. |
| R2-EXC-028 | *Zachman Framework* | https://en.wikipedia.org/wiki/Zachman_Framework | Wikipedia discovery summary; search authoritative framework sources directly. |
| R2-EXC-029 | *Enterprise Architecture Assessment Framework* | https://en.wikipedia.org/wiki/Enterprise_Architecture_Assessment_Framework | Wikipedia discovery summary; search the issuing government framework directly. |

## OpenAlex citation-chain execution

### Interfaces and client history

1. The direct OpenAlex DOI endpoints previously rejected by the web browsing
   layer in Round 002 were retried through public API clients.
2. PowerShell `Invoke-RestMethod` produced null projected work fields for both
   seeds; `Invoke-WebRequest` then failed locally with a null-reference error.
3. `curl.exe` against the same DOI endpoints succeeded. Client failure is not
   attributed to OpenAlex.

Successful seed endpoints:

- `https://api.openalex.org/works/https://doi.org/10.1002/j.2334-5837.2018.00514.x`
- `https://api.openalex.org/works/https://doi.org/10.1002/sys.21592`

The seed records exposed:

| Seed | OpenAlex ID | Citing count | Reference count |
| --- | --- | --- | --- |
| R2-CAND-001 | W2885317530 | 10 | 7 |
| R2-CAND-002 | W3183735209 | 44 | 26 |

### Forward chaining

Exact executed requests:

- `https://api.openalex.org/works?filter=cites:W2885317530&sort=cited_by_count:desc&per-page=10&select=id,doi,title,publication_year,type,cited_by_count`
- `https://api.openalex.org/works?filter=cites:W3183735209&sort=cited_by_count:desc&per-page=10&select=id,doi,title,publication_year,type,cited_by_count`

Results were explicitly sorted by OpenAlex `cited_by_count:desc`. That ordering
is discovery metadata, not a quality or relevance ranking.

- R2-CAND-001: all 10 exposed citing records retrieved.
- R2-CAND-002: first 10 of 44 exposed citing records retrieved; forward chaining
  remains incomplete.

### Backward chaining

The seed records exposed seven and 26 OpenAlex reference identifiers. Each full
identifier set was requested in one `openalex_id` OR-filter with `per-page=50`
and selected fields `id,doi,title,publication_year,type,cited_by_count`.

- R2-CAND-001: all seven exposed reference records retrieved.
- R2-CAND-002: all 26 exposed reference records retrieved.

The exact identifier sets were:

- **R2-CAND-001:** `W1994690836|W2485774103|W2488756085|W2492678393|W2496634487|W2498975601|W2569913488`
- **R2-CAND-002:** `W1495459766|W1550605309|W1605784959|W1873039666|W1998736027|W2004230907|W2008856128|W2058107586|W2062314620|W2075554387|W2111221180|W2123268828|W2127394476|W2469575695|W2503540216|W2527539869|W2550751448|W2754350468|W2766273739|W2779156691|W2800829932|W2810225942|W2896117780|W2916788648|W2971612533|W4255132591`

The request form was:

`https://api.openalex.org/works?filter=openalex_id:<pipe-separated-identifiers>&per-page=50&select=id,doi,title,publication_year,type,cited_by_count`

### Citation-chain status

- **R2-CHAIN-001:** forward and backward retrieval complete for the current
  OpenAlex graph snapshot; source appraisal and relevance review not begun.
- **R2-CHAIN-002:** backward retrieval complete; forward retrieval partial at
  10 of 44. Further pages remain required.

Completion describes retrieval from one citation graph, not comprehensive
scholarly citation coverage.

## Round 003 access and reproducibility limitations

- Web result sets, counts, ranking and provider remain unavailable; returned
  output was truncated.
- Crossref returned only the requested top five relevance-ranked metadata rows
  per query; total-result metadata was not retained in the projected output.
- OpenAlex is a mutable scholarly graph; counts and membership may change after
  the recorded date.
- OpenAlex citation metadata can contain irrelevant or misclassified records;
  selection does not validate a citation's substantive relationship.
- No full text was appraised and no citation-chain candidate was registered as
  evidence.
- Language, paywall and database-index coverage remain incomplete.

## Family coverage after Round 003

| Family | Cumulative state | Note |
| --- | --- | --- |
| F-01 — Named cross-lifecycle approaches | Initial coverage only | Digital-thread and integrated-engineering leads; evidence modes incomplete. |
| F-02 — Enterprise architecture and governance | Initial coverage through two routes | Dedicated web and Crossref routes executed; appraisal and evidence modes incomplete. |
| F-03 — Systems engineering, MBSE and lifecycle management | Initial coverage only | One seed chain complete in OpenAlex; second forward chain partial. |
| F-04 — Traceability and impact analysis | Initial coverage only | Additional PLM traceability lead found through citation chaining. |
| F-05 — Decisions, rationale and provenance | Initial coverage only | No new dedicated route in this round. |
| F-06 — Organisational memory and knowledge management | Initial coverage only | No new dedicated route in this round. |
| F-07 — Semantic and graph-based integration | Initial coverage only | Ontology semantic-integration lead found through citation chaining. |
| F-08 — DevOps, SRE and operational learning | Initial coverage through two routes | Dedicated web and Crossref routes executed; Crossref route was materially noisy. |
| F-09 — Deliberate compositions | Initial coverage only | MBSE-PLM and model-centric-engineering leads added. |
| F-10 — Adoption, burden and harmful integration | Initial coverage only | EA and incident-learning adoption/burden leads added. |

## Round 003 stopping-rule position

All ten families remain incomplete. Every family has now received at least one
intentional search, but most still depend on one discovery interface and none
has complete searches across sufficient practice, implemented use, limitations
and competing explanations. One OpenAlex seed chain is retrieved completely for
the current graph snapshot; the second remains partial. New approach families
and comparison dimensions were found, so the two-round diminishing-return rule
is not satisfied. The Evidence Reviewer has not reviewed search completeness.

## Round 003 boundary

Search Round 003 adds discovery, metadata and citation-chain provenance only.
It does not:

- register or appraise evidence;
- map a candidate to N-01 through N-06;
- assign a coverage level or evidential direction;
- treat route agreement or citation count as source quality;
- change C-003 or C-005;
- assign confidence or disposition;
- satisfy the Stage A stopping rules;
- authorise Stage B; or
- introduce OME terminology, canon or product material.

## Round 003 corrections

None recorded.

## CTO Independent Search-Round Review — Round 003

Status: complete.

- **Execution scope:** approved. Round 003 records dedicated F-02 and F-08
  discovery, an independent Crossref route and renewed OpenAlex citation
  chaining without entering evidence appraisal or claim assessment.
- **Crossref provenance:** approved after clarification. R2-CAND-013 is
  explicitly linked to web query 2 and Crossref query 1; R2-CAND-014 is
  explicitly identified as appearing only in the recorded Crossref results.
- **Citation chaining:** approved. Complete and partial OpenAlex retrieval is
  distinguished without treating one graph snapshot as comprehensive citation
  coverage.
- **Candidate provenance:** approved. Retained, deferred and excluded records
  remain triage records rather than Evidence Register entries.
- **Stopping-rule fidelity:** approved. All ten families remain incomplete
  against the approved Stage A stopping rules.
- **Research boundary:** approved. No evidence registration or appraisal,
  N-01–N-06 mapping, coverage level, evidential direction, confidence, claim
  assessment or Stage B authority has entered the round.
- **Independent decision:** approve PR #22.
- **Required corrections:** none remaining.

## Accountable decision — Round 003

Status: approved by the founder on 2026-07-18 through the merge decision for
[PR #22](https://github.com/OME-Foundation/ome-specification/pull/22).

The accountable decision accepts Search Round 003 as an execution and
provenance record. It does not register or appraise evidence, classify an
approach, change C-003 or C-005, assign confidence or authorise Stage B.

## Search Round 004

### Round record

- **Round ID:** R2-A-004.
- **Execution date:** 2026-07-18.
- **Research Lead:** repository execution agent (Codex).
- **Purpose:** add independent discovery, complete the outstanding
  R2-CAND-002 OpenAlex forward chain, and test whether another search round
  produces a new material approach family or comparison dimension.
- **Mandatory families targeted:** F-02, F-03, F-04, F-05, F-08, F-09 and
  F-10.
- **Meaning of targeted:** this round intentionally executed discovery for
  these families. Targeting does not indicate that a family's Stage A stopping
  conditions have been satisfied.
- **Public/private boundary:** public-source discovery only; no ContextBridge,
  customer, commercial or private product information used.

## Web-search invocation — Round 004

- **Interface:** OpenAI web-search tool exposed to the Codex desktop research
  agent as `web.run`, using its `search_query` operation.
- **Invocation shape:** four queries submitted in one invocation with
  `response_length: long`.
- **Filters:** no recency, domain or language filter supplied.
- **Locale and date range:** none supplied.
- **Sort order, result limit and per-query result count:** not exposed.
- **Underlying provider and ranking configuration:** not exposed.
- **Complete ranked result sets:** not exposed or captured; returned output was
  truncated.
- **Execution identifier:** no durable tool-run identifier was exposed.

### Exact web queries

1. `enterprise architecture implementation empirical longitudinal outcomes limitations governance case study`
2. `DevOps SRE post-incident review organizational learning empirical outcomes limitations adoption`
3. `digital thread MBSE PLM lifecycle integration implementation evidence barriers interoperability empirical`
4. `requirements traceability decision rationale provenance operations feedback lifecycle integration systematic review`

| Query | Primary purpose | Strategy families |
| --- | --- | --- |
| 1 | Seek implemented EA, outcomes, limitations and governance. | F-02, F-10 |
| 2 | Seek operational learning, outcomes and adoption limitations. | F-08, F-10 |
| 3 | Seek implemented digital-thread compositions and interoperability barriers. | F-01, F-03, F-09, F-10 |
| 4 | Seek lifecycle traceability, rationale and provenance syntheses. | F-04, F-05, F-09 |

## Semantic Scholar independent route

- **Interface:** public Semantic Scholar Academic Graph API.
- **Client:** `curl.exe`, with JSON projected in PowerShell.
- **Ordering:** API default relevance; no explicit sort supplied.
- **Limit:** ten records per query.
- **Selected fields:** paper ID, title, year, authors, external identifiers,
  Semantic Scholar URL, citation count and open-access-PDF metadata.
- **Authentication:** no API key supplied.

### Exact Semantic Scholar requests

1. `https://api.semanticscholar.org/graph/v1/paper/search?query=enterprise%20architecture%20implementation%20governance%20organizational%20benefits%20empirical&limit=10&fields=paperId,title,year,authors,externalIds,url,citationCount,openAccessPdf`
2. `https://api.semanticscholar.org/graph/v1/paper/search?query=DevOps%20SRE%20post%20incident%20organizational%20learning%20empirical&limit=10&fields=paperId,title,year,authors,externalIds,url,citationCount,openAccessPdf`
3. `https://api.semanticscholar.org/graph/v1/paper/search?query=digital%20thread%20MBSE%20PLM%20lifecycle%20integration%20interoperability%20barriers&limit=10&fields=paperId,title,year,authors,externalIds,url,citationCount,openAccessPdf`
4. `https://api.semanticscholar.org/graph/v1/paper/search?query=requirements%20traceability%20decision%20rationale%20provenance%20operations%20feedback&limit=10&fields=paperId,title,year,authors,externalIds,url,citationCount,openAccessPdf`

Request 1 returned ten projected records from an exposed total of 3,811.
Requests 2 through 4 returned HTTP 429 `Too Many Requests`; no result records
were exposed. A separate header-and-body check of request 2 confirmed the 429
response and the public API's request to wait or obtain an API key. The failed
requests were not represented as completed searches.

## Exact-title Crossref metadata checks

Crossref was used only to obtain durable metadata for candidates already found
through the web or Semantic Scholar routes. Five one-row requests used the
public REST API, default relevance ordering and fields DOI, title, author,
published, URL and type:

1. `https://api.crossref.org/works?query.title=Dynamic%20Enterprise%20Architecture%20Capabilities%20and%20Organizational%20Benefits%3A%20An%20empirical%20mediation%20study&rows=1&select=DOI,title,author,published,URL,type`
2. `https://api.crossref.org/works?query.title=The%20Effect%20of%20Enterprise%20Architecture%20Deployment%20Practices%20on%20Organizational%20Benefits%3A%20A%20Dynamic%20Capability%20Perspective&rows=1&select=DOI,title,author,published,URL,type`
3. `https://api.crossref.org/works?query.title=Enterprise%20Architecture%20and%20Organizational%20Benefits%3A%20A%20Case%20Study&rows=1&select=DOI,title,author,published,URL,type`
4. `https://api.crossref.org/works?query.title=A%20systematic%20literature%20review%20to%20explore%20traceability%20and%20lifecycle%20relationship&rows=1&select=DOI,title,author,published,URL,type`
5. `https://api.crossref.org/works?query.title=Defining%20requirements%20for%20integrating%20information%20between%20design%2C%20manufacturing%2C%20and%20inspection&rows=1&select=DOI,title,author,published,URL,type`

Requests 2 through 5 returned title-matching metadata. Request 1 instead
returned R2-CAND-039's differently titled record, so it did not verify the
Semantic Scholar result and no DOI was assigned from that response.

## Round 004 retained candidates

Retention remains triage only. Titles, abstracts, route agreement and citation
metadata do not establish source quality, lifecycle coverage, evidential
direction or relevance to C-003.

| ID | Candidate | Durable identifier or exact route | Discovery and triage reason |
| --- | --- | --- | --- |
| R2-CAND-032 | *Defining requirements for integrating information between design, manufacturing, and inspection* | https://doi.org/10.1080/00207543.2021.1920057 | Web query 3; NIST-associated experiment across design, manufacturing and inspection reports inability to fully link all required information. |
| R2-CAND-033 | *Testing the Digital Thread in Support of Model-Based Manufacturing and Inspection* | https://pmc.ncbi.nlm.nih.gov/articles/PMC4904719/ | Web query 3; implementation and interoperability lead spanning design, manufacturing and inspection. |
| R2-CAND-034 | *A systematic literature review to explore traceability and lifecycle relationship* | https://doi.org/10.1080/00207543.2020.1771455 | Web query 4; lifecycle-traceability synthesis lead. |
| R2-CAND-035 | *Formalizing the Digital Thread: A Standards-Based MBSE Integration Framework* | https://doi.org/10.1016/j.procs.2026.02.096 | Web query 3; recent standards-based integration concept with a bounded use case and stated tool/data incompatibility limits. |
| R2-CAND-036 | *A Study of Adoption and Effects of DevOps Practices* | https://arxiv.org/abs/2211.09390 | Web query 2; empirical adoption-and-outcomes lead requiring publication and method verification. |
| R2-CAND-037 | *Challenges and solutions when adopting DevSecOps: A systematic review* | https://arxiv.org/abs/2103.08266 | Web query 2; adoption and burden counterposition based on a reported review of 54 studies. |
| R2-CAND-038 | *The Effect of Enterprise Architecture Deployment Practices on Organizational Benefits: A Dynamic Capability Perspective* | https://doi.org/10.3390/su12218902 | Semantic Scholar query 1; Crossref title check supplied the DOI; empirical EA deployment-practice lead. |
| R2-CAND-039 | *Enterprise Architecture and Organizational Benefits: A Case Study* | https://doi.org/10.3390/su12198237 | Semantic Scholar query 1; Crossref title check supplied the DOI; bounded EA benefit case. |
| R2-CAND-040 | *Dynamic Enterprise Architecture Capabilities and Organizational Benefits: An empirical mediation study* | https://www.semanticscholar.org/paper/37fdd45c2f717ac466e357b0b9901210ea7ab49c | Semantic Scholar query 1; retained under the exact graph identifier because Crossref request 1 did not return matching metadata. |
| R2-CAND-041 | *Survey of model-based systems engineering (MBSE): State of practice, perception and aligning academic instructions with industry needs* | https://doi.org/10.1177/09544100251354958 | R2-CAND-002 forward page 2; current-practice and adoption lead. |
| R2-CAND-042 | *Scalable, Flexible Implementation of MBSE and DevOps in VSEs: Design Considerations and a Case Study* | https://doi.org/10.1002/iis2.13069 | R2-CAND-002 forward page 3; deliberate MBSE/DevOps composition and implementation lead. |

## Round 004 deferred and excluded results

| ID | Result | Exact URL | Disposition reason |
| --- | --- | --- | --- |
| R2-DEF-017 | *Digital thread in engineering: Concept, state of art, and enabling framework* | https://www.sciencedirect.com/science/article/abs/pii/S147403462500151X | Review and framework lead, but durable DOI and review method were not exposed in the recorded route. |
| R2-DEF-018 | *Incorporating MBSE Across a PLM managed Digital Thread — Three Real Life Use Cases* | https://www.jstage.jst.go.jp/article/isciesci/66/8/66_309/_article/-char/en | Concrete composition cases, but the visible author affiliation is a PLM vendor and independent corroboration is required. |
| R2-DEF-019 | *Technological challenges and enablers for successful PLM implementation within Engineering to Order industries* | https://strathprints.strath.ac.uk/96721/ | Recent implementation lead whose publication and method require inspection. |
| R2-DEF-020 | *Examining the social aspects of Enterprise Architecture Implementation: A Morphogenetic Approach* | https://arxiv.org/abs/1606.02499 | Social/adoption case lead; primary publication identity and method require verification. |
| R2-EXC-030 | *Seamless integration of CAD in AI based System of Systems Lifecycle Management of Digital Threads* | https://doi.org/10.71015/632vj197 | Recent technical concept; no implemented organisational-practice or outcome basis exposed during triage. |
| R2-EXC-031 | *IDDMBSE: Integrating Data-Driven and Model-Based Systems Engineering for Trusted Autonomous Cyber-Physical Systems* | https://arxiv.org/abs/2606.06727 | System-specific technical integration rather than evidence of maintained organisational lifecycle practice. |
| R2-EXC-032 | *Traceability* | https://en.wikipedia.org/wiki/Traceability | Wikipedia discovery summary; primary traceability sources are available. |
| R2-EXC-033 | *Requirements traceability* | https://en.wikipedia.org/wiki/Requirements_traceability | Wikipedia discovery summary; primary and review sources are available. |
| R2-EXC-034 | *Digital thread* | https://en.wikipedia.org/wiki/Digital_thread | Wikipedia discovery summary; authoritative and primary sources are available. |
| R2-EXC-035 | *DevOps Research and Assessment* | https://en.wikipedia.org/wiki/DevOps_Research_and_Assessment | Wikipedia discovery summary; direct research sources are searchable. |

The web interface also returned individually identified Reddit and trade-press
results. They were not selected for the candidate set because stronger primary,
publisher or review routes were present. Because the interface output was
truncated, no generic grouped exclusion is used to imply a complete result set.

## OpenAlex citation-chain continuation

The remaining R2-CAND-002 forward pages were retrieved through the public
OpenAlex API using `curl.exe`. Exact requests were:

- `https://api.openalex.org/works?filter=cites:W3183735209&sort=cited_by_count:desc&per-page=10&page=2&select=id,doi,title,publication_year,type,cited_by_count`
- `https://api.openalex.org/works?filter=cites:W3183735209&sort=cited_by_count:desc&per-page=10&page=3&select=id,doi,title,publication_year,type,cited_by_count`
- `https://api.openalex.org/works?filter=cites:W3183735209&sort=cited_by_count:desc&per-page=10&page=4&select=id,doi,title,publication_year,type,cited_by_count`
- `https://api.openalex.org/works?filter=cites:W3183735209&sort=cited_by_count:desc&per-page=10&page=5&select=id,doi,title,publication_year,type,cited_by_count`

Pages 2 through 4 returned ten records each and page 5 returned four. Combined
with Round 003 page 1, all 44 citing records exposed in this graph snapshot were
retrieved. Results were ordered by OpenAlex `cited_by_count:desc`; that is
discovery metadata, not a source-quality or relevance ranking.

### Citation-chain status after Round 004

- **R2-CHAIN-001:** forward and backward retrieval complete for the current
  OpenAlex graph snapshot.
- **R2-CHAIN-002:** forward and backward retrieval complete for the current
  OpenAlex graph snapshot: 44 citing and 26 referenced records retrieved.

Completion describes retrieval from one mutable citation graph, not complete
scholarly citation coverage. Most retrieved records were not retained because
their titles concerned system-specific MBSE applications rather than the R-002
unit of analysis. R2-CAND-041 and R2-CAND-042 preserve the two newly selected
leads; non-selection is not evidence appraisal.

## Round 004 access and reproducibility limitations

- Web result sets, counts, ranking and provider remain unavailable; returned
  output was truncated.
- Three of four Semantic Scholar requests were rate-limited before exposing
  results. The single successful route cannot represent the other families.
- Crossref exact-title matching returned a false-positive top result for one
  request; the mismatch remains explicit.
- OpenAlex is a mutable scholarly graph, and citation membership and counts may
  change after the recorded date.
- No full text was appraised and no candidate was registered as evidence.
- Language, paywall and database-index coverage remain incomplete.

## Family coverage after Round 004

| Family | Cumulative state | Note |
| --- | --- | --- |
| F-01 — Named cross-lifecycle approaches | Initial coverage only | Additional digital-thread implementation and limitation leads; evidence modes incomplete. |
| F-02 — Enterprise architecture and governance | Initial coverage through three routes | Web, Crossref and one successful Semantic Scholar route; source appraisal and evidence modes incomplete. |
| F-03 — Systems engineering, MBSE and lifecycle management | Initial coverage only | Two OpenAlex seed chains complete for the current graph snapshot; broader routes and evidence modes incomplete. |
| F-04 — Traceability and impact analysis | Initial coverage only | Lifecycle SLR lead added; independent database route was rate-limited. |
| F-05 — Decisions, rationale and provenance | Initial coverage only | Combined web query produced no retained new decision/provenance lead. |
| F-06 — Organisational memory and knowledge management | Initial coverage only | No dedicated route in this round. |
| F-07 — Semantic and graph-based integration | Initial coverage only | No dedicated route in this round. |
| F-08 — DevOps, SRE and operational learning | Initial coverage through two completed routes plus one failed route | Additional web discovery completed; Semantic Scholar request was rate-limited. |
| F-09 — Deliberate compositions | Initial coverage only | MBSE/DevOps and MBSE/digital-thread composition leads added; implementation evidence incomplete. |
| F-10 — Adoption, burden and harmful integration | Initial coverage only | EA, DevOps, DevSecOps and interoperability limitation leads added; evidence modes incomplete. |

## Round 004 diminishing-returns and stopping position

All ten families remain incomplete. Round 004 produced additional candidates
and completed both current OpenAlex seed chains, but it did not identify a new
material approach family or comparison dimension beyond those already defined
in the approved strategy and construct map. This is the first consecutive
round meeting that narrow diminishing-novelty condition; the approved stopping
rule requires two consecutive rounds and independent reviewer agreement.

The round does not establish saturation. F-04 and F-05 lack a completed new
independent route, F-06 and F-07 received no dedicated Round 004 search, three
Semantic Scholar searches failed, required evidence modes remain incomplete,
and the Evidence Reviewer has not reviewed search completeness.

## Round 004 boundary

Search Round 004 adds discovery and citation-chain provenance only. It does
not:

- register or appraise evidence;
- map a candidate to N-01 through N-06;
- assign a coverage level or evidential direction;
- treat route agreement or citation count as source quality;
- change C-003 or C-005;
- assign confidence or disposition;
- satisfy the Stage A stopping rules;
- authorise Stage B; or
- introduce OME terminology, canon or product material.

## Round 004 corrections

None recorded.

## CTO Independent Search-Round Review — Round 004

Status: complete.

- **Execution scope:** approved. Round 004 records four exact web searches, a
  distinct Semantic Scholar route, exact Crossref metadata checks and
  completion of the outstanding OpenAlex chain without entering evidence
  appraisal or claim assessment.
- **Route failures and mismatches:** approved. Three Semantic Scholar HTTP 429
  responses and the Crossref false-positive title match remain explicit rather
  than being represented as completed or verified discovery.
- **Citation chaining:** approved. Both current OpenAlex seed chains are
  complete for the recorded graph snapshot without implying universal citation
  completeness.
- **Candidate provenance:** approved. Eleven retained candidates remain triage
  records rather than Evidence Register entries.
- **Diminishing-returns fidelity:** approved. Round 004 is only the first round
  meeting the narrow no-new-family-or-dimension condition; it does not establish
  saturation or satisfy the two-round stopping rule.
- **Stopping-rule fidelity:** approved. All ten families remain incomplete.
- **Research boundary:** approved. No evidence registration or appraisal,
  N-01–N-06 mapping, coverage level, evidential direction, confidence, claim
  assessment, Stage A stopping declaration or Stage B authority has entered
  the round.
- **Independent decision:** approve PR #23.
- **Required corrections:** none.

## Accountable decision — Round 004

Status: approved by the founder on 2026-07-18 through the merge decision for
[PR #23](https://github.com/OME-Foundation/ome-specification/pull/23).

The accountable decision accepts Search Round 004 as an execution and
provenance record. It does not register or appraise evidence, classify an
approach, change C-003 or C-005, assign confidence, declare Stage A complete or
authorise Stage B.
