# Muscular-AChR
understanding the mechanism of binding of 3FTx and ligands to (α)2βγδ/ε Muscular  AChR
# 🧬 In Silico Investigation of 3FTX and Ligand Interactions with Muscular Nicotinic Acetylcholine Receptors

![MnAChR Docking](https://github.com/yourusername/yourrepo/assets/banner.png) <!-- Optional: Add a figure or schematic if you want -->

## 📌 Overview

This repository hosts the complete dataset, code, structural models, and analysis from the research paper:

**"In Silico Investigation of Snake Venom Three-Finger Toxin and Other Ligand Interactions with Muscular Nicotinic Acetylcholine Receptors Across Multiple Species: Implications for Neuromuscular Drug Development"**

The study explores the structural and functional dynamics of muscular nicotinic acetylcholine receptors (MnAChRs) from 10 mammalian species, focusing on their interaction with a snake venom-derived three-finger toxin (3FTX) and several small-molecule ligands using computational approaches.

## 🧪 Abstract

Three-finger toxins (3FTXs) derived from snake venom display potent neuromuscular blocking activity by binding strongly to muscular nicotinic acetylcholine receptors (MnAChRs). This study conducts a comprehensive **in silico** analysis across multiple mammalian species, utilizing **homology modeling**, **molecular docking**, and **molecular dynamics simulations** to evaluate the structural and interactional nuances of MnAChRs. Key findings include species-specific variations in binding affinities and structural adaptations at the receptor–toxin interface, offering insights into receptor pharmacodynamics, toxin sensitivity, and the design of targeted therapeutics or antivenoms.

## 📂 Repository Contents

| Folder/File | Description |
|-------------|-------------|
| `models/` | Homology models of MnAChRs for all 10 species (SWISS-MODEL output) |
| `dockings/` | HADDOCK and AutoDock4 docking result files (.pdb, .dlg) |
| `md_simulations/` | GROMACS input/output files, trajectories (.xtc), topologies (.top), and analysis scripts |
| `figures/` | Publication-quality figures (phylogenetic trees, structural models, docking interfaces, MD plots) |
| `ligands/` | Ligand structure files (.pdb, .mol2) used in docking |
| `scripts/` | Python and Bash scripts for structure prep, RMSD/RMSF/Rg analysis |
| `main_paper/` | Final research paper manuscript (DOCX & PDF) |
| `README.md` | This file |

## 🧬 Species Studied

- *Homo sapiens* (Human)
- *Mus musculus* (Mouse)
- *Rattus norvegicus* (Rat)
- *Oryctolagus cuniculus* (Rabbit)
- *Canis lupus familiaris* (Dog)
- *Capra hircus* (Goat)
- *Ovis aries* (Sheep)
- *Bos taurus* (Cow)
- *Sus scrofa domesticus* (Pig)
- *Macaca mulatta* (Monkey)

## 🧰 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **SWISS-MODEL** | Homology modeling of MnAChR subunits |
| **ClustalW / Clustal Omega** | Multiple sequence alignment & phylogenetics |
| **iTOL** | Visualization of phylogenetic trees |
| **HADDOCK 2.4** | Protein-protein docking (MnAChR–3FTX) |
| **AutoDock4** | Small-molecule docking with MnAChR |
| **GROMACS 2025.1** | Molecular dynamics simulations |
| **Chimera, Discovery Studio, LigPlot+** | Structure visualization and interaction analysis |
| **Open Babel, Python, Shell Scripts** | Ligand preparation, data processing |

## 🔍 Key Results

- **Sheep and goat** MnAChRs exhibited the strongest binding to 3FTX (−59.5 kcal/mol).
- Human receptors showed moderate binding (−23.4 kcal/mol), with fewer acidic residues at the binding site.
- 3FTX binding was stabilized by conserved aromatic and polar residues in MnAChRs across species.
- Pharmacological ligands like pancuronium showed high binding affinity (−11.03 kcal/mol), confirming their neuromuscular blocking potency.
- MD simulations confirmed structural stability of the 3FTX–MnAChR complex with low RMSD (~1.5 Å) and reduced Rg over time.

## 📖 Citation

If you use this repository, please cite:

```bibtex
@unpublished{sandeep2025MnAChR,
  author = {Sandeep R.},
  title = {In Silico Investigation of Snake Venom Three-Finger Toxin and Other Ligand Interactions with Muscular Nicotinic Acetylcholine Receptors Across Multiple Species},
  year = {2025}
}
