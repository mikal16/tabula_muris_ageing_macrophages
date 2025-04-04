# 🧬 Aging & Macrophage Dysfunction Across Tissues

This project explores effect of **aging** on **macrophage identity and function** across multiple murine tissues using the **Tabula Muris** dataset.

---

## 📚 Project Overview

This project focuses on:
- Comparing **young** vs **aged** macrophage populations.
- Major age groups are **1m**, **3m**, **18m**, **21m**, **30m**.
- Investigating just male, but actually can do this analysis seperately for both.
- Investigating **cellular composition**, **gene expression**, and **signaling pathways**
- Using both **FACS** and **Droplet-based single-cell RNA-seq** modalities

---

## 🗃️ Datasets: Tabula Muris Senis

I'm analyzing data from the [Tabula Muris Senis project](https://tabula-muris-senis.ds.czbiohub.org/), which provides high-resolution single-cell transcriptomes from aging mice.

Data obtained from [Figshare Website](https://figshare.com/projects/Tabula_Muris_Transcriptomic_characterization_of_20_organs_and_tissues_from_Mus_musculus_at_single_cell_resolution/27733)

Data obtained from 
### 🔬 Technologies Used:

| Method   | Description | Strengths | Limitations |
|----------|-------------|-----------|-------------|
| **FACS** (Smart-seq2) | Fluorescence-activated cell sorting | High sensitivity, full-length transcripts, low dropout | Fewer cells, more expensive |
| **Droplet** (10x Genomics) | Microfluidic-based capture of single cells | High throughput, more cell types captured | 3' bias, lower sensitivity, higher dropout |

---

## 🎯 Goals

- ✅ Filter out **non-macrophage** populations
- ✅ Compare cell proportions across **age groups**
- ✅ Visualize **UMAPs**, **violin plots**, and **differential expression**
- ✅ Explore **NRF2 (Nfe2l2)** and other aging-related regulators
- 🔜 Integrate FACS and Droplet data for cross-validation

---
