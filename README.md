# ICD-10 Ontology Module

The **ICD-10 Ontology Module** is a domain-specific extension of the [Meta Mesh Ontology (MMO)](https://github.com/MetaMeshOntology/meta-mesh-ontology). It focuses on the semantic representation of diagnostic categories, clinical syndromes, and symptom hierarchies in alignment with the International Classification of Diseases, 10th Revision (ICD-10). The module is based on the [Core Domain Framework (CDF)](https://github.com/MetaMeshOntology/core-domain-framework) and fully aligns with the architectural and ontological principles of the MMO system.

## 🔍 Purpose and Scope

This module provides ontologically grounded classes for the **semantic modeling of diagnostic entities and clinical phenomena as defined in ICD-10**, including but not limited to:

- Mental and behavioral disorders (F-Codes)
- Somatic disease entities and syndromic clusters
- Cross-system symptom and comorbidity structures
- Links between diagnostic categories, etiological factors, and observable indicators

It supports **interoperable semantic modeling** across domains such as clinical medicine, psychiatry, epidemiology, and public health informatics.

## 🧠 Ontological Structure

The module follows the architecture of the MMO:

MMO Core Classes -> Core Domain Framework (CDF) -> ICD-10 Module Classes

All classes in this module:
- Are subclasses of appropriate CDF superdomain entities
- Follow the MMO class definition format based on the Two-Part Definition Rule
- Are annotated with rich metadata

Currently, the module provides the foundational ontology structure and includes five initial data points as proof of concept.
In future iterations, it will evolve toward a comprehensive integration of all relevant healing and recovery data points within the MMO framework.

## 🧪 Validation and FAIR Compliance

The ontology is:
- Syntax-validated with RDF validation tools
- Published in RDF/XML (OWL) format
- Released under a permissive Creative Commons license
- Designed for FAIR compliance

## 📖 Citation

If you use this ontology module in your work, please cite:

> Meta Mesh Ontology – ICD-10 Module  
> Version 1.0.0 (2025-09-20)  
> MetaMeshOntology GitHub  
> [https://github.com/MetaMeshOntology/ICD-10-module](https://github.com/MetaMeshOntology/ICD-10-module)  

## 🛠 Contributing

Contributions are welcome! Please open issues or submit pull requests via GitHub. All changes should conform to the naming conventions, definition rules, and modular structure of the MMO system.

## 📬 Contact

To get involved or reach out to the maintainers, join our [Slack Workspace](https://metameshontology.slack.com).  
You can directly join the ICD-10 discussion channel here: [#ICD-10-module](https://metameshontology.slack.com/archives/C09NQJYSH8U).  
Maintained by the [Meta Mesh Ontology Team](https://github.com/MetaMeshOntology).

---

## 📄 License

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]  
This work is licensed under a  
[Creative Commons Attribution 4.0 International License][cc-by].  

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/  
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png  
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

