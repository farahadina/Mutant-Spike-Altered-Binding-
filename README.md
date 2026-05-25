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

1. Retrieval of SARS-CoV-2 RBD structure from the RCSB Protein Data Bank (PDB ID: 6M0J)
2. Preparation and separation of ACE2 receptor and RBD complex structure
3. In-silico mutation generation for:
   - N501Y
   - Q493A + N501A + K417A
4. Homology modeling and structure optimization using SWISS-MODEL
5. Structural quality evaluation using:
   - GMQE
   - QMEANDisCo
   - Ramachandran Plot analysis
6. Structural comparison through RMSD analysis using PyMOL
7. Binding interaction analysis between ACE2 and RBD variants using Discovery Studio Visualizer
8. Comparative interpretation of structural stability and interaction profiles among all variants
   
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
- Structural analysis showed that mutations in the SARS-CoV-2 RBD region influenced the local conformation of residues involved in ACE2 binding. Differences in residue arrangement and interaction patterns were observed among the wild type, N501Y mutant, and triple mutant structures.
- The wild type structure demonstrated a more compact and stable conformation, with most residues distributed within the favored region of the Ramachandran plot. Hydrogen bond interactions between RBD and ACE2 were also observed consistently, indicating stable binding behavior.
- In the N501Y mutant, several local conformational changes were detected around the binding interface. Residue distribution slightly shifted toward the allowed region, suggesting increased flexibility in specific areas of the structure. However, the overall interaction with ACE2 remained relatively stable, and several important binding interactions were still maintained.
- Compared to the wild type and single mutant, the triple mutant (Q493A + N501A + K417A) showed greater structural deviation. The residue distribution appeared more dispersed, accompanied by changes in hydrogen bond interactions and reduced structural compactness in several regions. These findings suggest that multiple mutations may affect the stability and interaction profile of the RBD–ACE2 complex more noticeably.
- Overall, all analyzed variants retained the ability to interact with the ACE2 receptor, although each mutation produced different structural and interaction characteristics that may influence binding stability.

----

## 📂 Repository Contents

```bash
Kelompok 30_Poster Bioinformatics.png
Kelompok 30_Poster Bioinformatics.pdf
Kelompok 30_PPT Bioinformatics_compressed.pdf
Kelompok 30_Pemodelan Struktur 3D dan Analisis Potensi Interaksi Variasi Protein Spike RBD SARS-CoV-2 terhadap ACE2 dengan SWISS-MODEL.pdf
README.md
