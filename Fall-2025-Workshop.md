<h1> Fall 2025 NCPI Workshop </h1>

The 2025 NCPI Fall Workshop took place on September 25-26 in Rockville, Maryland. The workshop convened Interoperability Project Teams, NCPI Steering Committee members, and other colleageus from across the NIH. 
The workshop focused on reviewing NCPI progress, sharing lessons learned, identifying opportunities for collaboration across NIH Data Ecosystems, and fostering new connections among participants. 

The meeting agenda for the workshop can be found [here](Workshop_Resources/NCPI_Fall_2025_Workshop_Public_Agenda.pdf)

<h2> Interoperability Demonstrations </h2>
At the workshop, representatives from NCPI Interoperability projects gave a series of demonstrations showcasing recent progress in interoperability across NCPI. 


----------------------------------------------

<h3> Watershed Demonstration </h3>

<a href = "https://www.youtube.com/watch?v=-ry91cDRVwI">
<img src="https://github.com/NCPITest/Resources/blob/main/Images/Watershed-Demo.jpg"
  style="border: 2px solid #007CB0; border-radius: 8px;"
  align="right"
  alt="Video Thumbnail for Watershed Demonstration including project title, presenter, and date"
  width="550" />

</a>
  
Dr. Schatz’s work on the AnVIL-BioData Catalyst Interoperability project aims to leverage GTEx, T2T, and HPRC datasets to study rare genetic variants in TOPMed cohorts. 
Watershed is a hierarchical Bayesian model that predicts regulatory effects of rare variants on nearby gene expressions. The Watershed-SV model extends this functionality to predicting the impact of rare structural variants. Watershed pipelines have been adapted to cloud analysis platforms, and are openly available through Dockstore. 

This demonstration walks through the process of finding data, using the Watershed pipelines, and data analysis in AnVIL and BDC. 

------------------------------------------

<h3> PFB Imports from AnVIL to CAVATICA </h3>
<a href = "https://www.youtube.com/watch?v=GzvNG9Omlj4">
  <img src="https://github.com/NCPITest/Resources/blob/main/Images/PFB-export-demo.jpg"
    align="left"
    alt="Video Thumbnail for PFB Import Demonstration"
    width="550"/> 
</a>

Portable Format for Bioinformatics (PFB) is an Avro-based file format that bundles data, schema, ontologies, and pointers to data files in a single backage, and can be easily sent across systems, with built-in flexibility for different data models. 

This demonstration shows PFB handoff from the AnVIL Data Explorer to Kids First CAVATICA, allowing for analysis of AnVIL data in the CAVATICA environment. 
Once implemented, users will be able to build cohorts in the AnVIL Data explorer, and export the cohort to CAVATICA while passing a PFB manifest, and eventually analyze the data in CAVATICA alongside other data. Implementation of this feature is expected in Q1 of 2026. 

<br>

------------------------------------------

<h3> Kids First dbGaP ImmPort FHIR and DRS in CAVATICA </h3>
<a href = https://www.youtube.com/watch?v=AvG2mu5KtTw>
  <img src="https://github.com/NCPITest/Resources/blob/main/Images/KF-dbGaP-ImmPort-FHIR.jpg"
  align="right"
  alt="Video Thumbnail for KidsFirst dbGaP ImmPort FHIR and DRS in CAVATICA"
  width="550"</>
</a>

At the Fall Workshop, the team from P01-003, the KidsFirst-dbGaP-ImmPort Project, presented the two use cases within their project work: (1) Phenotypic Expansions of Structural Birth defects using Kids First and Undiagnosed Disease Network Data and (2) Identifying the genetic and environmental determinants impacting Asthma Severity in Children.  After giving brief project updates, they gave a demonstration on connecting FHIR with DRS files in CAVATICA, enabling interoperability between platforms. 
