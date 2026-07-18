# Decision records and decision provenance

## Established definition and frameworks

### Source findings

Architecture Decision Records (ADRs) capture a significant decision together
with its context, status, and consequences. Michael Nygard's widely adopted
format keeps short records with the system so future maintainers can recover
rationale. Later templates add considered options, trade-offs, decision makers,
and confirmation. ISO/IEC/IEEE 42010 treats architecture descriptions as
structured expressions involving stakeholders, concerns, viewpoints, models,
and architecture decisions.

Decision-rationale and architectural-knowledge research predates and extends
the lightweight ADR practice. Requirements traceability and W3C provenance
already provide mechanisms for linking decisions to upstream and downstream
artefacts.

### OME interpretation

**Decision Lineage** is not clearly distinct enough to claim as a new primitive.
Its components are established: decision records, rationale, provenance,
traceability, version history, and impact analysis. The useful synthesis is a
time-aware graph connecting a decision to objectives, evidence, assumptions,
alternatives, authority, requirements, implementation, outcomes, and
superseding decisions.

Until that synthesis has a formal model and demonstrated use beyond existing
approaches, use **decision provenance and traceability** in research prose.
Retain “Decision Lineage” only as a provisional OME shorthand.

## Problems handled well

- Preventing repeated debate and rationale loss.
- Recording consequences and supersession.
- Keeping architectural knowledge close to implementation.
- Supporting audit and change-impact analysis when linked to other artefacts.

## Limitations relevant to OME

ADRs are commonly technical and manually maintained. They may omit pre-decision
business discussion, social authority, evidence quality, later operational
outcomes, and downstream links. A collection of ADRs is not automatically a
lineage graph.

## OME overlap and decision

| Founding idea | Assessment |
| --- | --- |
| Record decisions and rationale | **Established**. |
| Preserve superseded decisions | **Established/Principle**. |
| End-to-end decision provenance graph | **Synthesis**. |
| Decision Lineage as a novel field concept | **Not demonstrated**. |
| Outcome-validated decision history | **Synthesis/Hypothesis** depending on claimed benefit. |

## Primary and authoritative sources

- Nygard, Michael. 2011. “Documenting Architecture Decisions.” Cognitect.
  https://www.cognitect.com/blog/2011/11/15/documenting-architecture-decisions
- ISO/IEC/IEEE. 2022. *42010:2022 Software, systems and enterprise —
  Architecture description*. https://www.iso.org/standard/74393.html
- Architectural Decision Records community. *ADR Templates*.
  https://adr.github.io/adr-templates/
