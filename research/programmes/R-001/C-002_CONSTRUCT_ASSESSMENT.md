# Proposed C-002 Construct Assessment

Status: proposed; independent CTO review complete; accountable approval pending.

Assessment date: 2026-07-18

Prepared by: Research Lead - repository execution agent (Codex)

## Assessment question

Given the current evidence record, including the explicit gaps at E-006 through
E-008, should C-002 be retained, narrowed, revised, rejected or deferred as a
research construct?

> **C-002:** Organisations incur consequential reconstruction work because
> relevant reasoning cannot be retrieved when needed.

This assessment applies the repository's
[confidence and decision rules](../../operating-system/DECISION_RULES.md) under
the authority and limits of the approved
[Stage A gate review](STAGE_A_GATE_REVIEW.md).

It does not introduce evidence, change evidence lifecycle, alter C-002, claim
novelty, admit terminology, authorise Stage B, design further research or create
canon. All recommendations remain proposed until independently reviewed and
approved.

## Proposed assessment

- **Disposition:** `Defer`
- **Confidence:** `Very low`
- **Classification:** remain `Hypothesis`
- **Lifecycle:** no change proposed in this artifact
- **Working construct:** sufficiently distinguishable and operationalisable to
  remain a research target, but not empirically supported on the current record

`Defer` is not a finding that C-002 is false or unimportant. It records that the
available evidence cannot responsibly discriminate among retention, narrowing,
revision or rejection. `Very low` reflects indirectness and missing linkage,
not a numerical score or an inference from absent evidence.

## Construct being assessed

For assessment, C-002 is decomposed into three jointly required components:

1. **Prior availability** - relevant reasoning, context or knowledge was
   previously available to the organisation.
2. **Later unavailability** - that reasoning later cannot be retrieved or
   applied when needed.
3. **Consequential reconstruction** - organisational actors perform material
   work to re-establish it, producing observable effort or consequence.

This combination is distinguishable from:

- ordinary discovery of knowledge the organisation never held;
- deliberate re-evaluation after materially changed conditions;
- turnover without observed reasoning loss;
- knowledge that is retrievable but not used because of incentives, authority,
  coordination, workload or absorptive capacity;
- learning-curve performance decay without a retrieval mechanism;
- intentional unlearning or purposeful forgetting;
- planned redundancy, independent verification or productive exploration; and
- ordinary execution or rework without reconstruction of prior reasoning.

The distinction is analytically coherent. The current record does not establish
that the complete sequence occurs with material consequence in any defined
population or at any defensible prevalence.

## Evidence considered

### Reviewed evidence

| Evidence | Direct observation relevant to C-002 | Missing link | Assessment role |
| --- | --- | --- | --- |
| E-004 | Organisational knowledge can be lost, degraded, consolidated poorly or deliberately discarded | Does not isolate unavailable prior reasoning or consequential reconstruction | Mechanism and vocabulary context |
| E-005 | Forgetting may be beneficial or harmful under different conditions | Conceptual argument; no empirical reconstruction outcome | Required counterposition |
| E-009 | Transactive-memory systems coordinate current expertise location and use | No later loss or reconstruction event | Retrieval-mechanism boundary |
| E-010 | Participants recover architecture decisions and aspects of rationale | Recovery task is imposed; prior organisational transition and consequential cost are not measured | Closest direct decision-recovery observation |
| E-011 | Architectural assumptions can be reconstructed from surviving people and artifacts | Some assumptions may never have been shared; recovery effort and consequence are not measured | Close reconstruction mechanism |
| E-012 | Requirements-related rework is observed, including work associated with avoidable gaps in shared understanding | Prior availability and later retrieval failure are not established | Closest consequential-work observation |
| E-013 | A source unit's practice may remain difficult for a recipient to transfer or apply | First-time transfer and non-use are not later loss or reconstruction | Strong competing mechanism |
| E-014 | Adaptive change labelled organisational forgetting is associated with innovation | Measure does not demonstrate memory loss, retrieval failure or reconstruction | Beneficial-change boundary |
| E-015 | Coordination reduces redundant fact search while convergence reduces solution diversity | No organisational memory, loss or rediscovery is studied | Productive-exploration boundary |

### Explicit evidence gaps

| Evidence | Current accessible indication | Unavailable conclusion |
| --- | --- | --- |
| E-006 | Production conditions and omitted variables may explain performance changes labelled forgetting | Full model appraisal and whether any result bears more directly on the construct |
| E-007 | Turnover-performance relationships vary by role, sector and organisational capital | Full construct measurement and whether knowledge loss is observed rather than theorised |
| E-008 | Authority and standardisation may buffer turnover-associated project delay | Full construct validity, causal limitations and whether any unreported measure approaches reconstruction |

E-006 through E-008 remain `Registered`. Their incomplete appraisal limits the
assessment but is not counted as evidence for or against C-002. The assessment
must be reopened if full review changes their relevance under the gate's
recorded reopening conditions.

### Background records

E-001 provides established organisational-memory background. E-002 and E-003
are internal reviews and synthesis. They help identify adjacent disciplines and
questions but do not independently validate C-002 and are not used to raise
confidence.

## Claim-level appraisal

### Directness

**Very weak.** No source directly observes the complete sequence. E-010 and
E-011 observe recovery without measured organisational consequence. E-012
observes rework without prior availability followed by retrieval loss. Other
records concern mechanisms, proxies, alternatives or boundaries.

### Methodological fitness

**Insufficient for the compound claim.** Several studies are fit for their own
questions, but their designs do not test C-002 as written. Recovery experiments,
single cases, cross-sectional surveys, team studies and laboratory networks
cannot be combined as though they jointly observe one causal chain.

### Relevance

**Partial and fragmented.** Software architecture and requirements studies are
closest to reasoning and reconstruction. Organisational-forgetting, turnover,
transactive-memory, transfer and network studies clarify mechanisms and
boundaries but use different populations, units and outcomes.

### Independence

**Plausibly varied but not decisive.** The records span distinct disciplines,
authors, methods and settings. That diversity strengthens the boundary map, not
the empirical claim, because the sources do not independently test the same
construct.

### Consistency

**Consistent only at the boundary level.** The reviewed sources consistently
warn against equating loss, turnover, non-use, delay, performance decay, rework
or parallel search with consequential reconstruction. Apparent agreement about
adjacent mechanisms cannot be treated as convergent support for C-002.

### Precision

**Adequate for further investigation, inadequate for a public empirical
conclusion.** The three components can be stated separately. C-002 remains
underspecified regarding population, context, materiality threshold, unit of
reasoning, time horizon and acceptable outcome measures.

### Bias and alternatives

**Material and unresolved.** Confirmation bias is a first-order risk because
C-002 motivates OME. Plausible alternatives include initial absence of shared
reasoning, changed context, staffing disruption, coordination, incentives,
workload, absorptive capacity, causal ambiguity, implementation failure,
ordinary discovery and beneficial re-evaluation. The evidence does not yet
discriminate among them.

### Reproducibility

**Mixed.** The repository records search and source-selection provenance,
full-text appraisals and independent reviews. E-006 through E-008 remain
incomplete, the Stage A search was exploratory rather than fully reproducible,
and no frozen focused review has tested the compound claim.

## Disposition analysis

| Candidate disposition | Assessment | Reason |
| --- | --- | --- |
| `Retain` | Not justified | Current wording implies a relationship for organisations generally; no direct evidence establishes the complete sequence, scope or materiality. |
| `Narrow` | Premature | The record suggests software decision-rationale and requirements contexts may be closest, but it does not establish a bounded population or effect that can responsibly be retained. |
| `Revise` | Plausible later, not yet determined | The construct may ultimately be better represented as separate mechanism and outcome propositions or by established terms. Current evidence cannot select the defensible replacement. |
| `Reject` | Not justified | Absence of direct evidence is not evidence of absence. Recovery and rework observations keep the possibility open even though they do not validate the claim. |
| `Defer` | Best fit | Evidence is indirect and fragmented, alternatives remain unresolved, three records are incomplete, and no study links all required components. |

## Why the construct remains researchable

Deferral does not require abandoning the construct. It remains researchable
because:

- its three components can be defined without relying on OME terminology;
- adjacent constructs and exclusions are sufficiently mapped to avoid obvious
  category errors;
- candidate direct observations and outcomes can be distinguished from proxies;
- the evidence record identifies tests that could narrow, revise or reject it;
  and
- no established construct in the current review has yet been shown to subsume
  the entire sequence.

**Researchability is a property of the construct specification, not evidence
for the construct.** This is a methodological conclusion about whether the
question can be investigated, not a probability judgement or novelty claim.
Failure to find a unified established term in an exploratory review does not
demonstrate that the construct or label is new.

## Scope that remains unavailable

The assessment cannot responsibly conclude:

- that consequential reconstruction is common, costly or strategically
  important;
- that unavailable reasoning causes observed delay, rework, error or degraded
  decisions;
- that documentation, traceability or memory practices would prevent it;
- that the mechanism generalises beyond any studied context;
- that benefits exceed the costs of preserving and retrieving reasoning;
- that the construct is distinct enough to warrant new terminology;
- that C-002 supports C-003, C-004 or any product proposition; or
- that OME has identified a gap not adequately addressed by existing practice.

## What would change the disposition

A later assessment could move from `Defer` if independently appraised evidence:

- traces specific reasoning that was previously organisationally available;
- observes or validates later inability to retrieve or apply that reasoning;
- identifies reconstruction work separately from ordinary discovery, execution
  and changed-context re-evaluation;
- measures material consequences with a stated threshold and scope;
- tests credible alternatives and beneficial cases;
- establishes a bounded population or context in which the sequence recurs;
- shows that an established construct already explains the sequence, supporting
  revision or rejection; or
- demonstrates that the components cannot be measured without circularity,
  supporting rejection or substantive revision.

Full appraisal of E-006 through E-008 could also require reassessment, but their
completion alone would not determine a disposition.

## Proposed repository consequence

If this assessment is independently approved, a separate mechanical state
transition may record:

- C-002 as `Assessed` with disposition `Defer`;
- confidence as `Very low`;
- classification remaining `Hypothesis`; and
- the explicit evidence gaps and reopening conditions.

No such state change is made by this proposal. Approval would not authorise
Stage B, admit terminology, create canon or imply that C-002 has empirical
support.

## What would convince us we are wrong?

The proposed deferral would be wrong if the existing record has been materially
misread - for example, if a reviewed or incomplete source already establishes
all three components with a defensible consequence measure - or if the three
components cannot in fact be distinguished from an established construct or
operationalised without circular reasoning.

The Evidence Reviewer should challenge both possibilities rather than review
only whether the proposed `Defer` decision is cautious.

## CTO Independent Construct Review

Status: complete.

- **Evidence fidelity:** accurate. The assessment does not overstate the
  recovery, rework or boundary evidence and preserves E-006 through E-008 as
  explicit uncertainty.
- **Construct distinguishability:** sufficient for assessment. The three-part
  decomposition is coherent and distinguishable enough to remain researchable,
  but is not empirically established.
- **Operationalisability:** sufficient for continued hypothesis development.
  Population, materiality threshold, unit of reasoning, outcome measures and
  time horizon remain unresolved.
- **Alternative explanations:** adequately represented. Changed context,
  staffing, absorptive capacity, coordination, causal ambiguity, discovery,
  implementation failure and beneficial re-evaluation remain viable.
- **Proposed confidence:** `Very low` - supported because direct evidence is
  absent, the sequence is incomplete, alternatives remain viable and three
  records remain incompletely appraised.
- **Proposed disposition:** `Defer` - supported. `Retain` and `Reject` would
  overstate the record; `Narrow` and `Revise` would require selecting an
  unsupported direction.
- **Independent decision:** approve.
- **Required corrections:** none. A non-blocking clarification that
  researchability is not evidence for the construct was recommended and
  incorporated.

## Accountable decision

Status: pending founder approval.
