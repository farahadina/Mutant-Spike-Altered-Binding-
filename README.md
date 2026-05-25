# 🧬 ⁠Pemodelan Struktur 3D dan Analisis Potensi Interaksi Variasi Protein Spike RBD SARS-CoV-2 terhadap ACE2 dengan SWISS-MODEL

## 📌 Gambaran Umum
Repositori ini berisi proyek bioinformatika yang berfokus pada pemodelan dan analisis interaksi antara varian spike Receptor Binding Domain (RBD) SARS-CoV-2 dan Receptor permukaan sel manusia Angiotensin-Converting-Enzymes 2 (ACE2) sebagai protein pintu masuk SARS-CoV-2 yang umumnya ditemukan di paru-paru, jantung dan ginjal, menggunakan pendekatan komputasional.

Proyek ini membandingkan antara: 
- Wild Type RBD (6M0J)
- Mutant N501Y RBD
- Triple Mutant Q493A/N501A/K417A RBD

Analyses performed include:
- 3D structure modeling
- Structural validation
- RMSD analysis
- Binding site analysis
- Hydrogen bond interaction analysis

---

## 🖼️ Poster Preview

<p align="center">
  <img src="Kelompok%2030_Poster%20Bioinformatics.png" width="900">
</p>

---

## 🎯 Objectives
- Model 3D structures of SARS-CoV-2 Spike RBD variants
- Compare structural conformational changes
- Analyze ACE2 binding interactions
- Evaluate protein stability and interaction potential

---

## 🧪 Tools & Software
- SWISS-MODEL
- PyMOL
- Discovery Studio Visualizer
- MEGA X
- RCSB Protein Data Bank

---

## 🔬 Workflow
1. Protein sequence retrieval from RCSB PDB
2. In-silico mutation generation
3. 3D structure modeling using SWISS-MODEL
4. Structural validation using:
   - QMEANDisCo
   - GMQE
   - Ramachandran Plot
5. RMSD comparison with PyMOL
6. Binding interaction analysis using Discovery Studio

---

## 📊 Key Results

| Variant | RMSD (Å) |
|---|---|
| Wild Type | 0.312 |
| Mutant N501Y | 0.652 |
| Triple Mutant | 0.819 |

All hydrogen bond distances remained within stable interaction ranges (<3.5 Å), indicating preserved ACE2 binding capability despite mutations.

---

## 🧠 Main Findings
- Mutations affect local conformational structures in the RBD binding interface.
- Triple mutations produce greater structural deviation compared to single mutations.
- All variants maintain interaction capability with ACE2 receptors.

---

## 📂 Repository Contents

```bash
Kelompok 30_Poster Bioinformatics.png
Kelompok 30_Poster Bioinformatics.pdf
Kelompok 30_PPT Bioinformatics_compressed.pdf
Kelompok 30_Pemodelan Struktur 3D dan Analisis Potensi Interaksi Variasi Protein Spike RBD SARS-CoV-2 terhadap ACE2 dengan SWISS-MODEL.pdf
README.md
