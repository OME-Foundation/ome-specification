# R-002 construct map

Status: proposed interpretation framework; not a finding, coverage assessment
or OME terminology decision.

This map defines how R-002 will distinguish cross-lifecycle integration from
adjacent or partial practices. It implements the approved
[R-002 execution protocol](../R-002.md) and complements the approved
[search strategy](SEARCH_STRATEGY.md).

No search has been executed, no evidence has been registered and no approach
has been classified through this document. Approval and merge will not start
Stage A. Execution requires a later mechanical authority transition.

## Purpose

R-002 must test C-003 without defining the alleged gap so broadly that every
approach fails or so weakly that any artifact link succeeds:

> Existing organisational-memory, knowledge-management, traceability,
> decision-rationale and provenance practices leave a material cross-lifecycle
> integration gap.

This map supplies a neutral comparison boundary. It does not establish that the
boundary describes a valuable intervention, a novel construct or a real gap.

## Working construct

For R-002, **cross-lifecycle integration** provisionally means:

> An established approach or deliberate composition that creates explicit,
> recoverable and governed relationships among material organisational
> objectives, decisions and their reasoning, implementation, operational
> experience and subsequent learning, and maintains those relationships
> sufficiently through change for authorised actors to use them in relevant
> work.

This is research vocabulary only. It must not enter OME canon or product design
without a separate admission decision.

## Lifecycle functions

The five labels below identify functions, not required document types, tools,
teams or process phases. An approach may use different established vocabulary.

| Function | Working meaning | Examples of eligible representations | Boundary caution |
| --- | --- | --- | --- |
| Objective | A material purpose, intended outcome, constraint, stakeholder need or capability that gives work direction. | goals, strategy, mission, outcomes, requirements, capabilities | A task or artifact title alone may not express intent. |
| Decision | A consequential selection, commitment, assumption or trade-off and the available reasoning that explains it. | decisions, rationale, alternatives, assumptions, approvals | A final choice without context may provide traceability but not reasoning. |
| Implementation | A designed or realised change intended to enact the decision. | models, designs, configurations, code, procedures, controls, verification | Implementation need not be software. |
| Operation | Evidence or experience arising when the implementation is used, maintained or observed. | telemetry, incidents, service outcomes, validation, maintenance experience | Deployment status alone is not operational learning. |
| Learning | Interpretation that can confirm, challenge or change an objective, decision, implementation or governing practice. | review findings, lessons, adaptations, revised assumptions, improvement decisions | Storage of observations without interpretation or influence is insufficient. |

The functions may overlap, recur and change at different rates. The construct
does not assume a linear waterfall. The arrows in the protocol describe
traceable influence, including feedback and revision, not one-way hand-off.

## Unit of analysis

The unit assessed must be one of:

1. a single recognised approach, method, framework, standard or reference
   model;
2. a deliberate and repeatable composition of established approaches;
3. an implemented organisational practice with inspectable mechanisms; or
4. a tool ecosystem only where the practice, relationships and governance can
   be evaluated independently of vendor positioning.

The unit must have a stated boundary, population or context and version or time
period. Evidence about different implementations must not be silently combined
into one idealised approach.

### Deliberate composition rule

A composition is eligible when:

- its component practices and division of responsibility are explicit;
- hand-offs or relationship mappings between components are defined;
- ownership and maintenance are assigned;
- identifiers or equivalence rules permit relationships to be recovered;
- the composition is repeatable beyond a one-off integration; and
- its combined burden and failure modes can be evaluated.

No single repository, vocabulary, database, vendor or central authority is
required. Federated coverage can satisfy the working construct. Merely listing
compatible practices does not establish a deliberate composition.

## Necessary characteristics

An approach or composition must exhibit all six characteristics to qualify as
candidate cross-lifecycle integration. Failure of one characteristic means the
unit may still provide important partial or adjacent coverage.

### N-01 — Material lifecycle breadth

The approach represents all five lifecycle functions or provides an explicit,
defensible mapping to equivalent functions. It need not link every artifact;
scope and materiality rules must identify what belongs.

### N-02 — Explicit relational continuity

Relationships across the functions have defined meaning. They show more than
co-location or chronological proximity and allow a reviewer to distinguish,
for example, derivation, satisfaction, implementation, validation, influence,
revision and contradiction.

### N-03 — Change maintenance

The approach defines how relationships are created, updated, invalidated,
versioned or superseded as their objects change. A static snapshot does not
establish continuity through change.

### N-04 — Recoverability

Authorised actors can retrieve the relevant objects, relationships, state and
available reasoning when needed. Recoverability includes identity, history and
current validity; it does not require perfect or permanent retention.

### N-05 — Organisational practice and governance

The approach assigns responsibility, authority and decision rules for capture,
quality, maintenance, access and use. Technical connectivity without an
organisational operating practice is insufficient.

### N-06 — Learning connection

Operational evidence or experience can be interpreted and related back to at
least one earlier objective, decision or implementation, with a defined path
for confirmation, revision or deliberate non-action.

## Necessary, but not automatically sufficient

The six characteristics establish **candidate conceptual coverage**. They do
not by themselves show that the approach:

- has been implemented;
- remains maintained in use;
- improves any outcome;
- is proportionate to its burden;
- works across contexts; or
- eliminates a material gap.

An authoritative standard can establish what an approach specifies. It cannot
alone establish maintained organisational use or effectiveness.

## Sufficient basis for different coverage statements

Later evidence appraisals must state which level they can justify. Higher
levels do not follow automatically from lower ones.

| Level | Minimum basis | What may be said | What may not be inferred |
| --- | --- | --- | --- |
| Defined coverage | Authoritative specification satisfies N-01 through N-06. | The approach specifies candidate cross-lifecycle integration. | That anyone implements or benefits from it. |
| Implemented coverage | Inspectable implementation instantiates the specified mechanisms in a bounded context. | The approach has been implemented in that context. | That it remains maintained or routinely used. |
| Maintained coverage | Longitudinal or otherwise adequate evidence shows relationships and governance persist through material change and are recoverable in use. | The implementation provides maintained coverage in the studied context. | That outcomes exceed costs or generalise. |
| Outcome-supported coverage | Appropriate evidence connects maintained use to relevant benefits, harms, null outcomes and burden against credible alternatives. | The approach has demonstrated outcomes under stated conditions. | Universal effectiveness or absence of a remaining gap elsewhere. |

No evidence record should use the unqualified word `covers` when only one of
these levels is supported.

## Partial and adjacent coverage

The following constructs may satisfy important parts of the map without
qualifying as cross-lifecycle integration. They must be evaluated on their own
terms rather than treated as failed versions of this construct.

| Adjacent construct | Coverage it may provide | What remains to be tested |
| --- | --- | --- |
| Organisational memory | Acquisition, retention, retrieval and use of organisational knowledge. | Whether engineering objectives, decisions, implementation, operation and learning are explicitly related and maintained. |
| Organisational learning | Adaptation of knowledge, routines or behaviour through experience. | Whether learning is recoverably connected to the prior objectives, decisions and realised changes it informs. |
| Knowledge management | Creation, capture, sharing, retrieval and reuse of knowledge. | Whether lifecycle relationships, reasoning, change maintenance and accountable use are explicit. |
| Enterprise architecture | Alignment of strategy, capabilities, processes, information and technology with governance. | Whether decision reasoning, realised implementation, operational evidence and learning remain traceably connected in practice. |
| Systems engineering or MBSE | Lifecycle processes, requirements, models, verification and validation across system development. | Whether objectives, rationale, operational experience and learning form maintained organisational memory rather than project-only traceability. |
| Digital thread, PLM or engineering lifecycle management | Connected product, model and engineering data across lifecycle stages. | Whether relationship semantics, rationale, governance, use and learning meet N-01 through N-06. |
| Requirements traceability | Links among needs, requirements, design, implementation and tests. | Whether decisions and rationale, operational outcomes, learning and maintenance through change are included. |
| Decision records or design rationale | Decisions, alternatives, assumptions and reasons. | Whether these connect to objectives, implementation, operation and later learning and remain maintained. |
| Data, model or knowledge provenance | Origins, transformations, agents and derivations. | Whether provenance represents the required organisational decisions, lifecycle influence, governance and learning. |
| Knowledge graph or semantic model | Machine-readable entities and relationships across domains. | Whether the graph is maintained, governed, recoverable and used as organisational practice. |
| DevOps, SRE or incident learning | Delivery-to-operation feedback, telemetry, incident review and improvement. | Whether objectives, prior decisions and rationale are included and learning persists beyond local workflows. |
| Audit or compliance system | Evidence of approval, control and accountability. | Whether it preserves explanatory reasoning and enables learning rather than only demonstrating conformity. |

Adjacency is not inferiority. A bounded practice may be more effective and less
burdensome than full integration in its intended context.

## Excluded constructs and observations

The following do not qualify as the working construct on their own:

- a document repository or search portal;
- a lessons-learned database;
- an architecture diagram or static reference model;
- isolated requirements, test or code trace links;
- a decision log without downstream and feedback relationships;
- an audit trail that records events but not material influence or reasoning;
- data lineage limited to movement or transformation of data;
- a knowledge graph, ontology or common schema without maintained
  organisational practice;
- a dashboard or observability platform without a learning connection;
- a tool feature list, integration catalogue or vendor architecture;
- an API, connector or shared identifier without defined relationship
  semantics and governance;
- co-location of artifacts in one tool or repository;
- a one-off migration, demonstration or manually curated showcase;
- informal human memory or undocumented coordination; and
- a proposed OME or private product design.

These may contribute components to an eligible composition. Their existence
alone cannot establish full coverage.

## What does not count as evidence of coverage

Later appraisal must not treat any of the following as sufficient evidence:

- marketing claims, customer lists or product positioning;
- a source using `end-to-end`, `closed loop`, `digital thread`, `single source
  of truth` or similar language without inspectable definitions;
- a diagram spanning lifecycle labels without maintained relationships;
- a standard's aspirational scope as proof of implementation or outcome;
- tool interoperability as proof of organisational use;
- trace-link counts as proof of meaningful reasoning or recoverability;
- schema completeness as proof that records are current or used;
- successful retrieval as proof that knowledge influenced work;
- a single implementation as proof of general coverage;
- adoption failure as proof that conceptual coverage is absent;
- absence of a discovered source as proof that no approach exists;
- evidence from one component silently attributed to an entire composition;
- citation count, brand recognition or standards status as effectiveness
  evidence; or
- internal OME analysis or private product knowledge as external proof.

Such material may be contextual or support narrower statements when recorded
with the appropriate limitation.

## Comparison dimensions

Every eligible unit will later be mapped across the same dimensions. Unknown
must remain distinct from absent.

| Dimension | Comparison question |
| --- | --- |
| Intended scope | What contexts, populations, lifecycle objects and materiality rules does the approach claim? |
| Lifecycle breadth | Which of the five functions are represented, and by what equivalents? |
| Relationship semantics | What relationships are defined, and can influence, derivation, satisfaction, revision and contradiction be distinguished? |
| Decision reasoning | Are alternatives, assumptions, evidence and trade-offs recoverable, or only outcomes and approvals? |
| Directionality | Can later evidence revise or challenge earlier objectives and decisions, or are links one-way? |
| Change maintenance | How are links and objects updated, invalidated, versioned and superseded? |
| Recoverability | Who can retrieve what, when, with which history, access constraints and validity signals? |
| Governance | Who owns capture, quality, maintenance, access, review and correction? |
| Organisational use | Is the approach embedded in accountable work or merely technically available? |
| Composition and interoperability | How do components exchange identity, meaning, state and responsibility? |
| Temporal fit | Can objects changing at different rates remain meaningfully related? |
| Evidence level | Does the source establish definition, implementation, maintained use or outcome? |
| Outcomes | What benefits, harms, null results and unintended effects are observed? |
| Burden and proportionality | What capture, integration, maintenance, cognitive, privacy and governance costs arise? |
| Failure modes | How and why does coverage decay, fragment, become obsolete or go unused? |
| Alternatives | Could adoption, incentives, authority, coordination, data quality or another mechanism explain the result? |

No aggregate score or Organisational Memory Index is authorised. Dimensions
must remain visible so strengths in one area cannot conceal absence in another.

## Competing explanations

R-002 must preserve at least these alternatives:

1. **Existing sufficient approach:** one established method already satisfies
   the relevant boundary.
2. **Existing sufficient composition:** organisations can deliberately combine
   established practices without a new unifying discipline.
3. **Adoption gap:** conceptual coverage exists but is not adopted,
   institutionalised or funded.
4. **Maintenance gap:** the practice is implemented but relationships decay or
   ownership lapses.
5. **Governance or authority gap:** actors cannot create, challenge or act on
   records even when the technical mechanism exists.
6. **Interoperability or data-quality gap:** discontinuity arises from identity,
   semantic, versioning or data-quality failures.
7. **Incentive or coordination gap:** local priorities and organisational
   boundaries explain fragmented use better than missing practice.
8. **Evidence gap:** approaches may exist, but available evidence cannot
   distinguish definition, implementation, maintained use and outcomes.
9. **Contextual gap:** integration is useful only for particular risks,
   lifecycles or organisational forms.
10. **No beneficial gap:** broader integration adds burden, surveillance,
    rigidity, privacy risk or obsolete information without sufficient benefit.
11. **Temporal incompatibility:** lifecycle objects change at rates that make
    continuous integration impractical or misleading.
12. **Construct imposition:** the five-function boundary reflects the research
    team's model rather than a coherent phenomenon in established practice.

Evidence supporting one explanation does not automatically reject the others.

## Boundary cases

### Complete trace chain without reasoning

An approach may link objective, requirement, design, implementation, test and
operation while recording no decision context. It provides broad traceability
but does not satisfy N-02 as currently defined. This is partial coverage, not
failure of the approach at its intended purpose.

### Complete semantic graph without maintained use

A graph may model every lifecycle function and relationship but lack ownership,
update practice or routine use. It may establish defined technical coverage,
but not N-03 or N-05 and therefore not maintained organisational coverage.

### Maintained local feedback loop

An operational team may connect incidents, changes and reviews reliably while
omitting strategic objectives or earlier decision rationale. It may be an
effective bounded learning system without cross-lifecycle breadth.

### Federated composition

Separate systems and practices may satisfy the construct when stable identity,
semantic mappings, governance, maintenance and recovery join them. Physical
centralisation is irrelevant.

### Manual but governed practice

Automation is not necessary. A manual practice may qualify if it is explicit,
repeatable, maintained and recoverable. Automation cannot compensate for an
undefined or unowned practice.

### Selective retention

The construct does not require capturing everything. An approach may qualify
when it defines proportionate materiality, retention, expiry and access rules.
Selective forgetting can be necessary for privacy, relevance and burden.

## Operational mapping rule

During later Stage A work, each candidate approach must receive:

1. a bounded unit-of-analysis statement;
2. a source-backed map for N-01 through N-06 using `present`, `partial`,
   `absent`, `unclear` or `not applicable with justification`;
3. a coverage level limited to what the source can establish;
4. a comparison-dimension record with unknowns preserved;
5. relevant competing explanations and boundary cases;
6. an explicit statement of what the source does not establish; and
7. independent review before any evidential lifecycle promotion.

`Present` at all six characteristics permits the label **candidate conceptual
coverage** only. Claim direction and the sufficiency of evidence remain
separate judgements. A candidate map is not evidence unless its entries are
supported by eligible sources.

## Necessary evidence distinctions

Evidence records must distinguish:

- evidence about an approach's authoritative definition;
- evidence that an implementation instantiates it;
- evidence that relationships and governance remain maintained in use;
- evidence of beneficial, harmful or null outcomes;
- evidence about burden and proportionality; and
- evidence for an alternative explanation.

A source may bear on several distinctions, but each inference must be recorded
separately. Evidence direction is always relative to the precise claim, not the
reputation or overall quality of the source.

## Explicit non-goals

This construct map does not:

- assert that a cross-lifecycle integration gap exists;
- assess C-003 or C-005;
- define OME, its architecture or its canon;
- claim that broader integration is desirable;
- require a unified platform, repository, graph or vocabulary;
- prescribe an implementation or reference architecture;
- define product requirements or commercial differentiation;
- reopen R-001 or use C-002 as an established premise;
- define Stage B, field research or a pilot;
- introduce a score, maturity model or index;
- classify any existing approach;
- register or appraise evidence; or
- claim novelty from an empty search result.

## What would invalidate or require revision of this map?

- Established disciplines use a materially different lifecycle boundary that
  makes the five functions misleading or redundant.
- A sufficient established approach cannot be represented without distorting
  its intended unit or scope.
- N-01 through N-06 cannot be assessed without circularly assuming OME.
- The map excludes a repeatable composition solely because it is federated,
  manual or differently named.
- The map classifies useful bounded practices as deficient rather than partial
  by design.
- Relationship maintenance or organisational use cannot be distinguished from
  technical capability with inspectable evidence.
- Materiality, proportionality or selective retention cannot be represented.
- Independent review finds that a necessary characteristic embeds a desired
  outcome rather than defining the construct.

Any material revision after evidence is observed must follow the protocol-
amendment rule and disclose its possible effect on interpretation.

## Review and approval boundary

PR #18 proposes this map only. Independent review must determine whether:

- the working definition is neutral and non-circular;
- necessary characteristics are individually required and jointly coherent;
- specified, implemented, maintained and outcome-supported coverage remain
  distinct;
- deliberate compositions and federated approaches can qualify fairly;
- adjacent and excluded constructs are represented without being dismissed;
- comparison dimensions expose rather than aggregate important differences;
- competing explanations can overturn or narrow C-003;
- non-evidence rules prevent feature, diagram and marketing substitution;
- non-goals preserve the public/private and stage boundaries; and
- no evidence, classification, confidence or conclusion has entered the map.

Founder approval and merge will not authorise search execution. After approval,
a separate mechanical transition must record the accepted search strategy and
construct map and explicitly authorise Stage A before any query is run or
evidence is registered.

## Current authority

- R-002 remains the primary active research programme.
- The execution protocol and search strategy have been approved and merged.
- Construct-map preparation is authorised.
- This document remains proposed until independently reviewed and approved.
- No R-002 search has been executed.
- No R-002 evidence has been registered.
- Stage A execution and Stage B remain unauthorised.
- R-001 remains frozen at its approved stopping condition.

## CTO Independent Construct-Map Review

Status: complete.

- **Construct boundary:** approved. The working definition is neutral and
  non-circular, and the lifecycle labels remain functions rather than
  prescribed artifacts, tools or phases.
- **Necessary characteristics:** approved. N-01 through N-06 are individually
  defensible and jointly coherent without embedding an outcome requirement.
  Their joint presence establishes candidate conceptual coverage only.
- **Evidence levels:** approved. Defined, implemented, maintained and outcome-
  supported coverage remain distinct, preventing specifications or isolated
  implementations from being treated as proof of routine use or effectiveness.
- **Deliberate and federated compositions:** approved. Distributed practices
  can qualify without a single repository, vendor, vocabulary, database or
  authority, while explicit responsibilities, mappings, maintenance,
  recoverable identity and evaluable burden remain required.
- **Adjacent and excluded constructs:** approved. Established practices are
  represented as potentially valuable partial coverage, while repositories,
  diagrams, isolated links, dashboards, schemas, tool features and marketing
  claims cannot substitute for maintained organisational integration.
- **Comparison framework:** approved. The dimensions remain visible and non-
  aggregated, with `unknown` distinct from `absent` and no score or index.
- **Competing explanations and boundary cases:** approved. The alternatives can
  narrow, supersede or overturn C-003, and the cases demonstrate that the map
  can represent federated, manual, bounded and selectively retained practice.
- **Governance boundary:** approved. The operational mapping rule limits
  classification to the supported coverage level, preserves unknowns and
  requires independent review. No search, evidence, classification, claim
  decision, Stage A execution, Stage B work, canon or private product material
  has entered the proposal.
- **Independent decision:** approve PR #18.
- **Required corrections:** none.

## Accountable decision

Status: pending founder approval after independent review.
