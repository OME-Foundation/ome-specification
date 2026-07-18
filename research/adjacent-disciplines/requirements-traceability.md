# Requirements traceability

## Established definition and frameworks

### Source findings

Requirements engineering already treats traceability as the ability to follow
the life of a requirement forwards and backwards: to its origins, refinement,
design, implementation, verification, and change. ISO/IEC/IEEE 29148 defines
requirements processes and information items across the system and software
life cycle. Research and practice distinguish pre-requirements and
post-requirements traceability, trace links, trace matrices, impact analysis,
coverage, and orphan requirements.

Empirical work on requirements communication shows that organisational,
geographical, cognitive, and temporal distance can produce missing or
misunderstood requirements and costly rework.

### OME interpretation

OME must adopt requirements traceability, bidirectional traceability, coverage,
impact analysis, and orphan detection rather than rename them. The founding
objective-to-decision-to-requirement-to-work-item chain is an extension of
traceability scope toward reasoning and evidence, not a wholly new concept.

## Problems handled well

- Demonstrating requirement origin and downstream satisfaction.
- Change-impact analysis and coverage assessment.
- Auditability in regulated engineering.
- Identifying missing links between specification, design, code, and tests.

## Limitations relevant to OME

Trace links can be expensive to create and maintain, become stale, and record
that two artefacts are related without capturing why. Conventional schemes
often begin at a documented stakeholder requirement, after substantial business
reasoning has already occurred.

## OME overlap and possible gap

| Founding idea | Assessment |
| --- | --- |
| Objective-to-implementation traceability | **Established/Synthesis** depending on scope. |
| Trace decisions and rejected alternatives | **Synthesis** with decision rationale and provenance. |
| Backlog items without business origins are risky | **Hypothesis**, testable against outcomes. |
| A trace link proves shared understanding | **Discard**; links do not prove comprehension or correctness. |

## Primary and authoritative sources

- ISO/IEC/IEEE. 2018. *29148:2018 Systems and software engineering — Life
  cycle processes — Requirements engineering*.
  https://www.iso.org/standard/72089.html
- Bjarnason, Elizabeth, and Helen Sharp. 2017. “The Role of Distances in
  Requirements Communication: A Case Study.” *Requirements Engineering* 22:
  1–26. https://doi.org/10.1007/s00766-015-0233-3
