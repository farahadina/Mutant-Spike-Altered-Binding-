# 🧬 3D Structural Modeling and Analysis of the Interaction Potential of SARS-CoV-2 Spike RBD Variants with ACE2 Using SWISS-MODEL

## Overview
This repository contains bionformatics project focused on modeling and analyzing the interaction between SARS-CoV-2 spike Receptor Binding Domain (RBD) variants and the human cell surafce Receptor Angiostensin-Converting-Enzymes 2 (ACE2) as the SARS-CoV-2 entry protein commonly found in the lungs, heart, and kidneys, using computational approaches. 

Proyek ini membandingkan antara: 
- Wild Type RBD (6M0J)
- Mutant N501Y RBD
- Triple Mutant Q493A/N501A/K417A RBD

Analisis yang dilakukan meliputi:
- Pemodelan struktur 3D 
- Validasi struktur
- Analisis RMSD 
- Analisis binding site 
- Analisis interaksi ikatan hidrogen 

---

## Poster Preview

<p align="center">
  <img src="Kelompok%2030_Poster%20Bioinformatics.png" width="900">
</p>

---

## Tujuan 
- Membuat dan memodelkan struktur 3D varian RBD spike SARS-CoV-2
- Memvalidasi struktur 3 varian RBD spike SARS-CoV-2
- Membandingkan perubahan struktur protein spike RBD spike SARS-CoV-2
- Menganalisis binding site ACES2 dan RMSD

---

## 🧪 Tools & Software
- SWISS-MODEL
- PyMOL
- Discovery Studio Visualizer
- MEGA X
- RCSB Protein Data Bank

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
- Structural differences were observed between the wild type and mutant RBD structures after mutation modeling.
- The wild type structure showed a more stable residue distribution and consistent interaction pattern with ACE2.
- The N501Y mutant exhibited moderate conformational changes around the binding interface while maintaining several important interactions.
- The triple mutant (Q493A + N501A + K417A) showed greater structural deviation and more noticeable changes in interaction patterns compared to the single mutant.
- Variations in hydrogen bond interactions and residue distribution suggest that each mutation may influence the stability of the RBD–ACE2 complex differently.
- Despite structural differences, all analyzed variants were still able to interact with the ACE2 receptor.

----

## 📂 Repository Contents

```bash
Kelompok 30_Poster Bioinformatics.png
Kelompok 30_Poster Bioinformatics.pdf
Kelompok 30_PPT Bioinformatics_compressed.pdf
Kelompok 30_Pemodelan Struktur 3D dan Analisis Potensi Interaksi Variasi Protein Spike RBD SARS-CoV-2 terhadap ACE2 dengan SWISS-MODEL.pdf
README.md
