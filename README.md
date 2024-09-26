# Team Project Name

List of participants and affiliations:
- Kirtan Dave (Team Leader), Assistant Professor in Bioinformatics Research and development cell  Parul University 
- Narges SangaraniPour, Shahid Beheshti University of medical sciences 
- Edward Bird , Kansas State University, Interdepartmental Genetics
- Abolhassan Bahari , High Institute for Research and Education in Transfusion Medicine
- William Boateng , Noguchi Memorial Institute for Medical Research
- Chimenya Ntweya,Queen Elizabeth Central Hospital, Blantyre, Malawi
- Priyal Visavadiya, Gujarat Biotechnology University, Gandhinagar
- Precious Osadebamwen, Dalhousie University, Halifax, NS
- Mohamed A. Abouelkhair, Associate professor and founding faculty Diagnostic Medicine and Pathobiology, Rowan University New Jersey USA





## What is E-Guard (ESKAPE Pathogen Guard)?


Our project aims to develop a machine learning model for the rapid and accurate detection of ESKAPE pathogens, notorious for their antimicrobial resistance. The model is trained on genomic, phenotypic, and clinical datasets to improve diagnostic precision. By employing advanced feature extraction techniques and a scalable pipeline, we aim to streamline the identification of critical pathogens, contributing to better healthcare outcomes in the fight against antimicrobial resistance.
ESKAPE-specific genomes were sourced using BigQuery on Google Cloud. To avoid gene overrepresentation, guided assemblies were scrubbed, retaining only de novo assemblies. We generated two feature categories: sequence and annotation features. Sequence features include genomic markers like % GC content and protein features such as single amino acid and dipeptide counts. Annotation features were extracted using tools like PROKKA and MUMmer, focusing on gene annotations, pathway enrichment, and SNP-based clustering.

Keywords: ESKAPE pathogens, Machine learning, Genomic data, Phenotypic data, Clinical data, Model development, Diagnostic tool, public health

## Installation

Instructions for setting up the environment, installing dependencies, and running the project are provided in Install.txt

## Project structure

/genome: reference dataset
/feature_gen_lib: Scripts for feature extraction
/FEATURE-GEN: Training and testing data 


## Approach
![Workflow Image](https://github.com/NCBI-Codeathons/amr-2024-team-dave/blob/main/genome/workflow_team_dave.JPG)


## Results

## Future Work

## NCBI Codeathon Disclaimer
This software was created as part of an NCBI codeathon, a hackathon-style event focused on rapid innovation. While we encourage you to explore and adapt this code, please be aware that NCBI does not provide ongoing support for it.

For general questions about NCBI software and tools, please visit: [NCBI Contact Page](https://www.ncbi.nlm.nih.gov/home/about/contact/)

