## Astur Genomics

## 1. Overview

This repository contains code and data used in:

- **Publication:** Goshawk genomics: Genome wide Single Nucleotide Polymorphisms (SNPs) confirm Species Status of *Astur gentilis* and *Astur atricapillus*  

- **Authors:**  
  Florian Kunz<sup>1,2</sup>, Min Chai<sup>2,3</sup>, Martin Schwentner<sup>4</sup>, Frank Emmanuel Zachos<sup>3,5,6,7</sup>, Martin Kapun<sup>2</sup>, Elisabeth Haring<sup>2,5</sup>  

- **Affiliations:**  
  <sup>1</sup> BOKU University, Vienna, Department of Ecosystem Management, Climate and Biodiversity, Institute of Wildlife Biology and Game Management, Gregor-Mendel-Straße 33, 1180 Vienna, Austria  
  <sup>2</sup> Natural History Museum Vienna, Central Research Laboratories, Burgring 7, 1010 Vienna, Austria  
  <sup>3</sup> Natural History Museum Vienna, 1st Zoological Department, Burgring 7, 1010 Vienna, Austria  
  <sup>4</sup> Natural History Museum Vienna, 3rd Zoological Department, Burgring 7, 1010 Vienna, Austria  
  <sup>5</sup> University of Vienna, Department of Evolutionary Biology, Djerassiplatz 1, 1030 Vienna, Austria  
  <sup>6</sup> University of the Free State, Department of Genetics, Bloemfontein, South Africa  
  <sup>7</sup> Charles Darwin University, Research Institute for the Environment and Livelihoods, Casuarina, NT, Australia  

- **DOI / URL:** \<DOI – will be added\>  

**Short summary:**  
This repo contains the files and codes used in the publication. Raw reads used in the bioinformatic pipeline are stored in the Sequence Read Archive (SRA) under the BioProject Accession number PRJNA1432726 (ID: 1432726). BioSample Accession numbers range from SAMN56347845 to SAMN56347940 (see supplement of publication).

---

## 2. Repository Structure

```text
<repo-root>/
├─ final_files/            # Processed data used as input for phylogenetic analyses
├─ scripts/                # Helper scripts used throughout the pipeline
├─ shell/                  # shell scripts produced and called in the main_analysis_pipeline
├─ main_analysis_pipeline  # Main analysis pipeline, from raw data to final files
└─ README.md               # This file
