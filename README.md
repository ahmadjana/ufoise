# UFO-based RDF Data Generator and Index

This repository contains the **UFO-based Data Generator (UDG)** and indexing tools for generating and managing large RDF datasets grounded in the **Unified Foundational Ontology (UFO)**. The generator produces synthetic RDF triples compliant with UFO foundational categories, stored in triple stores and efficiently indexed using a UFO-aligned indexing strategy. This setup enables semantic-aware querying and benchmarking of SPARQL engines over conceptually rich ontologies.

---

## Features

- **UFO-Compliant RDF Data Generator**  
  Generates instances of UFO foundational entities such as `Person` (Agents), `Action` (Events), and `Trope` (Qualities), including nested event structures and richly attributed entities.

- **Configurable Data Generation**  
  Supports scaling factors and parameters controlling the size and complexity of generated data (number of participants, event depth, trope counts, etc.).

- **Semantic UFO-based Index**  
  Indexes RDF triples according to UFO foundational distinctions (e.g., Endurants vs. Perdurants) to improve query performance on ontology-aligned queries.

- **Integration with JOPA**  
  Utilizes JOPA, a Java persistence API for OWL ontologies, for programmatic creation and management of ontology instances.

- **[SHACL Validator](https://github.com/kbss-cvut/ufo-validator)**  
  Provides validation rules to ensure real-world or synthetic RDF datasets conform to the UFO structure and constraints required by the benchmark.

---

## Getting Started

### Prerequisites

- Java 8+  
- Maven (for building the generator and related tools)  
- A triple store supporting RDF and SPARQL (e.g., Virtuoso, Fuseki, Blazegraph)  
- [JOPA](https://github.com/kbss-cvut/jopa) for ontology persistence  

### Installation

Clone the repository:

```bash
git clone https://github.com/ahmadjana/ufomodel.git
cd ufomodel
