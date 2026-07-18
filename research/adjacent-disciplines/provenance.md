# Data and knowledge provenance

## Established definition and frameworks

### Source findings

Provenance records the entities, activities, and agents involved in producing,
deriving, or influencing something. The W3C PROV family supplies a domain-
independent data model and an OWL ontology (PROV-O) for interoperable provenance
representations. Its central relations include generation, use, derivation,
attribution, association, and delegation.

Data lineage is commonly narrower and system-oriented: where data originated,
how it moved, and which transformations produced a result. Knowledge provenance
extends concern to claims, sources, derivation, responsibility, and context.

### OME interpretation

OME should adopt W3C PROV concepts wherever compatible and extend them only for
clearly defined organisational reasoning needs. “Every assertion cites its
evidence” is a **Principle** implemented using established provenance patterns,
not a novel law.

Provenance does not itself establish truth. A perfectly traceable claim may be
wrong, biased, stale, or circular. OME must keep provenance, confidence,
validation status, and outcome evidence distinct.

## Problems handled well

- Reconstructing derivation and responsibility.
- Supporting reproducibility, audit, attribution, and interchange.
- Representing transformations rather than only static citations.

## Limitations relevant to OME

Generic provenance models do not decide which organisational decisions matter,
whether evidence is persuasive, whether participants shared an interpretation,
or whether an outcome validated the reasoning. Granular provenance can also be
costly and privacy-sensitive.

## OME overlap and possible gap

| Founding idea | Assessment |
| --- | --- |
| Provenance as a first-class concern | **Established/Principle**. |
| Trust equals provenance | **Discard**; provenance is evidence about origin, not trust itself. |
| Immutable history with supersession | **Synthesis** of provenance and versioning. |
| Contradicting evidence must remain visible | **Principle**. |
| Provenance-weighted trust score | **Hypothesis** requiring calibration and validation. |

## Authoritative sources

- W3C. 2013. *PROV-O: The PROV Ontology*, W3C Recommendation.
  https://www.w3.org/TR/2013/REC-prov-o-20130430/
- W3C. 2013. *PROV-DM: The PROV Data Model*, W3C Recommendation.
  https://www.w3.org/TR/prov-dm/
