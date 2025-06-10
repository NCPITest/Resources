# Introduction to FHIR

Fast Healthcare Interoperability Resources (FHIR) is a standard for exchanging electronic healthcare information developed by Health Level Seven International (HL7).

FHIR defines data elements called **Resources**—such as `Patient`, `Observation`, or `Specimen`—and outlines their structure and sharing via web technologies like RESTful APIs, JSON, and XML. Its modular design supports interoperability across diverse health information systems.

## NCPI and FHIR

NCPI uses FHIR as a common standard for research data exchange, supporting the NCPI's goal of FAIR data principles (Findable, Accessible, Interoperable, and Re-usable). The work of the NCPI FHIR Working Group also focuses on defining an NCPI FHIR Implementation Guide to provide a common data model for describing NCPI data sets. This standardization simplifies the integration and analysis of data from varied research studies.

## NCPI FHIR Resources

- **NCPI FHIR Implementation Guide (IG)**  
  The *NCPI FHIR Implementation Guide v2* (NCPI FHIR IG v2) provides specifications, building blocks, interaction models, and use cases for FHIR within NCPI. It details study data structuring with specific FHIR Resource Types to ensure compliance and interoperability across NCPI platforms. A contributors guide is also available.

- **NCPI FHIR Aggregator**  
  The NCPI FHIR Aggregator is a centralized catalog for FHIR data from various biomedical resources, such as clinical data, research study information, and OMICS data tied to specimens. Researchers can use it to search for patient phenotypes and associated data across these diverse sources. Learn more about the [FHIR Aggregator].

- **fhir-query tool**  
  The `fhir-query` (or `fq`) command-line tool, a companion to the aggregator, simplifies interactions with FHIR servers. It assists in retrieving server vocabularies and executing queries to filter and pull FHIR resources.

- **Additional Tools**  
  The NCPI GitHub organization hosts additional FHIR tools and projects, such as a basic FHIR client and utilities for terminology mapping. Visit the NIH Cloud Platform Interoperability Program GitHub to learn more.

## Learn More

To learn more about FHIR and its research applications:

- [Introduction to FHIR for Research | Data Science at NIH]("https://datascience.nih.gov/fhir-initiatives/introduction-to-fhir-for-research")
- [FHIR for Researchers Training | Data Science at NIH]("https://datascience.nih.gov/fhir-initiatives/researchers-training")
