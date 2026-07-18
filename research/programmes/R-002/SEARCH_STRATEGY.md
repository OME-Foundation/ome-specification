# R-002 search strategy

Status: approved search strategy; Stage A execution is authorised only when
the mechanical authority transition in PR #19 is merged. No search has been
executed and no evidence has been registered.

This strategy defines how R-002 will find existing approaches that may already
cover the claimed cross-lifecycle integration gap. It implements the approved
[R-002 execution protocol](../R-002.md) without assuming that a gap exists.

Approval of this document did not start Stage A. Search execution remains
unauthorised until the approved strategy and construct map are mechanically
recorded as execution prerequisites through the merge of PR #19.

## Search objective

Find and evaluate established approaches, deliberate compositions and
implemented practice ecosystems that may connect:

> objective -> decision -> implementation -> operation -> learning

The sequence is provisional retrieval vocabulary inherited from the protocol.
It is not an OME model, a finding or a test of coverage. PR #18 will define and
challenge the construct boundary before any result is classified.

The search must make it easier to discover that existing practice is
sufficient than to conclude that OME fills a gap.

## Questions the search must serve

1. Does one established approach claim and define cross-lifecycle integration?
2. Can a documented, repeatable composition of approaches provide equivalent
   coverage?
3. Are relationships maintained through change and recoverable when needed?
4. Is claimed capability implemented and used, or only specified or marketed?
5. What evidence exists about outcomes, maintenance burden and failure modes?
6. Are discontinuities explained better by adoption, governance, incentives,
   authority, interoperability, data quality or cost?
7. In which contexts is integration unnecessary, harmful or inferior to
   bounded local practices?

## Search principles

- Search for sufficient existing practice and disconfirming cases first.
- Evaluate approaches at their intended scope and in deliberate combination.
- Use established disciplinary vocabulary before any OME language.
- Separate specified capability, implemented practice, maintained use and
  demonstrated outcome.
- Treat tool and vendor claims as discovery leads, not independent evidence.
- Preserve null results, negative findings, exclusions and access barriers.
- Do not infer novelty or absence from failure to retrieve a source.
- Do not classify coverage until the construct map is approved.

## Units sought

Searches may retrieve:

- a recognised approach, method, framework, standard or reference model;
- a deliberate and repeatable composition of established practices;
- an implemented organisational practice with inspectable design or outcomes;
- an interoperability or governance mechanism that maintains lifecycle
  relationships; or
- a tool ecosystem only where its practice can be evaluated independently of
  vendor positioning.

An isolated artifact, link, repository, dashboard or feature is not sufficient
by itself. A federated approach remains eligible when its composition,
relationships, ownership and maintenance are explicit.

## Retrieval vocabulary

The following vocabulary is a search aid, not a construct decision. Terms may
be added after a protocol amendment records why retrieval required them.

### Lifecycle concepts

| Area | Initial vocabulary |
| --- | --- |
| Objective | objective, goal, intent, strategy, mission, capability, outcome, requirement, stakeholder need |
| Decision | decision, rationale, assumption, trade-off, justification, approval, architecture decision |
| Implementation | implementation, design, model, configuration, code, change, realization, verification |
| Operation | operation, runtime, service, incident, telemetry, performance, maintenance, validation |
| Learning | learning, feedback, review, retrospective, lesson learned, adaptation, improvement |
| Continuity | traceability, provenance, lineage, digital thread, knowledge continuity, closed loop, lifecycle integration |
| Maintenance | change propagation, impact analysis, synchronization, evolution, governance, ownership, versioning |
| Recovery | retrieval, recoverability, auditability, explanation, reconstruction, reuse, decision history |

### Practice and discipline families

1. organisational memory, organisational learning and knowledge management;
2. enterprise architecture and architecture knowledge management;
3. systems engineering, model-based systems engineering and lifecycle models;
4. digital thread, product lifecycle management and engineering lifecycle
   management;
5. requirements, design and test traceability;
6. architecture decisions, design rationale and decision provenance;
7. data, model and knowledge provenance;
8. knowledge graphs, semantic models and ontology-based integration;
9. DevOps, SRE, incident learning and continuous improvement; and
10. documented compositions spanning two or more of these families.

### Competing-explanation vocabulary

- adoption, institutionalisation, maturity and compliance;
- incentives, authority, accountability, ownership and governance;
- interoperability, integration, federation and data quality;
- absorptive capacity, transfer, coordination and expertise location;
- maintenance cost, capture burden, information overload and obsolescence;
- privacy, surveillance, rigidity, autonomy and local adaptation; and
- failed implementation, workarounds, decay, abandonment and non-use.

## Mandatory search families

Each family must include searches for conceptual coverage, implemented use,
outcomes or limitations, and credible counterexamples.

### F-01 — Named cross-lifecycle approaches

Seek approaches explicitly claiming end-to-end, closed-loop or lifecycle-wide
integration. Search both general terms and the vocabulary used by recognised
standards bodies and professional disciplines.

### F-02 — Enterprise architecture and governance

Test whether enterprise-architecture methods connect strategy, decisions,
realisation, operation and change, including governance and maintained
traceability rather than diagrams alone.

### F-03 — Systems engineering, MBSE and lifecycle management

Test systems-engineering lifecycle processes, model-based practice, digital
thread, PLM and engineering lifecycle management on their strongest intended
scope and in operational use.

### F-04 — Traceability and impact analysis

Search requirements-to-design-to-code-to-test-to-operation traceability,
bidirectional traceability, change propagation and impact analysis. Distinguish
link existence from maintained reasoning and learning.

### F-05 — Decisions, rationale and provenance

Search architecture decision records, design rationale, decision provenance,
data provenance, model provenance and knowledge provenance, including their
composition with delivery and operational evidence.

### F-06 — Organisational memory and knowledge management

Search organisational-memory systems, lessons-learned systems, knowledge
retention, knowledge reuse and continuous-learning practices for explicit
connections to engineering lifecycle objects and outcomes.

### F-07 — Semantic and graph-based integration

Search engineering knowledge graphs, semantic digital threads, ontologies and
linked lifecycle data. Require an evaluable maintained practice rather than
assuming that a graph schema establishes organisational use.

### F-08 — DevOps, SRE and operational learning

Search feedback from telemetry, incidents, post-incident review and continuous
improvement into objectives, decisions, requirements or implementation.

### F-09 — Deliberate compositions

Actively seek documented combinations that provide coverage without a single
named framework, including standards profiles, tool-neutral reference
architectures and repeatable governance arrangements.

### F-10 — Adoption, burden and harmful integration

Search failures, null outcomes, abandonment, maintenance decay, excessive
capture cost, surveillance effects, rigidity, privacy risks and contexts in
which local or loosely coupled practice performs better.

## Query construction

Search rounds will combine one term from each relevant block:

1. a practice or discipline family;
2. two or more lifecycle concepts;
3. a continuity or maintenance mechanism; and
4. an evidence qualifier where empirical or implementation evidence is sought.

Initial evidence qualifiers include:

`empirical`, `case study`, `field study`, `evaluation`, `implementation`,
`longitudinal`, `systematic review`, `failure`, `limitation`, `adoption`,
`maintenance`, `outcome`, `burden`, `abandonment`, `counterexample`.

Example query templates, not executed queries:

- `(<approach>) AND (<objective term>) AND (<operation term>) AND
  (traceability OR provenance OR "digital thread")`
- `(<approach>) AND (decision OR rationale) AND (implementation OR operation)
  AND (evaluation OR "case study")`
- `(<approach A>) AND (<approach B>) AND (integration OR composition OR
  interoperability) AND lifecycle`
- `(<approach>) AND (failure OR abandonment OR burden OR limitation)`
- `(<approach>) AND (adoption OR governance OR ownership OR maintenance) AND
  (gap OR discontinuity OR decay)`

Exact strings, syntax changes and filters must be recorded at execution time.
Queries must not use `OME` or `Organisational Memory Engineering` as discovery
terms except for a separately labelled check for prior use of the name; such a
check cannot establish coverage or novelty.

## Sources and interfaces

### Authoritative and scholarly sources

- official standards catalogues and issuing-body publications;
- Crossref and DOI metadata for durable identity;
- OpenAlex for broad discovery and citation relationships;
- IEEE Xplore, ACM Digital Library, INFORMS, SpringerLink, ScienceDirect,
  Wiley, Oxford Academic and other relevant publisher indexes;
- Scopus or Web of Science when access is available and the interface and
  coverage can be recorded;
- discipline-specific authoritative repositories; and
- backward and forward citation searching from eligible sources.

### Supplementary discovery

General web and scholarly web search may locate terminology, standards,
implementations and grey literature. Each interface must be named. Where the
provider does not expose ranking, configuration or complete results, the log
must say that the result set is not reproducible.

Vendor documentation, consultancy material and practitioner reports may help
describe a practice or locate primary material. They cannot independently
establish effectiveness, sufficiency or comparative advantage.

## Search order

1. Search F-01, F-03 and F-09 for sufficient existing approaches and
   compositions capable of superseding C-003.
2. Search F-02, F-04, F-05 and F-06 for established partial or integrated
   coverage.
3. Search F-07 and F-08 for semantic and operational feedback mechanisms.
4. Search F-10 throughout, beginning in the first round rather than after
   apparently supporting material is found.
5. Follow terminology and citations into newly identified established
   families through recorded amendments, without silently changing scope.

This order is a bias control, not a ranking of disciplines.

## Screening and selection

### First-pass screening

Record for every potentially eligible approach:

- durable identifier or stable URL;
- source type and issuing authority;
- claimed scope and lifecycle stages;
- whether it is a single approach or composition;
- whether evidence concerns specification, implementation, maintained use or
  outcome;
- apparent relevance to C-003 and plausible competing explanation; and
- include, exclude or defer decision with reason.

### Inclusion for evidence registration

A source must satisfy the protocol's inclusion criteria and contribute at
least one of:

- authoritative definition of material lifecycle coverage;
- inspectable integration or composition mechanism;
- primary evidence of implementation, maintenance, outcomes or burden;
- authoritative synthesis or critical review;
- credible failure, null result, harmful case or sufficient-practice
  counterexample; or
- evidence that an apparent gap is caused by adoption or another competing
  explanation.

Registration direction will be claim-specific and cannot be assigned until the
construct map is approved. Discovery and selection do not change C-003.

### Exclusion

Record, rather than silently discard:

- feature lists without an evaluable practice;
- unsupported marketing claims;
- diagrams without defined and maintained relationships;
- isolated lifecycle links presented as complete integration;
- sources whose relevant claims cannot be inspected;
- duplicate reports of the same underlying study; and
- internal OME or private product material.

More complete versions of the same work should be linked and the selected
version justified. Language and access restrictions must be logged as search
limitations, not treated as irrelevance.

## Provenance record

Each search round must record:

- round identifier, date, researcher and execution context;
- named database, catalogue, website or tool and operation used;
- exact query as submitted, including syntax, filters and field restrictions;
- locale, date range, language, sort order and result limit when exposed;
- result count when exposed;
- whether the complete ranked result set was captured;
- selected result identifiers and URLs;
- selection, exclusion and deferral reasons;
- citation-chaining actions; and
- interface limitations affecting reproducibility.

If a tool hides its provider, ranking or full result set, the record must not
claim exact result-set reproducibility. Search logs preserve what was executed;
they are not evidence records.

## Search log structure

Execution will create a separate `SEARCH_LOG.md` with one immutable section per
round. Corrections will append a dated note rather than overwrite the original
query or selection account. Candidate sources will retain stable local
identifiers before evidence numbers are assigned.

The log will also maintain:

- a family-coverage table;
- an excluded-and-deferred candidate table;
- an access-gap register;
- vocabulary additions and their amendment rationale; and
- backward- and forward-chaining status for included sources.

## Stopping rules

Stage A search may be proposed for gate review only when all of the following
are true:

1. every mandatory family has been searched using at least one scholarly or
   authoritative interface and one independent discovery route where such a
   route exists;
2. each family has been searched for sufficient existing practice, implemented
   use, limitations and competing explanations;
3. eligible cornerstone sources have undergone recorded backward and forward
   citation searching where the interface permits it;
4. deliberate compositions have been searched directly rather than inferred
   only from single-practice results;
5. two consecutive planned rounds add no new eligible approach family or
   material comparison dimension;
6. unresolved access, language, database and source-family gaps are explicit;
   and
7. the Evidence Reviewer agrees that further searching is unlikely to alter
   the construct-boundary picture enough to block assessment readiness.

These are bounded Stage A stopping rules, not a claim of systematic-review
exhaustiveness or evidence saturation. Resource limits alone cannot satisfy
them. The gate may remain closed when a missing source or family is materially
capable of changing the boundary assessment.

## Quality and bias controls

- Begin with searches capable of showing that C-003 is unnecessary.
- Pair claimed-capability searches with implementation, failure and burden
  searches.
- Do not treat citation count, brand recognition or standards status as outcome
  evidence.
- Do not equate semantic connectivity with maintained organisational practice.
- Do not equate missing adoption with missing conceptual coverage.
- Do not equate specified coverage with effective or economical use.
- Record Research Lead and reviewer disagreements without resolving them by
  deletion.
- Preserve conflicts of interest arising from OME's intellectual and
  prospective commercial interest in finding a gap.

## Protocol amendments

A material amendment must record:

1. the prior strategy;
2. what changed and when;
3. why the change was necessary;
4. what material had already been observed;
5. whether that observation could have influenced the change; and
6. the expected effect on scope, bias and interpretation.

Adding a newly discovered synonym to an existing family may be logged as a
minor vocabulary amendment. Adding or removing a family, eligibility rule,
source class or stopping condition requires separate review.

## Outputs authorised after later execution approval

Execution may produce only:

- the immutable search log and family-coverage record;
- candidate, excluded, deferred and access-gap records;
- conservatively registered public evidence;
- documented vocabulary amendments; and
- a later proposed Stage A gate review.

It may not assess C-003 or C-005, design Stage B, introduce OME terminology,
change canon or governance, or use private product information.

## Review and approval boundary

PR #17 proposes this strategy only. Independent review must determine whether:

- the search can readily find sufficient existing practice;
- all material adjacent disciplines and deliberate compositions are covered;
- capability, implementation, maintained use and outcome remain distinct;
- failure, adoption, burden and harmful-integration evidence are searchable;
- provenance is proportionate and honest about reproducibility;
- stopping rules are bounded without presenting convenience as saturation;
- the construct map remains a separate prerequisite; and
- no search, evidence, assessment or conclusion has entered the proposal.

Founder approval and merge did not by themselves authorise search execution.
The merge of PR #19 records that this strategy and the approved construct map
satisfy the execution prerequisites and authorises Stage A.

## Current authority

- R-002 is the primary active research programme.
- The search strategy and construct map are independently reviewed,
  founder-approved and merged.
- Stage A execution is authorised only when PR #19 is merged.
- No R-002 search has been executed.
- No R-002 evidence has been registered.
- Until PR #19 is merged, Stage A execution remains unauthorised.
- Stage B remains unauthorised.
- R-001 remains frozen at its approved stopping condition.

## CTO Independent Search-Strategy Review

Status: complete.

- **Search coverage:** approved. The ten mandatory families cover named
  approaches, adjacent disciplines and deliberate compositions. F-09 prevents
  the absence of a single branded framework from being mistaken for absence of
  sufficient existing practice.
- **Bias control:** approved. The search begins with approaches capable of
  superseding C-003, searches failure, burden and adoption from the first
  round, and separates specified capability, implementation, maintained use
  and demonstrated outcomes.
- **Provenance:** approved. Exact queries, filters, interfaces, exposed result
  counts, selections and limitations are required without claiming
  reproducibility where ranking or complete results are hidden. Search-log
  corrections remain append-only.
- **Stopping rules:** approved. All mandatory families, deliberate
  compositions, implementation and limitation evidence, citation chaining,
  diminishing novel coverage, explicit gaps and reviewer agreement are
  required without claiming systematic-review exhaustiveness or saturation.
- **Governance boundaries:** approved. No search, evidence registration,
  coverage classification, claim change, Stage A execution or Stage B work has
  entered the proposal. The construct map and later mechanical authority
  transition remain prerequisites to execution.
- **Independent decision:** approve PR #17.
- **Required corrections:** none.

## Accountable decision

Status: approved by the founder on 2026-07-18 through the merge decision for
[PR #17](https://github.com/OME-Foundation/ome-specification/pull/17).

The accountable decision adopts the independently reviewed search strategy
without changing its scope. Approval did not authorise execution. The merge of
PR #19 records the completed prerequisites and authorises Stage A under this
strategy and the approved construct map.
