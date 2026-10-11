# Devising a breast cancer diagnosis protocol through machine learning

**Mujtaba T**, Hashmi SU, Imtiaz UB, Nusra SJF

*Brazilian Journal of Oncology*, 20 (2024) · [doi:10.1055/s-0044-1791655](https://doi.org/10.1055/s-0044-1791655)

**Keywords:** breast cancer · RNA-seq · machine learning · SVM · decision tree · STRING

## Summary
This study built a gene-expression-based diagnostic workflow for ER-positive / HER2-negative breast cancer from public RNA-seq data (ArrayExpress E-GEOD-52194, E-GEOD-75367 and E-GEOD-58135).

- Reads were processed in Galaxy: quality control (FastQC), alignment with HISAT2, duplicate removal, counting with featureCounts and differential expression with DESeq2 (FDR < 0.05).
- The resulting differentially expressed genes were used to train support vector machine and decision tree classifiers.
- The decision tree classifier reached **96.15 % accuracy** (F1 = 0.974).
- A STRING protein–protein interaction network and enrichment analysis characterised the biological processes and functions of the selected genes.

## Cite
```bibtex
@article{mujtaba2024breast,
  title   = {Devising a breast cancer diagnosis protocol through machine learning},
  author  = {Mujtaba, Tooba and Hashmi, Saif Ullah and Imtiaz, Usama Bin and Nusra, Sheikh Jameel Fathima},
  journal = {Brazilian Journal of Oncology},
  volume  = {20},
  year    = {2024},
  doi     = {10.1055/s-0044-1791655}
}
```

[← All publications](https://github.com/ToobaAwais)
