# SCImago — Analysis of SCImago SJR Data

## Overview

**SCImago** is a data analysis project focused on exploring and visualizing metrics from the *SCImago Journal & Country Rank* (SJR) dataset. The SJR dataset provides journal impact and scientific publication indicators derived from **Scopus®** data and is widely used in bibliometrics and scientometrics research. 

This repository contains:
- Python notebooks analyzing publication characteristics and patterns.
- A data folder with processed SCImago data.

### Folders
- **data/** — Structured SCImago Journal & Country Rank metrics (CSV, parquet, or similar).
- **Notebooks** — Jupyter notebooks with exploratory analysis and visualizations.

## What Is SCImago SJR Data?

*SJR (SCImago Journal Rank)* is an indicator that reflects the scientific influence of academic journals, accounting for both **citation counts** and the **prestige of citing journals**. It is an alternative to traditional metrics like impact factor and is freely available via the SCImago portal. 

The dataset typically includes:
- Journal identifiers and titles
- SJR indicator values
- H-index scores
- Country, subject area, and category classifications
- Yearly publication metadata

## Notebooks

### 📌 `publ-area-type-analysis.ipynb`
Explores how publication metrics vary across *scientific subject areas* and *journal types*. Typical analyses:
- Distribution of SJR by broad knowledge area
- Comparisons of metrics across publication types
- Trend analysis over years

### 📌 `publ-female-analysis.ipynb`
Investigates gender-related patterns in publications by linking author attributes (when available) to journal impact. Typical aims:
- Compare SJR or publication counts by author gender
- Visualize gender balance across subject areas

### 📌 `publ-female-analysis-add.ipynb`
Supplementary or extended notebook with additional visualizations and statistical tests building on the core female analysis.

## Citation

If you use this repository or the SCImago dataset in your research, please cite the SJR dataset as provided through the SCImago portal. 

## License

This project is licensed under the **MIT License**.
