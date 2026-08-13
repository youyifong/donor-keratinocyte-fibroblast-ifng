# Donor Keratinocyte and Fibroblast IFNg Response

Multiple statistical models were completed for most data sets, including linear mixed models and student t test (paired or unpaired). Generally, linear mixed models were reported in the manuscript. In the case of Figure 6 the linear mixed model had low confidence due to limited replicates. In this case the student t test is reported in the manuscript. 

## Reproducibility

The following table shows the mapping between manuscript figures and report figures.

| Manuscript | Report Name | Table/Figure |
|---|---|---|
| Figure 1 | No statistics | No statistics |
| Figure 2 | analysis_20251114 | 2A: Fig 5B, page 5<br>2B: Fig 5C, page 6, second table down<br>2C: Fig 5D, page 8, second table down |
| Figure 3 | analysis_20251114 | 3A: Figure 5B, page 4<br>3B: Fig 5C, page 6, first table<br>3C: Fig 5D, page 8, first table |
| Figure 4 | analysis_20260224 | 4A: Table 12<br>4B: Table 14<br>4C: Table 16 |
| Figure 5 | analysis_20251114 (5A)<br>analysis_20260224 (5B and 5C) | 5A: Fig 7B and 7A, page 15, second table down<br>5B: Table 19<br>5C: Table 29<br>5D: No statistics |
| Figure 6 | analysis_20260224 | 6C: Table 9<br>6D: Tables 10 and 11<br>6H: Table 28 |
| S1Fig | analysis-for-rev----sens 3 | S1BFig: Table 3 |
| S2Fig | analysis-for-rev----sens 3 | S2AFig: Table 1<br>S2BFig: Table 1<br>S2CFig: Table 5 |

The report analysis_20250204.pdf was generated with the following command:
```{shell}
Rscript -e "rmarkdown::render('analysis.Rmd', output_file='reports/analysis_$(date +%Y%m%d).pdf')"
```

Additional reports correspond to sensitivity study and additional experiments for revision were rendered directly using RStudio menu.


