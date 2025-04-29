# ABS Strike Zone EDA

**Authors:** Beili Chou, Charlie Braverman, Andrew Hack  
**Course:** QTM 302W, Spring 2025, Emory University

---

## 📖 Project Overview

This repository explores how the proposed Automated Ball-Strike (ABS) strike zone would have altered MLB hitter outcomes in 2024. It contains:

- **EDA_Notebook.Rmd** / **EDA_Notebook.html**  
  Full exploratory analysis of Statcast pitch data: computes old vs. ABS zones, per-player impacts, and team-level wOBA comparisons.

- **Presentation_Visuals.Rmd**  
  Streamlined notebook that produces key figures and tables for a research presentation: 2D density plots, bar charts, player & team rankings.

- **data/**  
  - `biofile_df.csv` (3.8 MB): Retrosheet biofile with player heights (in inches).  
  - `full_pitch_df.csv` (18.6 MB): Sample of enriched pitch-by-pitch data (50 000 rows) for rapid iteration.

- **references.bib**  
  Bibliography of external sources and package documentation.

- **QTM302W.Rproj**  
  RStudio project file.

- **renv/** & **renv.lock**  
  Reproducible package environment via **renv**.

---

## 🚀 Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/BeiliChou/MLBs-ABS-Zone-EDA-QTM302W.git
   cd MLBs-ABS-Zone-EDA-QTM302W
   ```
2. Open **QTM302W.Rproj** in RStudio.

3. Restore packages
   In the R console:
   renv::restore()

4. Render or run the notebooks
   EDA_Notebook.Rmd for full exploration (including optional full-season scrape).
   Presentation_Visuals.Rmd for slide-ready graphics (echo=FALSE by default).

## 📂 File Structure

abs-zone-eda/\
├── data/\
│   ├── biofile_df.csv\
│   └── full_pitch_df.csv\
├── EDA_Notebook.Rmd\
├── EDA_Notebook.html\
├── Presentation_Visuals.Rmd\
├── references.bib\
├── QTM302W.Rproj\
├── renv/\
├── renv.lock\
└── README.md

## 📝 Citation
If you use this work, please cite:

Chou, B., Braverman, C., & Hack, A. (2025). ABS Strike Zone Comparison EDA. QTM 302W, Emory University.

All external code and data sources are listed in references.bib.
