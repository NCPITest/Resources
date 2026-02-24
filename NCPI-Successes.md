Since its inception in 2019, NCPI stakeholders have made significant strides to increase interoperability across the five NCPI partner sytems. A curated list of accompliments are detailed below. 

<h3> NCPI FHIR Implementation Guide, 2026</h3>

The NCPI FHIR working group has developed an guide for the implementation of FHIR as a metadata standard, improving upon [NCPI FHIR IG](https://nih-ncpi.github.io/ncpi-fhir-ig/). [Version 2](https://nih-ncpi.github.io/ncpi-fhir-ig-2/) is in active development as of February 2026. 

<h4> High Level Picture </h4>
NCPI FHIR IG defines the structure of a study using the following Resource Types (Entities):

<p align="center"><img src="https://github.com/NCPITest/Resources/blob/main/Images/research-study-structure.png" width="550" alt="High-level diagram of study structure in NCPI FHIR Implementation Guide"/>



<br>

Additional documentation can be found on the [NCPI FHIR IG GitHub](https://github.com/NIH-NCPI/ncpi-fhir-ig-2?tab=readme-ov-file).  


<h3> FHIR Aggregator </h3>

The [FHIR Aggregator](https://fhir-aggregator.org/) is an open-access tool for finding and downloading biomedical data from across the NIH developed for the interoperabiltiy project [Connecting FHIR, the CDA, and DRS Across NIH Cloud Resources](https://github.com/NIH-NCPI/Interoperability-Projects/blob/main/Project%20Descriptions/OHSU-FHIR.md). The aggregator indexes FHIR endpoints, and helps researchers identify and retrieve relevant biological samples and datasets. The FHIR Aggregator includes data from the Cancer Data Aggregator (CDA), Cellosaurus, Genomic Data Commons (GDC), Genotype-Tissue Expression Portal (GTEx), the Human Tumor Atlas Network (HTAN), the International Cancer Genome Consortium (ICGC), and 1000 Genomes project. 

<h4> FHIR as a Unifying Format for Genomic Research Data Tracking, Aggregation,  and Integration, 2025 </h4>
Multiple NCPI partners, including the FHIR WG and FHIR Aggregator project team, have submitted a paper on the use of FHIR in genomic research, which is now available as a [preprint](https://www.biorxiv.org/content/10.64898/2025.12.22.695544v1). 

<br>
<br>

[**Abstract**](https://www.biorxiv.org/content/10.64898/2025.12.22.695544v1): The increasing complexity of genomic research demands standardized data sharing and integration. The Fast Healthcare Interoperability Resources (FHIR) specification has become a well-established standard for exchanging data among health data systems. While designed primarily for clinical and patient data in health care environments, it also has applicability to represent genomic research data and offers a path for aggregating and integrating extremely rich datasets that have traditionally remained siloed and disparate. To study this potential, we developed FHIR Aggregator, an integration of seven major biomedical repositories, including the Genomic Data Commons, GTEx, HTAN, and DepMap, that covered 142334 patients, 819251 specimens, 1096491 observations and 711166 documents. We explore the various ways the FHIR standard can be applied to structure genomic research data and enable new possibilities. We demonstrate how FHIR can be used, where it succeeds or falls short, and which concepts must be extended to better support large-scale clinical and genomics research projects.



<h3> Untangling Participant-level Search for Faster and Compliant Data Discovery: A Review of Current and Prospective Policies and Technologies in Data Exploration in the NCPI Program </h3>

The NCPI [Search Working Group](https://github.com/NIH-NCPI/About/blob/main/Working-Groups.md#-search-working-group-) has developed a [whitepaper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5208394) on participant level search. The working group is refining a draft of this work, with hopes to submit to a peer-reviewed journal.

**Abstract**: The U.S. federal government has made significant advancements in genomic and biomedical data accessibility through the Database of Genotypes and Phenotypes (dbGaP) and NIH Cloud Platform Interoperability (NCPI) Program. These platforms aim to democratize access to data, enabling researchers to leverage large-scale datasets for scientific discovery while respecting privacy and consent constraints. The tools available for exploring these datasets can be categorized into three levels of search functionality: 1. study-level, 2. dataset-level, and 3. participant-level. Each of these levels serves distinct purposes and presents unique design and implementation challenges.


<h3> Watershed and Watershed-SV Models </h3> 

[Watershed](https://github.com/BennyStrobes/Watershed) is a probabilistic model that integrates both genomic and transcriptomic signals to predict the function or rare variants, published in 2020. The Watershed GitHub, detailing the model and how to run it, can be found here. Recently, Watershed has been made available on [Dockstore](https://dockstore.org/workflows/github.com/jasonbhn/Watershed-SV/Watershed-SV) through work on Jonhs Hopkins' [AnVIL-BDC interoperability project](https://github.com/NIH-NCPI/Interoperability-Projects/blob/main/Project%20Descriptions/JHU-AnVIL-BDC.md). [Watershed-SV](https://github.com/jasonbhn/Watershed-SV) expands Watershed to model the impact of rare structural variantws (SVs) on nearby gene expressions outliers.  
<br>
A cloud workspace demonstrating Watershed-SV analysis of 1000 genomes and MAGE data is publicly available on the [Terra platform](https://anvil.terra.bio/#workspaces/nccpi-rti-P01-002-JHU-TERRA/Watershed_SV_MAGE). Publications details on the development of both Watershed and Watershed-SV are provided below. 

<h4> Watershed - Transcriptomic signatures across human tissues identify functional rare genetic variation, 2020 </h4>

[**Abstract**](https://pubmed.ncbi.nlm.nih.gov/32913073/): Rare genetic variants are abundant across the human genome, and identifying their function and phenotypic impact is a major challenge. Measuring aberrant gene expression has aided in identifying functional, large-effect rare variants (RVs). Here, we expanded detection of genetically driven transcriptome abnormalities by analyzing gene expression, allele-specific expression, and alternative splicing from multitissue RNA-sequencing data, and demonstrate that each signal informs unique classes of RVs. We developed Watershed, a probabilistic model that integrates multiple genomic and transcriptomic signals to predict variant function, validated these predictions in additional cohorts and through experimental assays, and used them to assess RVs in the UK Biobank, the Million Veterans Program, and the Jackson Heart Study. Our results link thousands of RVs to diverse molecular effects and provide evidence to associate RVs affecting the transcriptome with human traits.


<h4> Watershed-SV - Integration of transcriptomics and long-read genomics prioritizes structural variants in rare disease, 2025 </h4>

[**Abstract**](https://pubmed.ncbi.nlm.nih.gov/40113264/): Rare structural variants (SVs)-insertions, deletions, and complex rearrangements-can cause Mendelian disease, yet they remain difficult to accurately detect and interpret. We sequenced and analyzed Oxford Nanopore Technologies long-read genomes of 68 individuals from the undiagnosed disease network (UDN) with no previously identified diagnostic mutations from short-read sequencing. Using our optimized SV detection pipelines and 571 control long-read genomes, we detected 716 long-read rare (MAF < 0.01) SV alleles per genome on average, achieving a 2.4× increase from short reads. To characterize the functional effects of rare SVs, we assessed their relationship with gene expression from blood or fibroblasts from the same individuals and found that rare SVs overlapping enhancers were enriched (LOR = 0.46) near expression outliers. We also evaluated tandem repeat expansions (TREs) and found 14 rare TREs per genome; notably, these TREs were also enriched near overexpression outliers. To prioritize candidate functional SVs, we developed Watershed-SV, a probabilistic model that integrates expression data with SV-specific genomic annotations, which significantly outperforms baseline models that do not incorporate expression data. Watershed-SV identified a median of eight high-confidence functional SVs per UDN genome. Notably, this included compound heterozygous deletions in FAM177A1 shared by two siblings, which were likely causal for a rare neurodevelopmental disorder. Our observations demonstrate the promise of integrating long-read sequencing with gene expression toward improving the prioritization of functional SVs and TREs in rare disease patients.





