# 🧬 Hemolytik 2.0 🩸

Welcome to the official data repository for **Hemolytik 2.0**, a comprehensive and manually curated database of experimentally validated hemolytic and non-hemolytic peptides. This resource is designed to support researchers in the rational design and development of safer, more effective therapeutic peptides. 👩‍🔬👨‍🔬

**🔬 About the Database**
Hemolytik 2.0 is an updated and significantly expanded version of the original Hemolytik database. Peptides are promising therapeutic agents, but their clinical use can be limited by hemotoxicity—the unintended destruction of red blood cells (RBCs). This database provides a centralized platform to explore the complex relationship between a peptide's sequence, structure, chemical modifications, and its hemolytic activity.

The data have been meticulously collected from over 4,533 peer-reviewed publications and established peptide repositories, including APD3, CAMP-R4, UniProt, and DRAMP4.0.

![Hemolytik 2.0 Overview](images/hemolytik2_overview.png)

---
**✨ Key Features**
Massive Dataset 📈: Contains 13,215 curated entries for over 7,500 unique peptides.

Rich Annotations 📝: Each entry includes detailed information such as amino acid sequence, biological source, terminal modifications (amidation, acetylation, etc.), stereochemistry (L, D, or mixed amino acids), and structural classification (linear, cyclic, branched, etc.).

Structural Information 🧬: Provides predicted tertiary structures and SMILES (Simplified Molecular Input Line Entry System) notations for over 10,615 peptides, enabling deep structure-activity relationship studies.

Functional Data 🎯: Includes peptides with diverse biological functions, such as antimicrobial, antibacterial, antifungal, anticancer, and cell-penetrating activities.

Focus on Modified Peptides 🧪: A significant portion of the database is dedicated to chemically modified peptides, which are crucial for enhancing therapeutic performance. The database includes information on non-canonical amino acids that are often used to optimize peptide drug candidates.
---
---

## 🔍 Overview

Hemolytik 2.0 provides experimentally verified peptide sequences along with detailed annotations such as:
- **Hemolytic activity status** (Hemolytic / Non-Hemolytic)
- **Physicochemical properties**
- **Source organism**
- **Functional nature** (e.g., Antimicrobial, Anticancer, Cytotoxic)
- **Chemical modifications** (C-terminal amidation, N-terminal acetylation, lipidation, etc.)
- **Structural and sequence information**
- **Reference literature (PubMed-linked)**

---

## 🌐 Web Server

Access the live web application here:  
👉 **[https://webs.iiitd.edu.in/raghava/hemopi2/](https://webs.iiitd.edu.in/raghava/hemopi2/)**

The web server offers modules for:
- **Prediction:** Identify hemolytic potential of peptides.  
- **Protein Scanning:** Detect hemolytic regions within full-length proteins.  
- **Motif Scan:** Locate hemolytic and non-hemolytic motifs.  
- **Design:** Generate and evaluate mutant peptides for reduced hemolytic activity.

---

## 📦 Dataset Download

The complete curated dataset of **Hemolytik 2.0** is available for academic use.  
You can download it directly from this repository:

- [`Hemolytik2_complete_data.csv`](link-to-your-file)
- [`Hemolytik2_fasta_sequences.fasta`](link-to-your-file)
- [`Hemolytik2_MAP_format.fasta`](link-to-your-file)
- [`Hemolytik2_chemical_modifications.csv`](link-to-your-file)

> 📘 **Note:** The dataset is intended for non-commercial, academic, and research purposes only.  
> Please cite the corresponding publication when using this resource.

---

## 📊 Key Statistics

| Category | Count |
|-----------|-------|
| Total Peptides | 13,215 |
| Hemolytic Peptides | 9,589 |
| Non-Hemolytic Peptides | 3,626 |
| Peptides with Non-Natural Amino Acids | 2,678 |
| Functional Categories | 30+ (Antimicrobial, Anticancer, Antifungal, etc.) |
| Source Categories | 20+ (Human, Horse, Sheep, Mouse, etc.) |

---

## 🧠 Citation

If you use **Hemolytik 2.0** in your research, please cite:

 
> **Singh, A., Raj SA, K., Rathore, A. S., & Raghava, G. P. S. (2025). Hemolytik2: An Updated Database of Hemolytic Peptides and Proteins.**  
> [Manuscript under review / Journal name, Year].


## ⚙️ Repository Structure

```
.
├── Hemolytik2_complete_data.csv
├── Hemolytik2_fasta_sequences.fasta
├── Hemolytik2_chemical_modifications.csv
├── source/
│   ├── Human
│   ├── Horse
│   └── ...
├── peptide type/
│   ├── L
│   ├── D
│   ├── Linear
│   └── ...
├── function/
│   ├── Antimicrobial
│   ├── Antibacterial
│   ├── Antifungal
│   └── ...
└── README.md
```

