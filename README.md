# 🧬 Optimized qPCR Primer Set for Mouse Genes (Tm 60°C)

This repository contains a validated set of primers for **20 mouse genes** (Target & Reference genes) designed for high-efficiency Real-Time PCR (SYBR Green). All primer pairs are optimized to run simultaneously under the same thermal profile.

---

## 🛠 Methodology
The primers were designed and validated using the following bioinformatic pipeline:

1.  **Sequence Retrieval:** mRNA confirmed sequences (RefSeq) from **NCBI GenBank**.
2.  **Primer Design:** Using **Primer-BLAST** with a focus on **Exon-Exon Junction Spanning** to eliminate gDNA interference.
3.  **Thermodynamic Analysis:** Secondary structures (Hairpin, Self-Dimer, Hetero-Dimer) were analyzed via **IDT OligoAnalyzer**.
4.  **Tm Optimization:** All primers are normalized for an **Annealing Temperature ($T_a$) of 60°C**, allowing for a **Single-Run** plate analysis.



---

## ✅ Quality Control (QC) Analysis

* **Specificity:** Verified 100% specificity against the *Mus musculus* genome using **BLAST**. No significant off-target binding was detected.
* **Dimer Profile:** Challenging genes (e.g., **GAS6**, **TGF-β1**) were screened with high sensitivity. Selected pairs maintain an optimal $\Delta G$, ensuring clean **Melt Curves** at 60°C.
* **Amplicon Length:** Optimized between **94 to 142 bp** for maximum PCR efficiency.

---

## 📊 Data Files
You can access the primer sequences and details through the files below:
* [📄 Download Primer List - Part 1 (CSV)](Primers_Part1.csv)
* [📄 Download Primer List - Part 2 (CSV)](Primers_Part2.csv)

---

## 🔗 External Tools Used
* [NCBI Primer-BLAST](https://www.ncbi.nlm.nih.gov/tools/primer-blast/)
* [IDT OligoAnalyzer](https://eu.idtdna.com/calc/analyzer)
* [NCBI GenBank](https://www.ncbi.nlm.nih.gov/genbank/)

---

## 📝 License
This project is open-source. Please cite this repository if you use these primer sequences in your research.
