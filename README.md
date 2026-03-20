# Deterrent Effects of DUI Punishment at the 0.08 BAC Threshold: Evidence from a Regression Discontinuity Design

## Summary

This project examines whether harsher punishments for drunk driving reduce the probability of future DUI offenses. Using a dataset of approximately 214,558 traffic stops in Washington State starting from 1999, we apply a Regression Discontinuity Design (RDD) to estimate the causal effect of stricter DUI punishment on recidivism. The legal BAC threshold of 0.08 serves as the cutoff — drivers just above and just below this limit are compared to isolate the effect of punishment.

Our results suggest that crossing the 0.08 BAC threshold and receiving harsher punishment reduces the probability of future DUI offenses by approximately 2.02 percentage points, representing a 17.4% reduction relative to the baseline recidivism rate of 11.96%. These findings support the deterrent effect of current DUI enforcement policy in Washington State.

---

## Files

| File | Description |
|------|-------------|
| `Deterrent_Effects_DUI.qmd` | Raw Quarto document containing all analysis, code, and written sections |
| `Deterrent_Effects_DUI_writeup.pdf` | Rendered PDF writeup with non-visible code |
| `Presentation_ECON.pptx` | Slide deck summarizing the findings |
| `Writeup.docx` | Full report |
| `Video` | Recorded presentation |

---

## How to Run

1. Clone this repository
2. Open `Deterrent_Effects_DUI.qmd` in RStudio
3. Make sure the following R packages are installed:
```r
install.packages(c("rdrobust", "ggplot2", "fixest", "vtable", "tidyverse", "rio", "rddensity"))
```

---

## Authors

- Liliya Dimova
- Brenda Hernandez Barragan
- Cesar Lagos Davila
- Xuanzhi Lu
- Tien Nguyen
- Zion Yates

---

## Course

BUAN 5310 — Econometrics  
Instructor: Nicholas Huntington-Klein  
Seattle University — March 2026
