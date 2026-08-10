# Donor Keratinocyte and Fibroblast IFNg Response

## Reproducibility

| Manuscript | analysis_20250204.pdf |
|---|---|
| Fig 1 data, but stats not reported.<br>Fibroblast data not in this figure. | Figure 5A |
| Fig 3A (Table 3), 3B (Table 5), 3C (Table 7). Table 4 and 6 stats not used in figures. | Figure 5B |
| Fig 6 (C) | Fig 4C |
| Fig 6 (D) | Fig 4D |
| Fig 4A (Table 12/13) | Fig 6A |
| Fig 4B (Table 14/15) | Fig 6B |
| Fig 4C (Table 16/17) | Fig 6C |
| Fig 5A (Table 18) | Fig 7A |
| Fig 5B (Table 19/20) | Fig 7B |
| Outdated Luminex data that was replaced by improved detection methodology | Fig 8 |
| Fig 6H (Table 27/28) | Cellprofiler data analysis |
| Fig 5C (Table 29/30) | Updated Luminex Data |

analysis_20250204.pdf was generated with the following command:
```{shell}
Rscript -e "rmarkdown::render('analysis.Rmd', output_file='reports/analysis_$(date +%Y%m%d).pdf')"
```

* Reports prior to 2026-02-24 was completed with preliminary datasets and can be used for data transparency but do not represent analysis of complete and final data sets.
* Additional reports correspond to sensitivity study and additional experiments for revision.

