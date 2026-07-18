# Synthesis and gap analysis

## Status and recommendation

This document is a research recommendation, not accepted OME canon. The review does not yet support presenting OME as a new scientific discipline or any proposed metric as validated. It does support developing OME as a coherent engineering synthesis: a method for preserving, connecting, retrieving, challenging and revising organisational reasoning across delivery lifecycles.

The strongest candidate gap is not organisational memory itself. It is the practical integration of organisational-memory theory, learning loops, knowledge-boundary work, requirements traceability, decision rationale, provenance, socio-technical design and semantic representation into an evidence-backed, temporal chain from objectives to outcomes and subsequent learning.

## What OME inherits

These concepts should be used with their established names and cited foundations.

| Inherited concept | Source discipline | Consequence for OME |
|---|---|---|
| Acquisition, retention and retrieval of organisational information | Organisational memory | Use as the basic memory lifecycle; do not claim it as an OME invention. |
| Organisational routines and other retention media | Organisational memory and learning | Treat repositories as only one part of memory. |
| Single-loop and double-loop learning; exploration and exploitation | Organisational learning | Distinguish correcting action from revising governing assumptions. |
| Tacit and explicit knowledge; knowledge creation and transfer | Knowledge management | Do not imply that all consequential knowledge can be captured as documents. |
| Syntactic, semantic and pragmatic knowledge boundaries; grounding; knowledge-transfer stickiness | Organisation studies and communication research | Use these constructs when diagnosing loss of meaning across groups. |
| Requirements traceability and traceability links | Requirements engineering | Reuse its vocabulary and evidence practices. |
| Architecture decision records and rationale | Software and enterprise architecture | Reuse records and explicit status/supersession rather than inventing another document type. |
| Entity, activity, agent, derivation, attribution and generation | Provenance | Adopt W3C PROV semantics where applicable. |
| Joint cognitive systems, distributed cognition and work-as-performed | Cognitive systems engineering | Design memory practices around people, tools and authority together. |
| Stakeholders, concerns, viewpoints, views and architecture governance | Enterprise architecture | Align with existing governance and modelling practices. |
| RDF graphs, ontologies and semantic entailment | Semantic modelling | Use standards where machine-readable relationships are justified. |

## What OME synthesises

OME can legitimately name a synthesis when it makes the combination precise and useful. The candidate synthesis is:

1. preserve objectives, assumptions, alternatives, decisions and evidence—not merely outputs;
2. connect them bidirectionally to requirements, implementation, operational outcomes and learning;
3. represent authorship, derivation, time, status, contradiction and supersession;
4. make gaps and stale claims inspectable without treating automated inference as truth;
5. assign human authority for consequential decisions and corrections; and
6. evaluate whether the system improves retrieval, explanation, challenge and adaptation in real work.

No reviewed discipline supplies that entire delivery-oriented package. Each supplies substantial parts. OME should therefore describe the package as a **synthesis**, not portray its constituents as novel discoveries.

## What may remain genuinely novel

No founding term is demonstrated to be genuinely novel merely by this review. The following are research opportunities rather than established claims:

- a validated, cross-lifecycle model connecting organisational intent, delivery evidence, outcomes and learning;
- measures that predict consequential failures better than existing traceability, documentation-quality or knowledge-management measures;
- governance patterns for machine-assisted reconstruction of organisational reasoning with explicit uncertainty and human authority; and
- evidence that the combined method produces benefits exceeding those of its constituent practices.

Novelty would require a precise construct, a comparison against prior work and empirical evidence. Until then, these are **novel proposals** or **hypotheses**, not findings.

## Classification of proposed OME concepts

The classification applies to the concepts as presently understood from the founding drafts. It should be revised as definitions and evidence improve.

| Proposed concept | Classification | Assessment |
|---|---|---|
| Organisational memory | Established | A mature research construct; OME inherits it. |
| Organisational learning | Established | A mature research field; OME inherits it. |
| Acquisition, retention and retrieval | Established | Established organisational-memory processes. |
| Requirements traceability | Established | Standard requirements-engineering practice and terminology. |
| Decision records and rationale | Established | Established practice, though implementation maturity varies. |
| Data/knowledge provenance | Established | Standardised conceptual vocabulary exists in W3C PROV. |
| Preserve reasoning as well as artefacts | Principle | Normative design choice assembled from rationale, provenance and memory research. |
| Human authority for consequential decisions | Principle | Normative socio-technical constraint, not a discovered law. |
| Objective-to-outcome-to-learning chain | Synthesis | Combines established traceability, provenance, rationale and learning concepts. |
| Translation Loss | Synthesis | A useful umbrella only if mapped to established boundary, grounding, transfer and requirements-communication constructs. |
| Translation Loss Index | Hypothesis | No defensible measurement model or validation has yet been supplied. |
| Decision Lineage | Synthesis | Currently a convenient label for decision provenance plus traceability, rationale, time and supersession. |
| Memory Debt | Hypothesis | Possible construct, but presently overlaps knowledge, documentation, intent and technical debt. |
| Knowledge Half-Life | Hypothesis / Open question | Could become measurable only after specifying what decays and under what model. |
| Organisational Memory Index | Hypothesis / Open question | A scalar composite is premature before construct and measurement validation. |
| The Seven Laws | Principles | Normative propositions should not be called laws without strong invariant empirical support. |
| Organisational Memory Engineering as a discipline | Hypothesis / Novel proposal | It is currently better described as an engineering synthesis and research programme. |

## Evaluation of the founding terms

### Translation Loss

**Finding.** Shannon's information theory formalises uncertainty and channel capacity while deliberately excluding semantic meaning from the engineering problem. Organisation and communication research already describes several mechanisms closer to the OME concern: failures of grounding, syntactic/semantic/pragmatic knowledge boundaries, knowledge-transfer stickiness, and communication gaps between requirements and development.

**Interpretation.** “Translation Loss” does not denote one recognised construct with a single accepted measure. It is a plain-language umbrella over several established phenomena. It adds value only if it directs diagnosis to those mechanisms instead of obscuring them.

**Recommendation: retain provisionally, narrow and map.** Define it as an umbrella diagnostic label for consequential change, omission or misalignment of intended meaning as knowledge crosses people, representations, tools, teams or lifecycle stages. Do not equate it with Shannon entropy. Do not assume losses are additive or reducible to one percentage. Rename a proposed “Translation Loss Index” to a plural **translation-loss diagnostic profile** until measurement validity exists.

### Decision Lineage

**Finding.** Traceability links artefacts across a lifecycle; provenance records entities, activities, agents and derivations; decision records preserve decision context, alternatives, rationale and status. Temporal and supersession relationships are also established modelling capabilities.

**Interpretation.** The present idea combines these practices but has not shown a categorical distinction from them. It can still be useful shorthand for a specific graph-shaped view centred on decisions.

**Recommendation: rename formally; retain only as shorthand.** Use **decision provenance and traceability** in definitions and research. “Decision lineage” may remain a user-facing view if it includes at least rationale, evidence, derivation, affected artefacts, outcomes, status, contradiction and supersession. Those semantics—not the label—would supply its value.

### Memory Debt

**Finding.** Technical debt already describes future cost created by expedient technical choices. Documentation debt and knowledge debt are used for related deficiencies, while recent work also discusses cognitive or intent debt. The vocabulary is less standardised than technical debt, but the conceptual territory is occupied.

**Interpretation.** “Memory Debt” currently risks grouping missing documentation, lost rationale, inaccessible expertise, stale assertions, weak traceability and obsolete systems into one metaphor. That reduces rather than increases diagnostic precision. A debt metaphor also implies a present obligation, accumulating consequences and a plausible remediation cost; simple absence is not necessarily debt.

**Recommendation: discard as a founding term for now.** Use the specific established or descriptive term—knowledge gap, documentation debt, traceability gap, obsolete knowledge, inaccessible expertise, intent loss or technical debt. Reconsider **organisational memory debt** only if it can be defined as a measurable remediation obligation not adequately represented by those constructs and shown to predict future cost or risk.

### Knowledge Half-Life

**Finding.** Half-life is rigorous only when a defined quantity follows a specified decay process. Bibliometrics sometimes measures citation aging or cited half-life; that is not the same as the useful life of organisational knowledge. Organisational knowledge may decay gradually, become invalid abruptly, remain dormant, be corrected, or increase in value.

**Interpretation.** A universal half-life is indefensible. A bounded empirical measure might be possible for a specified population of claims and a specified outcome, such as probability of remaining valid, retrievable or correctly applied after time _t_. Exponential decay cannot be assumed.

**Recommendation: discard as a core metric; retain the research question.** Prefer **knowledge-validity decay**, **retrievability decay** or **applicability decay**, whichever is actually measured. Any study must state the population, time origin, event/outcome, censoring rules, context changes and fitted survival/decay model.

### Organisational Memory Index

**Finding.** This review found no accepted scalar Organisational Memory Index. Composite indices require a defined construct, justified dimensions and weights, normalisation rules, reliability, convergent and discriminant validity, sensitivity analysis and evidence about incentives and gaming.

**Interpretation.** Acquisition, retention, retrieval, validity, accessibility, traceability and learning are distinct properties. Collapsing them now would conceal failure modes and create false comparability between organisations.

**Recommendation: defer.** Begin with a transparent **organisational-memory diagnostic profile** containing separately reported measures and qualitative evidence. Consider a composite index only after the dimensions independently demonstrate validity and a real decision requires aggregation.

## Retain, rename or discard

| Founding term | Recommendation | Preferred treatment now |
|---|---|---|
| Organisational Memory Engineering (OME) | Retain provisionally | Name the engineering synthesis and research programme, not a proven new discipline. |
| Translation Loss | Retain provisionally | Umbrella diagnostic label explicitly mapped to established constructs. |
| Translation Loss Index | Rename/defer | Translation-loss diagnostic profile; no scalar index yet. |
| Decision Lineage | Rename formally | Decision provenance and traceability; optional shorthand for a defined decision-centred view. |
| Memory Debt | Discard for now | Use the particular gap or established debt category. |
| Knowledge Half-Life | Discard as metric | Retain bounded questions about validity, applicability or retrievability decay. |
| Organisational Memory Index | Defer | Multidimensional diagnostic profile. |
| Seven Laws | Rename | OME principles or propositions until evidence warrants stronger language. |

## Research and validation agenda

Public canon should wait for at least the following work:

1. Define the unit of analysis: claim, decision, rationale, trace link, retained expertise, routine, team or organisation.
2. Publish a concept map aligning every OME term with established terms and noting narrower or broader scope.
3. Specify a minimal objective-to-learning information model using existing provenance and traceability semantics where possible.
4. Create separate, observable measures for retrieval success, explanation quality, validity, trace coverage, contradiction handling and time-to-recover context.
5. Test those measures for inter-rater reliability and construct validity before aggregation.
6. Compare an OME intervention against ordinary ADR, traceability and knowledge-management practice rather than against no practice.
7. Record failure cases, including where capture cost exceeds benefit, sensitive context should not be retained, or formalisation suppresses useful ambiguity.
8. Treat AI-extracted claims and links as candidates with source, confidence and review status—not as institutional truth.

## Sources supporting the synthesis

- Richard L. Daft and Karl E. Weick, “Toward a Model of Organizations as Interpretation Systems,” *Academy of Management Review* 9, no. 2 (1984): 284–295. https://doi.org/10.5465/amr.1984.4277657
- James G. March, “Exploration and Exploitation in Organizational Learning,” *Organization Science* 2, no. 1 (1991): 71–87. https://doi.org/10.1287/orsc.2.1.71
- James P. Walsh and Gerardo Rivera Ungson, “Organizational Memory,” *Academy of Management Review* 16, no. 1 (1991): 57–91. https://doi.org/10.5465/AMR.1991.4278992
- Claude E. Shannon, “A Mathematical Theory of Communication,” *Bell System Technical Journal* 27 (1948): 379–423, 623–656. https://doi.org/10.1002/j.1538-7305.1948.tb01338.x
- Paul R. Carlile, “Transferring, Translating, and Transforming: An Integrative Framework for Managing Knowledge Across Boundaries,” *Organization Science* 15, no. 5 (2004): 555–568. https://doi.org/10.1287/orsc.1040.0094
- Gabriel Szulanski, “Exploring Internal Stickiness: Impediments to the Transfer of Best Practice Within the Firm,” *Strategic Management Journal* 17, Winter Special Issue (1996): 27–43. https://doi.org/10.1002/smj.4250171105
- World Wide Web Consortium, *PROV-DM: The PROV Data Model*, W3C Recommendation, 30 April 2013. https://www.w3.org/TR/prov-dm/
- ISO/IEC/IEEE 29148:2018, *Systems and software engineering—Life cycle processes—Requirements engineering*. https://www.iso.org/standard/72089.html
- ISO/IEC/IEEE 42010:2022, *Software, systems and enterprise—Architecture description*. https://www.iso.org/standard/74393.html
- Michael Nygard, “Documenting Architecture Decisions,” 15 November 2011. https://www.cognitect.com/blog/2011/11/15/documenting-architecture-decisions
- Erik Hollnagel and David D. Woods, *Joint Cognitive Systems: Foundations of Cognitive Systems Engineering* (Boca Raton: CRC Press, 2005).
- Aidan Hogan et al., “Knowledge Graphs,” *ACM Computing Surveys* 54, no. 4 (2021), article 71. https://doi.org/10.1145/3447772
