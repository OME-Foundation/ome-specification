# Phase 1 research operating system

Status: proposed research governance; not accepted OME canon.

## Objective

Phase 1 must determine whether organisations experience a consequential problem
that existing disciplines address only partially, and whether an integrated
engineering approach could measurably improve it.

This operating system makes that work inspectable. It does not presuppose that
the gap exists or that OME is the correct response.

## Core records

```text
Research item (R-###)
        investigates
Claim (C-###)
        is assessed using
Evidence record (E-###)
        may support, conflict with, or be inconclusive about
Claim (C-###)
```

- The [Claim Register](CLAIMS.md) is the inventory of material propositions and
  their current classifications and dispositions.
- The [Evidence Register](EVIDENCE.md) records sources and observations in a
  form that preserves provenance, scope, relevance and direction.
- The [Research Backlog](BACKLOG.md) records bounded investigations needed to
  resolve claims or important open questions.
- [Confidence and decision rules](DECISION_RULES.md) define how evidence changes
  a claim's status without converting judgement into a misleading score.
- [Templates](templates/README.md) define the minimum fields for new records.

## Identifier rules

Identifiers are stable and never reused:

| Record | Pattern | Example |
| --- | --- | --- |
| Claim | `C-###` | `C-001` |
| Evidence | `E-###` | `E-001` |
| Research item | `R-###` | `R-001` |

Records are never deleted. Their lifecycle status changes and their history is
retained. Renaming a concept, correcting a source or superseding a record does
not change or reuse its identifier.

## Relationships

Relationships are explicit and bidirectional:

- every evidence record names each claim it bears on and its direction for that
  claim;
- every evidence record has an independent lifecycle and change history;
- every claim lists its evidence and relevant research items;
- every research item identifies the claims or open questions it investigates;
- completing a research item does not automatically change a claim; the
  resulting evidence must be registered and reviewed; and
- a document may cite a claim, but a document is not itself evidence merely
  because it exists in this repository.

## Evidence directions

For each claim, an evidence record has exactly one current direction:

- **Supporting**: increases the plausibility of the claim within the evidence's
  stated scope.
- **Conflicting**: decreases the plausibility of the claim or supports a
  materially incompatible explanation.
- **Inconclusive**: is relevant but cannot discriminate between the claim and
  plausible alternatives.
- **Contextual**: defines, bounds or explains the claim without testing it.

Absence of conflicting evidence is not supporting evidence. The same source may
have different directions for different claims.

## Workflow

1. Register a material claim or open question before writing conclusions around
   it.
2. Classify it using the [claim-classification standard](../CLAIM_CLASSIFICATION.md).
3. Search adjacent disciplines and register relevant evidence, including
   counter-evidence and null findings.
4. Create a bounded research item when the current evidence cannot answer a
   material question.
5. Review provenance, relevance, limitations and alternative explanations.
6. Apply the confidence and decision rules; record the reasoning rather than
   only the outcome.
7. Publish a research conclusion only at the scope supported by the evidence.
8. Consider canon separately. Research acceptance is necessary but not
   sufficient for canonisation.

## Public and private boundary

Public records include reviewed research questions, methods, claim assessments,
evidence and counter-evidence that can be disclosed responsibly. Private
incubation includes unreviewed notes and cultural exploration. Private company
records include customer information, product strategy, security, architecture,
implementation and commercial work.

Evidence that cannot be published must not be laundered into a public claim.
The public record may state that undisclosed evidence exists only when doing so
does not expose protected information, and it must not ask readers to treat that
evidence as independently verifiable.

## Change policy

Changes to identifiers, required fields, evidence directions, confidence rules,
decision rules or canon-admission criteria require pull-request review. Examples
are explicitly marked and must not be treated as validated findings.
