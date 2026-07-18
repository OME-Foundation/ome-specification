# Knowledge graphs and semantic modelling

## Established definition and frameworks

### Source findings

Knowledge graphs represent entities and relationships in graph form, often with
schemas or ontologies that define meaning and constraints. RDF models
information as subject-predicate-object triples; RDF datasets, named graphs,
RDFS, OWL, SHACL, and SPARQL support semantics, validation, and querying.
Property graphs offer a different graph model. The term “knowledge graph” has
no single universally accepted formal definition.

Semantic modelling already supplies identity, classes, relations, constraints,
inference, interoperability, and ontology-alignment methods. W3C PROV can be
represented in RDF rather than replaced by an OME-specific provenance system.

### OME interpretation

An OME graph is an implementation option, not the discipline's definition. The
public canon should specify conceptual semantics and competency questions
before choosing RDF, property graphs, or a database. It should reuse PROV-O and
other vocabularies where possible and publish mappings for any extension.

Automated extraction creates candidate claims, not authoritative knowledge.
Identity resolution, temporal validity, contradiction, uncertainty, and human
governance remain hard problems.

## Problems handled well

- Integrating heterogeneous structured knowledge.
- Traversing multi-hop relationships and provenance.
- Providing explicit semantics and validation constraints.
- Supporting interoperability and machine-readable models.

## Limitations relevant to OME

Graphs do not guarantee truth, completeness, shared understanding, or useful
granularity. Ontology development is costly; inference can magnify modelling
errors; temporal and contested claims require deliberate representation.

## OME overlap and possible gap

| Founding idea | Assessment |
| --- | --- |
| Canonical knowledge graph model | **Synthesis/implementation choice**. |
| Every organisational claim is an entity | **Open question**; reification costs matter. |
| Contradictions should coexist with provenance | **Principle/Synthesis**. |
| AI-extracted graph equals organisational truth | **Discard**. |

## Primary and authoritative sources

- W3C. 2014. *RDF 1.1 Concepts and Abstract Syntax*.
  https://www.w3.org/TR/rdf11-concepts/
- W3C. 2012. *OWL 2 Web Ontology Language Document Overview*, second edition.
  https://www.w3.org/TR/owl2-overview/
- Hogan, Aidan, et al. 2021. “Knowledge Graphs.” *ACM Computing Surveys*
  54(4), Article 71. https://doi.org/10.1145/3447772
