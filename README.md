# 🧬 Gene Expression Variability Analysis (GSE15852)

This project performs exploratory analysis of a publicly available microarray gene expression dataset from the Gene Expression Omnibus (GEO) to identify patterns of variability across biological samples.

---

## 📌 Objective

The goal of this analysis was to:

* Process raw gene expression data
* Explore distribution and sample relationships
* Identify highly variable genes
* Map probe IDs to gene symbols for biological interpretation

---

## 📂 Dataset

* **Source:** GEO (Gene Expression Omnibus)
* **Accession:** GSE15852
* **Platform:** Affymetrix Human Genome U133A Array
* **Samples:** 86
* **Genes (probes):** ~22,000

---

## ⚙️ Methods

* Data cleaning and preprocessing in R
* Conversion of expression values to numeric format
* Variance-based feature selection
* Probe-to-gene mapping using Bioconductor (`hgu133a.db`)
* Basic visualization (distribution plots, sample comparison)

---

## 🔍 Key Findings

* Identified highly variable genes including:

  * **HBB, HBA1** (hemoglobin-related)
  * **FABP4, AKR1C1, ADIPOQ** (metabolism-related)
  * **RPS3A, RPS20** (ribosomal proteins)
* Observed substantial variability across samples, suggesting biological heterogeneity
* Presence of hemoglobin genes may reflect sample composition or microenvironmental signals

---

## 🧠 Interpretation

Highly variable genes often represent key drivers of biological differences across samples. The identified genes include markers associated with metabolism, structural components, and cellular processes, indicating potential relevance to disease-related variability.

---

## 🛠️ Tools & Technologies

* R
* Bioconductor (`hgu133a.db`)
* GEO dataset

---

## 📊 Project Structure

```
analysis.Rmd     # Reproducible analysis
analysis.html    # Final rendered report
README.md        # Project overview
```

---

## 🚀 Future Improvements

* Differential expression analysis (e.g., limma)
* Clustering and heatmap visualization
* Principal Component Analysis (PCA)
* Functional enrichment analysis

---

## 👤 Author

**Mohit Swami**
MSc Medical Biochemistry, AIIMS New Delhi
Interested in computational biology, molecular mechanisms, and disease biology
