# GraphRAG-Knowledge-Graph-Extraction-Pipeline

##  Project Objective
This project implements an advanced Information Extraction (IE) pipeline—GraphRAG—designed to transform unstructured text into semantic Knowledge Graphs. The primary goal is to structure data to mitigate LLM hallucinations when querying complex knowledge bases.

##  Technical Stack
* **Language:** Python
* **Extraction & Structuring:** LLMs, Instructor, and Pydantic for strict JSON schema validation
* **Semantic Web:** Ontology modeling using RDF/OWL standards
* **Graph Databases:** Integration with Stardog and AllegroGraph

##  Key Features
* Automated ingestion of raw text data.
* Ontology-guided entity and relationship extraction.
* RDF triplet generation and validation.
* Knowledge indexing for semantic querying via SPARQL.

##  Main File
* `pipeline_extraction_v2.ipynb`: A comprehensive notebook covering the entire workflow, from data ingestion to graph generation.
