# Behavioral Interoperability Testing Ontology (BITO)

The Behavioral Interoperability Testing Ontology (BITO) provides an ontology-based representation layer for behavioral interoperability testing. It represents expected scenario behavior, observed execution evidence, behavioral constraints, trace evidence, validation results, and interoperability verdicts. BITO complements domain ontologies with testing-specific concepts needed to represent behavioral interoperability testing scenarios, execution evidence, and assessment outcomes for interacting systems.

## Ontology Metadata

| Metadata | Value |
| --- | --- |
| **Ontology name** | Behavioral Interoperability Testing Ontology |
| **Acronym** | BITO |
| **Preferred prefix** | `bito` |
| **Ontology IRI** | <https://w3id.org/bito> |
| **Namespace** | <https://w3id.org/bito#> |
| **Version** | `1.0.0` |
| **DOI** | <https://doi.org/10.5281/zenodo.23111388> |
| **Zenodo archive** | <https://zenodo.org/records/23111388> |
| **License** | [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE) |
| **Repository** | <https://github.com/trialog/Behavioral-Interoperability-Testing-Ontology> |
| **Citation metadata** | [`CITATION.cff`](CITATION.cff) |

## Ontology

The BITO ontology files are available in the [`ontology/`](ontology/Behavioral_Interoperability_Testing_Ontology.ttl) directory.

---

## Ontology Development

BITO was developed following the **[Linked Open Terms (LOT)](https://lot.linkeddata.es/)** methodology. Competency questions, available in [`competency-questions/`](competency-questions/CQs.txt), were used to specify the ontology requirements. Existing ontologies and vocabularies were reviewed for reuse, and BITO-specific classes and properties were introduced where suitable reusable terms were not identified.

---

## Reused Ontologies

BITO reuses terms from **[SAREF](https://saref.etsi.org/core/v4.1.1/)**, **[SAREF4ENER](https://saref.etsi.org/saref4ener/v2.1.1/)**, **[PROV-O](https://www.w3.org/TR/prov-o/)**, and **[OWL-Time](https://www.w3.org/TR/owl-time/)** where their semantics match the intended meaning. BITO defines additional classes and properties for behavioral interoperability testing concepts not covered by the reused terms.

---

## Conceptual Diagram

The BITO conceptual diagram is available in [`conceptual-diagram/`](conceptual-diagram/Conceptual%20Diagram%20(BITO).png). It provides a visual representation of the principal concepts and relationships in BITO and shows how BITO-specific concepts relate to terms reused from external ontologies.

---

## Competency Questions

The competency questions used to specify BITO's ontology requirements are available in [`competency-questions/`](competency-questions/CQs.txt). They express the questions that should be answerable using the ontology, covering expected scenario behavior and observed execution evidence.

---

## SPARQL and Description Logic (DL) Queries

The SPARQL and Description Logic (DL) queries used during ontology evaluation are available in [`sparql-dl-queries/`](sparql-dl-queries/sparql%20queries/SPARQL_Queries.rq). SPARQL queries were used to assess whether the competency questions could be answered over a representative test graph, while selected DL queries were used to check expected inferred relationships and class memberships within the ontology.

---

## Ontology Evaluation

Evaluation resources are available in [`ontology-validation/`](ontology-validation/). BITO was evaluated through competency-question assessment using SPARQL queries, Description Logic query checks, logical consistency checking with the **[HermiT reasoner](http://www.hermit-reasoner.com/)**, and ontology pitfall detection using **[OOPS! (OntOlogy Pitfall Scanner!)](https://oops.linkeddata.es/)**.

---

## Documentation

Ontology documentation is available in [`documentation/`](documentation/). It provides a browsable description of the ontology terms and structure. The documentation was generated using **[WIDOCO](https://dgarijo.github.io/Widoco/doc/tutorial/)**.

---

## Citation

If you use BITO, please cite:

```text
Chy, T. M. R. H., Bouter, C., & Daniele, L. (2026). Behavioral Interoperability Testing Ontology (BITO) (Version 1.0.0). Zenodo. https://doi.org/10.5281/zenodo.23111388
```

Citation metadata is available in [`CITATION.cff`](CITATION.cff).

**Zenodo archive:** <https://zenodo.org/records/23111388>

---

## Project and Funding

BITO has been developed in the context of the [HEDGE-IoT](https://hedgeiot.eu/) project, funded by the European Union's Horizon Europe research and innovation programme under Grant Agreement No. 101136216.

---

## Maintainers and Contributors

**Trialog, Paris, France**  
BITO ontology maintenance and technical coordination.  
**Primary contact:** Tareq Md Rabiul Hossain Chy

**TNO – Netherlands Organisation for Applied Scientific Research, The Hague, The Netherlands**  
Ontology co-development, technical guidance, and review.  
**Contributors:** Cornelis Bouter and Laura Daniele

---

## License

The Behavioral Interoperability Testing Ontology (BITO) is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. See [`LICENSE`](LICENSE) for the complete license terms.
