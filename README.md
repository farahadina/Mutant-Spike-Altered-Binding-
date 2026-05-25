# 🧬 3D Structural Modeling and Analysis of the Interaction Potential of SARS-CoV-2 Spike RBD Variants with ACE2 Using SWISS-MODEL

## Overview
This repository contains bionformatics project focused on modeling and analyzing the interaction between SARS-CoV-2 spike Receptor Binding Domain (RBD) variants and the human cell surafce Receptor Angiostensin-Converting-Enzymes 2 (ACE2) as the SARS-CoV-2 entry protein commonly found in the lungs, heart, and kidneys, using computational approaches. 

This project compares: 
- Wild Type RBD (6M0J)
- Mutant N501Y RBD
- Triple Mutant Q493A/N501A/K417A RBD

The analyses performed included:
- 3D structure modeling 
- Structure validation
- RMSD analysis 
- Binding site analysis
- Hydrogen bond interaction analysis

---

## Poster Preview

<p align="center">
  <img src="Kelompok%2030_Poster%20Bioinformatics.png" width="900">
</p>

---

## Objectives 
- Create and model the 3D sturcture of SARS-CoV-2 RBD spike variants
- Validate the structure of three SARS-CoV-2 RBD spike variants
- Compare structural changes in the SARS-CoV-2 RBD spike protein 
- Analyze the ACE2 binding site and RMSD

---

## Tools & Software
- SWISS-MODEL, to create a 3D structure model of the spike protein
- PyMOL, as a protein visualization tools and RMSD analysis
- Discovery Studio Visualizer, as a hydrogen bond and bond distance analysis tool
- MEGA X, for sequence aligntmend and comparing protein sequence
- RCSB Protein Data Bank, serves as a provider of FASTA Protein 6MOJ data

---

## 🔬 Workflow

1. Retrieval of SARS-CoV-2 RBD structure from Protein Data Bank (PDB ID: 6M0J)
2. FASTA sequence extraction and in-silico mutation generation using MEGA X
3. 3D structure modeling of mutant proteins using SWISS-MODEL
4. Structural comparison and RMSD analysis using PyMOL
5. Binding interaction visualization using Discovery Studio:
   - Hydrogen bond analysis
   - Bond distance observation
   - Contact residue identification
6. Structural validation and quality assessment using:
   - Ramachandran Plot
   - Binding site confidence
   - GMQE
   - QMEANDisCo global score
7. Comparative analysis between wild-type and mutant structures
   
---

## Results

Table 1. SARS-CoV-2 RBD Structure Model Validation Results
| Model | GMQE | QMEANDisCo
|---|---|---|
| RBD SARS-CoV-2 Wild Type | 0.76 | 0.84 ± 0.05 |
| RBD SARS-CoV-2 Mutant N501Y | 0.77 | 0.52 ± 0.05 |
| RBD SARS-CoV-2 Triple Mutant | 0.74 | 0.65 ± 0.05 |

GMQE becomes a parameter initial model reliability based on template fit and sequence alignment, which was relatively high and stable for all three models. The values indicate all the three models had good reliability and a high fit to the template structure throughout the modeling process. The decrease in QMEANDisCo value for bothe mutant RBD models indicated that amino acid substitutions due to mutations cause local conformational changes in the protein structure.   

Table 2. Hydrogen Bond Distance Value 
| Variant RBD| RMSD (Å) |
|---|---|
| Wild Type | 0.312 |
| Mutant N501Y | 0.652 |
| Triple Mutant | 0.819 |

All hydrogen bond distances remained within stable interaction ranges (<3.5 Å), indicating preserved ACE2 binding capability despite mutations.

---

## 🧠 Main Findings

- Structural modeling of the SARS-CoV-2 wild type, N501Y mutant, and triple mutant (Q493A/N501A/K417A) showed that all RBD variants were still capable of interacting with the ACE2 receptor.
- Validation results based on GMQE, Global QMEANDisCo, and Ramachandran Plot analysis indicated that the generated protein models had acceptable structural quality.
- RMSD analysis and binding interaction observations revealed conformational differences and variations in binding site characteristics among the analyzed structures.
- Differences in hydrogen bond interactions and bond distances suggest that each mutation may influence the stability and interaction profile of the RBD–ACE2 complex differently.
- Overall, mutations in the RBD region contributed to structural and interaction changes that may affect ACE2 binding behavior and the adaptive properties of SARS-CoV-2 variants.
- These findings may provide useful information for further studies related to therapeutic development, inhibitor design, and vaccine evaluation against emerging SARS-CoV-2 variants.

----

## 📂 Repository Contents

```bash
Kelompok 30_Poster Bioinformatics.png
Kelompok 30_Poster Bioinformatics.pdf
Kelompok 30_PPT Bioinformatics_compressed.pdf
Kelompok 30_Pemodelan Struktur 3D dan Analisis Potensi Interaksi Variasi Protein Spike RBD SARS-CoV-2 terhadap ACE2 dengan SWISS-MODEL.pdf
README.md
