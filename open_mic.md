# Overview of Thesis and UFO-based Data Generator

This document provides a concise explanation of my thesis research focused on semantic data management using foundational ontologies, along with the UFO-based RDF Data Generator developed to support this work.

---

## Thesis Summary

The core objective of my thesis is to improve the efficiency and semantic clarity of querying large RDF datasets grounded in foundational ontologies. Specifically, I leverage the **Unified Foundational Ontology (UFO)** to:

- Develop a semantically aware **indexing technique** for RDF triple stores,
- Design a benchmark of **foundational query patterns** aligned with UFO conceptual distinctions,
- Evaluate how semantic modeling influences SPARQL query performance across different triple stores.

This research bridges conceptual modeling and Semantic Web technologies by embedding rich ontological structures directly into RDF data management and querying.

---

## Role of the UFO-based Data Generator (UDG)

To experimentally validate my approach, I updated the **Data Generator (UDG)** to  **UFO-based Data Generator (UDG)**— a tool to generate synthetic RDF datasets that:

- Conform strictly to UFO foundational categories such as `Agent`, `Action`, `Trope`,
- Include complex event structures with participants and nested sub-events,
- Fully instantiate attributes and relationships to support comprehensive benchmarking,
- Scale in size and complexity based on configurable parameters.

The UDG ensures that the datasets used for benchmarking closely reflect the conceptual structures inherent in foundational ontologies, enabling meaningful evaluation of UFO-aware indexing and query optimization.

---

## Key Components and Technologies

- **UFO Ontology:** Provides the conceptual framework and categories that guide data generation and indexing.
- **JOPA:** A Java-based API used to programmatically create and persist ontology instances into RDF triple stores.
- **RDF Triple Stores:** Backend storage for generated data, supporting SPARQL queries and UFO-based indexing.
- **SHACL Validator:** Ensures datasets comply with UFO constraints, maintaining data quality for benchmarking.

---

## How This Fits Into the Thesis

- The UFO model grounds the semantic structure of the generated data, ensuring ontological soundness.
- Generated data is used to test the UFO-based indexing method, which partitions RDF triples by foundational categories to improve query performance.
- Benchmark queries are derived from common foundational patterns (e.g., event participation, trope inherence) to evaluate indexing effectiveness.
- The results demonstrate the benefits of integrating foundational ontologies into RDF data management.

---

## Further Reading

- Refer to the [full thesis document](link-to-your-thesis) for detailed explanations of the theoretical background, methodology, and experimental evaluation.
- Explore the [GitHub repository](https://github.com/ahmadjana/ufomodel) for the source code of the UFO-based Data Generator and indexing tools.

---

## Contact

For questions or collaboration inquiries, please contact:  
**Ing. Jana Ahmad**  
Email: ahmadjan@fel.cvut.cz  
GitHub: [github-profile](https://github.com/ahmadjana)

---

*This project is part of ongoing research in ontology-driven data management and semantic querying.*

